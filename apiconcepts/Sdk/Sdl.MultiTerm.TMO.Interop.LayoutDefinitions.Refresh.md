

# 
    Refresh method



## Name

Sdl.MultiTerm.TMO.Interop.LayoutDefinitions.Refresh —          Updates the layout definition collection.



## Returntype

void



## Parameters
*none*


## Description



By applying this method you can make sure that MultiTerm client users always have access to the up-to-date layout definition collection, which includes all definitions that have been added while the users were online.



## Sample


```cs
Termbase oTb = oTbs["Termbase name"];

LayoutDefinitions oLayouts = oTb.LayoutDefinitions;
oLayouts.Refresh();
```



## Provide Feedback

[Make annotation](mailto:sdk-feedback@sdl.com&amp;subject=Reference%20for%20Sdl.MultiTerm.TMO.Interop.LayoutDefinitions.Refresh)

