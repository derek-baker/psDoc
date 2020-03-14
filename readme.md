PSDoc is a Powershell Help Document generator.

----
### Using PSDoc ###

To generate documentation from a module, import the module and use this tool to generate the documentation.

```
Import-Module SomeModule
Set-Location -Path .\src\

# To generate HTML
.\psdoc.ps1 -moduleName SomeModule

# To generate Markdown
.\psdoc.ps1 -moduleName SomeModule -template './out-markdown-template.ps1'

```

### License ###

[Microsoft Public License (Ms-PL)](https://opensource.org/licenses/MS-PL)
