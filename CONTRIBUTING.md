# How to contribute

I'm really glad you're reading this, because we need volunteer developers to help this project come to fruition.

If you haven't already, come find us in [Slack](https://join.slack.com/t/quantummaid/shared_invite/zt-cx5qd605-vG10I~WazfgH9WOnXMzl3Q). We want you working on things you're excited about.

Here are some important resources:

  * [QuantumMaid](http://quantummaid.de/)
  * [Twitter](https://twitter.com/quantummaid)
  * [Slack](https://quantummaid.slack.com/) (follow [here](https://join.slack.com/t/quantummaid/shared_invite/zt-cx5qd605-vG10I~WazfgH9WOnXMzl3Q) to join)
  * [Gitter](https://gitter.im/quantum-maid-framework/community)
  * [Our Code of Conduct](CODE_OF_CONDUCT.md)

## Bugs and feature requests
To report a bugs or request a feature, please do so using [GitHub issues](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request).
All issues are accepted in the English language.

## Reporting vulnerabilities
Please refer to our [security policy](SECURITY.md) in order to report security vulnerabilities.

## Submitting changes

Please send a [GitHub pull request](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request) to the QuantumMaid sub-project you'd like to contribute to with a clear list of what you've done.
When you send a pull request, we will love you forever if you include tests. Please follow our coding conventions (below).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

## Coding conventions
QuantumMaid's coding conventions are based on the popular book [Robert C. Martin: Clean Code - A Handbook of Agile Software Craftsmanship](https://www.oreilly.com/library/view/clean-code/9780136083238/).
The conventions are enforced by our [Maven configuration](https://github.com/quantummaid/quantummaid-opensource-parent).
Start reading our code and you'll get the hang of it.

## Copyright
All contribution must be signed off using the [Developer Certificate of Origin](https://developercertificate.org/).

Submitting a contribution implies this agreement. Nonetheless a "Signed-off-by" tag in every patch is required as confirmation that you agree. The following git command can be used:

    git commit --signoff
        
All contributions must be released under the same license as the project the contribution is made to.

## Building the projects from source
All QuantumMaid projects use Maven to build. You can build a project from source like this:
```bash
mvn clean package
```

## Testing
All functionality in all QuantumMaid projects is tested in an end-to-end fashion. 
The test suite of any QuantumMaid project can be run like this:
```bash
$ mvn clean verify
``` 
Please write tests in the same way for new code you create.
