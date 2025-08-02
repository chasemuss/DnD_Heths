---
title: _Homepage
tags: 
 - 
---

**Original Post**
>Overview You are on a continent about to be over run by the undead. Make your mark on the land of the wasteland. There are three cities alive.
>
> We already have 2 players, You will start out as level 6 or 7. You will get an uncommon item. It will be 60% roleplay & 40% fighting. You will get to lead armies
>
> What to expect from me: I have been a DM for 5 years, I love putting players story into the plot, and I love to homebrew for player if they are interested. Message me if you are interested.


# Characters

```dataview
TABLE tags, status
FROM #Character
FLATTEN tags
SORT tags DESC, title
```

# Organizations

```dataview
LIST
FROM #Organization
SORT file.title
```

# All Notes

```dataview
TABLE tags, title
FROM ""
WHERE file.folder != "_Templates" AND title != "_Homepage"
FLATTEN tags
SORT tags, title
```
