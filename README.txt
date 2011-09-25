Abstraction Common Submodule
----------------------------
- Common includes for T4 handling
- Visual Studio 2010 specific projects for now
- First submodule tests

Usage (for read-only cloning):
git submodule add git://github.com/abstractiondev/abscommon Demos/ProjectStatusReportingDemo/Abstractions/abscommon


Usage (for updating repositories):
git submodule add git@github.com:abstractiondev/abscommon Demos/ProjectStatusReportingDemo/Abstractions/abscommon

Updating submodules:
git submodule foreach git pull