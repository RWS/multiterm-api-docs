

# 
    Sdl.MultiTerm.TMO.Interop.LayoutDefinition class



## Name

Sdl.MultiTerm.TMO.Interop.LayoutDefinition —          Provides programmatic access to a particular layout definition.



## Description



Layouts basically contain an XSL stylesheet, which renders MultiTerm entry XML as HTML. Via this class you can retrieve information on a particular layout, e.g. the layout description, the content (i.e. the layout 'source code'), etc. In addition you can also use this class to edit an existing layout using the layout wizard.



## Properties

* [Content](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Content.html): Returns the layout definition content.
* [Description](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Description.html): Returns the layout description.
* [ID](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.ID.html): Returns the unique id of the layout.
* [Name](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Name.html): Returns the name of the layout.
* [Owner](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Owner.html): Returns the owner name for a particular layout definition.
* [ReadOnly](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.ReadOnly.html): Returns whether a particular layout is read-only.




## Methods

* [Delete](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Delete.html): Removes the layout from the collection.
* [Load](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Load.html): Updates the selected layout from an external layout definition file.
* [Save](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.Save.html): Saves the layout definition to an external file.
* [StartWizard](Sdl.MultiTerm.TMO.Interop.LayoutDefinition.StartWizard.html): Calls up the layout definition wizard for editing a particular layout.




## Sample


```cs
//select termbase
Termbase oTb = oTbs["Termbase name"];

//select layout
LayoutDefinitions oLayouts = oTb.LayoutDefinitions;
LayoutDefinition oLayout = oLayouts["Flags layout"];

Debug.WriteLine(oLayout.Description);
```



## Provide Feedback

[Make annotation](mailto:sdk-feedback@sdl.com&amp;subject=Reference%20for%20Sdl.MultiTerm.TMO.Interop.LayoutDefinition)

