# Contributing

Great to have you here. These are a few ways you can help make this project better:

- scratch an itch and implement a new feature using our [workflow](#workflow)
- add an example to README.md
- avoid sending pull requests related to "style" or whitespace as we have
  tools in our workflow to do this already
- [creating a new issue](http://github.com/imlucas/mongodb-version-manager/issues)
  if there is something you need this project to do that it currently doesn't.
  We're always more than happy to chat about other projects.

## Workflow

1. Fork the repository on GitHub
1. Create a branch with a name that breifly describes your feature
1. Implement your feature or bug fix
1. Add new cases to `./tests.js` that verify your bug fix or make sure no one
   unintentionally breaks your feature in the future and run them with `npm test`
1. Add comments around your new code that explain what's happening
1. Commit and push your changes to your branch then submit a pull request

Don’t get discouraged! We estimate that the response time from the
maintainers is less than 24 hours.

## Bugs

It would be extremely helpful, if you have the time, to
look at existing bugs and help us understand if:

* The bug is reproducible?
* Is it reproducible in other environments (browsers)?
* If they weren't included originally, what are the steps to reproduce?

You can report new bugs by
[creating a new issue](http://github.com/imlucas/mongodb-version-manager/issues).
Please include as much information as possible about your environment
("I am using node.js v 0.10.28 on OSX Mavericks").  Actual code is always
more valuable than an explanation, so please include a link to a GitHub
gist or include a snippet directly in your issue description.

## Versioning

This library aims to adhere to [Semantic Versioning 2.0.0](http://semver.org/).
Violations of this scheme should be reported as bugs. Specifically, if a
minor or patch version is released that breaks backward compatibility,
that version should be immediately yanked and/or a new version should be
immediately released that restores compatibility.

## Pro

If you've been doing JS for awhile, thanks for checking this out.  The quick
version of the house rules are:

- Indent 2 spaces
- Single quotes > double quotes
- Don't use ASI
- Maximum line length is 80
- Don't check in `dist` files
- Avoid mutation
- Write tests that make sense
- Test must always be green
