# StartWizard method




## Name

Sdl.MultiTerm.TMO.Interop.FilterDefinitions.StartWizard —          Starts the Filter Definition wizard.



## Returntype
[Sdl.MultiTerm.TMO.Interop.FilterDefinition](Sdl.MultiTerm.TMO.Interop.FilterDefinition.md)



## Parameters
*none*


## Description



Applying this method opens the Filter Definition wizard, which allows you to create a new filter definition with the wizard GUI.



## Sample


```cs
Termbase oTb = oTbs["Termbase name"];

FilterDefinitions oFilters = oTb.FilterDefinitions;
oFilters.StartWizard();
```


