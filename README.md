gsunit-test
===========
Unit tests and a test driver that can be used to test Google Apps Scripts.
* See class GsUnit for the unit test functions.
* See class RunTests for the test driver
* Also see the section "Run Unit Tests to validate GsUnit" for how these are used.

For a full example of how these objects can be used for Test Driven Development, see repo: gdrive-rename-files

---

Release Checklist
-----------------

- Have ALL unit tests been run?
- Update CHANGES.md and README.md
- Check in all code: cvs ci; git ci
- Fixup the Revision and Date keywords in the spreadsheet scripts
- Publish:
	- git push origin develop
	- git co main
	- git merge develop
	- git push origin main
- Create the new Release, tagging "main" branch
