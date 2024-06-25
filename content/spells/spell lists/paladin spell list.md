### first level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #paladinspelllist AND #firstlevel
SORT file.name ASC
```

### second level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #paladinspelllist AND #secondlevel 
SORT file.name ASC
```

### third level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #paladinspelllist AND #thirdlevel 
SORT file.name ASC
```

### fourth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #paladinspelllist AND #fourthlevel 
SORT file.name ASC
```

### fifth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #paladinspelllist AND #fifthlevel 
SORT file.name ASC
```

