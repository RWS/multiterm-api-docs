# Item property

## Name

Sdl.MultiTerm.TMO.Interop.InputModelDefinitions.Item —          Provides access to a particular input model definition.

## Type
[Sdl.MultiTerm.TMO.Interop.InputModelDefinition](Sdl.MultiTerm.TMO.Interop.InputModelDefinition.md)
(read)

## Index Parameters

* Index (Variant)

## Description

To select a specific input model definition you can either use the corresponding index number, e.g. Item(0), or the definition name, e.g. Item("Default input model").



## Sample


```cs
Termbase oTb = oTbs["Termbase name"];

InputModelDefinitions oModels = oTb.InputModelDefinitions;
InputModelDefinition oModels = oModels[0];
```

