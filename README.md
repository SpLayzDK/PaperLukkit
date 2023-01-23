# PaperLukkit
PaperLukkit is a fork of Lukkit, which is specifically made to work with paper events out-of-the-box. This includes amongst other the `PlayerJumpEvent`, `CreeperIgniteEvent`, `ThrownEggHatchEvent` and `TNTPrimeEvent`. They can be used with the `plugin.registerEvent` method, as any other Lukkit event.

# Lukkit
Lukkit allows developers and server administrators to create plugins for the Spigot API with ease using the Lua scripting language. The language is simple and can be quickly picked up, even by beginners.

NOTE: Lukkit is being rewritten so PR's will not be accepted. If you have an issue you're welcome to accept it if it could also impact v3.

UnwrittenFun was the original author behind Lukkit. However, he abandoned the project and jammehcow took over a couple years later. He was able to update the project to 1.11.2, but lacked the time and motivation to continue maintaining the project himself. Because of this, Lukkit has been in the hands of a number of developers since jammehcow, but has now landed in the hands of AL_1 and Artex Development.

The Lukkit Discord guild can be found [here](https://discord.gg/mhsyabW).

### Documentation
There have been numerous updates and changes made to Lukkit since the original documentation for both Lukkit v1.1.3 and Lukkit v2.0 had been released. In order to keep the documentation updated and in the best interest of users, the documentation has been moved from using the GitHub wiki to using GitBook.

The documentation can be found on [here](https://docs.lukkit.net) and on [GitHub](https://github.com/artex-development/docs.lukkit.net).

### Branch Conventions
Lukkit follows a set of branch conventions that make it easier for developers and contributors to manage the project.
* ``master`` contains the latest released version of Lukkit.
* ``develop`` is the active development branch. Upon a release, this will be merged into ``master``.
* ``patch-x.x.x`` will be created with the appropriate version in the branch name when a patch release is in development. For example, if there is an issue in the v2.0 release and features for v2.1.0 are in the ``develop`` branch, we will pull v2.0 into a new branch, fix the issue, merge into both ``master`` and ``develop`` and then create a release from ``master``. This will avoid incomplete features for the next milestone being incorporated into a patch.
