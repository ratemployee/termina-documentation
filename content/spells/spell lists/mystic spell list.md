### cantrips
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #mysticspelllist AND #cantrip
SORT file.name ASC
```

### first level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #mysticspelllist AND #firstlevel
SORT file.name ASC
```

### second level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #mysticspelllist AND #secondlevel 
SORT file.name ASC
```

### third level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #mysticspelllist AND #thirdlevel 
SORT file.name ASC
```

### fourth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #mysticspelllist AND #fourthlevel 
SORT file.name ASC
```


