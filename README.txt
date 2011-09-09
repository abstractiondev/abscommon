Abstraction Common Submodule
----------------------------
- Common includes for T4 handling
- Visual Studio 2010 specific projects for now
- First submodule tests

Usage:
git submodule add git@github.com:abstractiondev/abscommon Demos/ProjectStatusReportingDemo/Abstractions/abscommon

git submodule update --init

Updating submodules:
git submodule foreach git pull

Modifying submodules:


cd abscommon
git checkout master
<Do your editing>
git commit --all -m "Lots of fixes"
cd ..

git add abscommon
git commit -m "Bumped up the revision of abscommon"
REM git push origin master
==> It seems this didn't work; Git Extension's push worked; so the parameters
==> need to be checked.