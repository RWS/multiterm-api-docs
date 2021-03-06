# Sdl.MultiTerm.TMO.Interop.LockedEntries class

## Name

Sdl.MultiTerm.TMO.Interop.LockedEntries —          Provides programmatic access to all locked termbase entries.

## Description

Entry locking allows MultiTerm to ensure that only one user can edit an entry at any given point in time. While an entry is being edited it is locked and therefore read-only for all other users, regardless of their access privileges.

As an administrative user you might want to know whether there are any locked entries in the first place, how long an entry has been locked and by whom. This class provides programmatic access to such information.

## Properties

* [Count](Sdl.MultiTerm.TMO.Interop.LockedEntries.Count.md): Returns the number of locked entries.
* [Item](Sdl.MultiTerm.TMO.Interop.LockedEntries.Item.md): Provides access to a particular locked entry.


## Methods
*None*

## Sample


```cs
Termbase oTb = oTbs["Termbase name"];

LockedEntries oLocks = oTb.LockedEntries;
Debug.Write("Number of locked entries: " + oLocks.Count.ToString());
```


