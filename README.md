# VSIX Test

This project is a test to support diffrent Visual Studio versions with one extension via a Shared Project.

## Notes:

- Use the latest BuildTools in the Projects.
- The buildstep of the `.vsct` file must be **VSCTCompile**
- The `.vsct` has to have `<ResourceName>Menus.ctmenu</ResourceName>` inside it's XML-tag in the project file.
