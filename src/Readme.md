# Common Domain (by Jonathan Oliver)

A project for easily using event sourcing with a domain model. Implements 
most of the important concepts discussed on the ddd-cqrs mailing list.

Some documentation can be found at:

 * [haf/CommonDomain/wiki](https://github.com/haf/CommonDomain/wiki)
 * in the unit tests (great reading - just browse the code and run the tests
   with machine.specifications at the same time!)
 * By browsing the [Documently](https://github.com/haf/Documently) source.
 
Issues and pull requests go here:
https://github.com/joliver/CommonDomain

unless you want a new nuget out with some commits, in which case you can either talk above,
or send [me](https://github.com/haf) a message.

Note: this project will be shoved into [joliver/EventStore](https://github.com/joliver/EventStore)
by EventStore's next release.

## Working with the project:

`git clone ...`
`git submodule update --init`
`build.bat`

or:

`install-package CommonDomain`