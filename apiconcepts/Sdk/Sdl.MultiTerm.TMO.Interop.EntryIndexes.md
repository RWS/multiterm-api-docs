# Sdl.MultiTerm.TMO.Interop.EntryIndexes class

## Name

Sdl.MultiTerm.TMO.Interop.EntryIndexes —          Provides programmatic access to the indexes contained in a particular entry.



## Description



Via this class you can retrieve the indexes (i.e. languages) and terms contained in a selected entry.



## Properties
* [Count](Sdl.MultiTerm.TMO.Interop.EntryIndexes.Count.md): Returns the number of indexes contained in a particular entry.
* [Item](Sdl.MultiTerm.TMO.Interop.EntryIndexes.Item.md): Refers to a particular entry index.




## Methods

* [Add](Sdl.MultiTerm.TMO.Interop.EntryIndexes.Add.md): Adds an index to the collection.




## Sample


```cs
Termbase oTb = oTbs["Termbase name"];
Entries oEntries = oTb.Entries;
Entry oEntry = oEntries.Item(1);
EntryIndexes oIndexes = oEntry.Content.EntryIndexes;
for(int i=0;i<oIndexes.Count;i++)
{
   	Debug.WriteLine(oIndexes[i].IndexName + ": " + oIndexes[i].Term);
}
```

