## Hi there 👋

**GherKing** is a tool to make Gherkin smarter! It allows you to handle Cucumber/Gherkin feature files programatically, in your JavaScript/TypeScript code.

### What can you do with **GherKing**?

* You can use the [gherkin-ast](https://github.com/gherking/gherkin-ast) package to build and work with feature files in your code, using an **AST**.
* You can load feature files to AST and save them back using the [gherkin-io](https://github.com/gherking/gherkin-io) package; and the [gherkin-formatter](https://github.com/gherking/gherkin-formatter) to make them pretty.
* You can use the [gherking](https://github.com/gherking/gherking) CLI tool (and the precompilers below) to build a precompiler for your feature files, adding more logic and **magic 🌈** to your feature files.

### Our precompilers

* **Replacer** - [gpc-replacer](https://github.com/gherking/gpc-replacer)<!-- @gula --> - to use variables in your feature files
* **For Loop** - [gpc-for-loop](https://github.com/gherking/gpc-for-loop)<!-- @6ai --> - to repeace certain scenarios many times
* **Macro** - [gpc-macro](https://github.com/gherking/gpc-macro)<!-- @moni --> - to shoren your feature files by using reusable step groups (macros)
* **Remove Duplicates** - [gpc-remove-duplicates](https://github.com/gherking/gpc-remove-duplicates)<!-- @6ai --> - to clean up your feature files from duplicate tags/data rows
* **Scenario Numbering** - [gpc-scenario-numbering](https://github.com/gherking/gpc-scenario-numbering)<!-- TBD --> - to mark your scenarios/outlines with an index to help reading
* **Scenario Outline Numbering** [gpc-scenario-outline-numbering](https://github.com/gherking/gpc-scenario-outline-numbering)<!-- TBD --> - to mark your scenario outline rows with an index to help reading
* **Scenario Outline Expander** [gpc-scenario-outline-expander](https://github.com/gherking/gpc-scenario-outline-expander)<!-- TBD --> - to resolve scenario outlines to scenarios
* **Step Group** [gpc-step-groups](https://github.com/gherking/gpc-step-groups)<!-- TBD --> - to make the step keywords more readable

### Precompilers we plan

Do you have an idea for a cool precompiler? [Send your idea to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=precompiler-request.md&title=%5BGPC%5D+The+name+of+the+precompiler)

* **Sorter** - to sort scenario/outline based on certain conditions (https://github.com/gherking/gherking/issues/52)
* **Filter** - to filter scenario/outline based on tags/outher conditions (https://github.com/gherking/gherking/issues/40)
* **Splitter** - to split each scenario/outline to separate feature files, to improve parallelization (https://github.com/gherking/gherking/issues/44)
* **Suite Generator** - to sort feature files and scenarios/outlines in separate files, based on suite-tags (https://github.com/gherking/gherking/issues/45)
* **Example Sampler** - to chose a given number of random example (https://github.com/gherking/gherking/issues/37)
* **Test Data** - to insert test data to feature files (https://github.com/gherking/gherking/issues/21)

### Precompilers made by the community

Do you have a precompiler you implemented? [Send it to us!](https://github.com/gherking/gherking/issues/new?assignees=judit-nahaj%2C+szikszail&labels=enhancement&template=precompiler-request.md&title=%5BGPC%5D+New+OSS+precompiler) And we will list here!
