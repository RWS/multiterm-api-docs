#  Sdl.MultiTerm.TMO.Interop.Termbase class

## Name

Sdl.MultiTerm.TMO.Interop.Termbase —          Provides programmatic access to a particular termbase.


## Description

A termbase is a database that is physically stored in a JET, SQL Server or Oracle backend. A termbase contains a number of entries (i.e. concepts), a set of so-called termbase or catalog objects (e.g. filter and layout definitions, etc.) and possibly also multimedia blobs.

The Termbase class allows you to retrieve various information on a specified termbase, e.g. the termbase name, location, the entry count, the number of indexes in the termbase definition, etc.

Apart from that you can also configure a number of settings for a selected termbase, e.g. the source and target index, the active filter, etc.

To select a termbase from a termbase repository you can either use the termbase path (for local termbases), the termbase name (for server termbases) or the index number, e.g.:

```cs
oTb = oTbs["C:\Testdata\Sample Termbase.sdltb"]
```
or
```cs
oTb = oTbs["Sample Termbase"]
```
or
```cs
oTb = oTbs[0]
```


## Properties

* [_Cookie](Sdl.MultiTerm.TMO.Interop.Termbase._Cookie.md): [For internal use only.]
* [_DefaultEntryClassID](Sdl.MultiTerm.TMO.Interop.Termbase._DefaultEntryClassID.md): Returns the default entry class id.
* [_IsLocal](Sdl.MultiTerm.TMO.Interop.Termbase._IsLocal.md): Flags whether a termbase is local or not.
* [AccessPermissions](Sdl.MultiTerm.TMO.Interop.Termbase.AccessPermissions.md): Provides programmatic access to the permissions the currently logged-in user has to a termbase.
* [ActiveFilter](Sdl.MultiTerm.TMO.Interop.Termbase.ActiveFilter.md): Returns the active filter for a termbase.
* [Browse](Sdl.MultiTerm.TMO.Interop.Termbase.Browse.md): Provides access to the browse functionality for a termbase.
* [ChangeDate](Sdl.MultiTerm.TMO.Interop.Termbase.ChangeDate.md): Returns the last termbase change date.
* [CopyrightText](Sdl.MultiTerm.TMO.Interop.Termbase.CopyrightText.md): Returns the copyright text for a particular termbase.
* [DefaultEntryClass](Sdl.MultiTerm.TMO.Interop.Termbase.DefaultEntryClass.md): Returns the default entry class for a particular termbase.
* [Definition](Sdl.MultiTerm.TMO.Interop.Termbase.Definition.md): Provides programmatic access to a termbase definition.
* [DownloadedCopyrightIcoPath](Sdl.MultiTerm.TMO.Interop.Termbase.DownloadedCopyrightIcoPath.md): Returns the path and name of the termbase icon file.
* [DownloadedCopyrightInfoPath](Sdl.MultiTerm.TMO.Interop.Termbase.DownloadedCopyrightInfoPath.md): Returns the path and name of the termbase reference document.
* [DownloadedCopyrightSplashPath](Sdl.MultiTerm.TMO.Interop.Termbase.DownloadedCopyrightSplashPath.md): Returns the path and name of the termbase splash screen image.
* [Entries](Sdl.MultiTerm.TMO.Interop.Termbase.Entries.md): Provides programmatic access to the entries of a termbase.
* [ExpiryDate](Sdl.MultiTerm.TMO.Interop.Termbase.ExpiryDate.md): Returns the expiry date of the termbase.
* [ExportDefinitions](Sdl.MultiTerm.TMO.Interop.Termbase.ExportDefinitions.md): Provides programmatic access to the export definitions of a termbase.
* [FilterDefinitions](Sdl.MultiTerm.TMO.Interop.Termbase.FilterDefinitions.md): Provides programmatic access to the filter definitions of a termbase.
* [ImportDefinitions](Sdl.MultiTerm.TMO.Interop.Termbase.ImportDefinitions.md): Provides programmatic access to the filter definitions of a termbase.
* [IncompleteEntries](Sdl.MultiTerm.TMO.Interop.Termbase.IncompleteEntries.md): Provides programmatic access to the incomplete entries of a termbase.
* [Information](Sdl.MultiTerm.TMO.Interop.Termbase.Information.md): Provides programmatic access to the termbase information.
* [InputModelDefinitions](Sdl.MultiTerm.TMO.Interop.Termbase.InputModelDefinitions.md): Provides programmatic access to the input model definitions of a termbase.
* [IsReadOnly](Sdl.MultiTerm.TMO.Interop.Termbase.IsReadOnly.md): Returns True or False depending on whether a termbase is read-only or not.
* [LayoutDefinitions](Sdl.MultiTerm.TMO.Interop.Termbase.LayoutDefinitions.md): Provides programmatic access to the layout definitions of a termbase.
* [LockedEntries](Sdl.MultiTerm.TMO.Interop.Termbase.LockedEntries.md): Provides programmatic access to the locked entries of a termbase.
* [Name](Sdl.MultiTerm.TMO.Interop.Termbase.Name.md): Returns the name of a termbase.
* [Search](Sdl.MultiTerm.TMO.Interop.Termbase.Search.md): Provides programmatic access to the search functionality for a particular termbase.

## Methods

* [_Reorganise](Sdl.MultiTerm.TMO.Interop.Termbase._Reorganise.md): [For internal use only.]
* [Close](Sdl.MultiTerm.TMO.Interop.Termbase.Close.md): Closes a specified termbase.
* [Delete](Sdl.MultiTerm.TMO.Interop.Termbase.Delete.md): Deletes a particular termbase.
* [ExtractToFile](Sdl.MultiTerm.TMO.Interop.Termbase.ExtractToFile.md): Saves the a termbase to an \*.mdb file.
* [GetHomonyms](Sdl.MultiTerm.TMO.Interop.Termbase.GetHomonyms.md): Retrieves all homonym entries of a particular termbase.
* [Reorganise](Sdl.MultiTerm.TMO.Interop.Termbase.Reorganise.md): Reorganises a specified termbase.


## Sample


```cs
Termbases oTbs = oLocalRep.Termbases;
Termbase oTb = oTbs["Termbase Path"];

Debug.Write("Total number of termbase entries: " + oTb.Information.TotalNumberOfEntries.ToString());
```


