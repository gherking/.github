# Contribution guideline

**GherKing** is an Open Source ecosystem, a collection of Open Source NPM package.
You are highly welcome to contribute and make GherKing better!

When contributing to **GherKing**, please follow this guidelines, in order to keep GherKing in a good quality to deliver benefits to our users.

## "I have a new idea!"

We are on it to make **GherKing** a usefull tool to make Gherkin better!

But we cannot think of all cases and useful feature to add to the tool. If you have an idea, either for a **feature** in any GherKing package, or for a **new gherkin precompiler (GPC)**, share it with us and make it happen!

**Create an issue** and describe your idea with us!

**Important**: Please be reasonable with your idea! Not all idea would bring benefit to our users, as much as you first think, e.g. Making a precompiler what replaces all words with "Nyan cat", should funny, but not too helpful ;) Long story, short, keep still keep the right to govern the GherKing packages and reject ideas.

## "I found an issue"

Something does nto feel right in GherKing, when you use it, it is sus.

**Create an issue** and describe your issue! Let us look on it and fix it - or you can also fix it by yourself!

## Development guidelines

If you decided to develop any gherking package, please keep in mind these points, when contributing:

1. **Create an issue** - eventhough GherKing is OS, still we apply software development processes. Creating an issue helps to track and plan our activities. We create **issue templates** to help you create the right issue containing necessary information.
2. **Fork the repository** - in general feel free to fork any of our repositories, all our packages licensed as MIT. But this is crucial, when you contribute. Make your own fork, and work there. When you are done, create a **Pull request** to the main repository.
3. **Implement your code** - when changing any GherKing code, please keep in mind
   - the good development practices, such as the **Clean Code** and **Clean Design** principles,
   - making your code **tested** by unit or integration
   - making your changes **documented** in `CHANGELOG.md` and/or `README.md`. As we use TypeScript, JSDocs are not necessary.
4. **Test your code** - before you should create a pull request, ensure your code work, both by testing your code with unit tests, and simply trying it out by yourself.
5. **Create a pull request** - when you are done and ready to add publish your changes, create a pull request to the main repository, describe your changes, what you have done. We created **Pull request templates** to help you create an informative pull request, see [GherKing pull request templates](https://github.com/gherking/.github/tree/main/.github/PULL_REQUEST_TEMPLATE) and [About automation for issues and pull requests with query parameters](https://docs.github.com/en/github/managing-your-work-on-github/about-automation-for-issues-and-pull-requests-with-query-parameters) on how to use them.

**+1**: Do not forget to add your name and e-mail to the `contributors` field of the `package.json` file ;)
