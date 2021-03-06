# Powershell

- [[ps-cmd]] - PS Commands
- [[ps-errors]] - PS Error Handling


**Environment variables**
* [Documentation](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_environment_variables?view=powershell-7)
* Setting: 
  * for current powershell session: $env:<variablename> = ''
  * available to any process run under this user: [System.Environment]::SetEnvironmentVariable('<variableName>','<variableValue>',[System.EnvironmentVariableTarget]::User)
  * available to any process run on this machine:  [System.Environment]::SetEnvironmentVariable('<variableName>','<variableValue>',[System.EnvironmentVariableTarget]::Machine)
*  They exist in a hierarchy
   * "ENV:" - treat variables as files
   * "$env" - treat variables as variables



[//begin]: # "Autogenerated link references for markdown compatibility"
[ps-cmd]: ps-cmd "Powershell Commands"
[ps-errors]: ps-errors "Powershell Errors"
[//end]: # "Autogenerated link references"