EclipseRCP_MAIL2.0
==================
В Eclipse есть стандартный шаблон RCP-приложения.
Говорят, он хорошенько устарел.
Парни усовершенствовали шаблон. Добавили новые штуки,
появившиеся после 2009 года.
Сделали тюториал. Поэтапно строят большое приложение.

[Home Page](http://max-server.myftp.org/trac/rcp-mail)

[Eclipse RCP examples](http://www.ralfebert.de/archive/eclipse_rcp/rcp_examples/)

RCP Mail 2.0 is an enhanced version of the "RCP Mail" template which comes with Eclipse. It was created by Michael Scharf, Kai Toedter, Boris Bokowski, Francis Upton IV, Frank Gerhardt and Paul Webster for their EclipseCon 2009 tutorial "RCP Mail 2.0: Commands, Common Navigator, and Data Binding ". The project is currently in discussion for inclusion as an official example, see bug #253105 and #290029.

It shows best practices for RCP features like Commands, Handlers, Data Binding, Common Navigator and Branding.

To setup the project, download the sources from the RCP Mail 2.0 site. In /steps/handout you'll find some instructions. Just import the projects from the archive file using Import > Existing projects into Workspace. Choose to import rcpmail-99 and execute the included launch configuration rcpmail-99.launch.


Steps
-----
* 00: Original RCP Mail 1.0
* 01: Introduction of the Model (and artwork)
* 02: The New Server Wizard
* 03: Adding data binding
* 04: Adding validator and error messages
* 05: Adding field decorations
* 06: Using data binding in the NavigationView (ContentProvider)
* 07: Adding a view with a table of Messages
* 08: MessageView: 1. use selection of NavigationView, 2. bind table contents to selection details
* 09: Exercise: port binding with validator
* 10: Commands: add/change About, New Server command, ways of placing it in the UI,
MarkAsSpam command, consolidate predefined actions/commands, Sync command,
enabledWhen, visibleWhen, Delete command
* 11: Exercise: File/Exit and New Window command: exercise
* 12: CNF instead of SimpleNavigator, change in-place
* 13: Add Contacts plugin model and content/label providers
* 14: Exercise: Hook Contacts plugin to CNF
