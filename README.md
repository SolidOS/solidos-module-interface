# solidos-modules-interface
The way a solid-os module describes itself, is loaded and called.

An operating system for Solid, like solidos, or the podbrowser, or a number of other
pod managers, and generic user portals into the solid world, typically different
 code modules to allow the user to view, interact with and create different sorts of solid things,
like contacts, groups, resources, chats, medical and fitness data and so on.
These modules have been variously called panes, views, applets and so on and the best
name for them may not yet have been found. Here we will talk about 'panes' as that
the terminolgy used by `solid-panes` but we will also talk abut the modules
which are loaded in order to provide the UX functionality of the panes.

The goal of this repo is to document the interface to a pane.

- The typescript/JS interface of the pane code when it is loaded
- An RDF shape for information about a pane and the corresponding loadable code
- The algorithm for selecting panes to display to the user
