### cantrips
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #artificerspelllist AND #cantrip
SORT file.name ASC
```

### first level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #artificerspelllist AND #firstlevel
SORT file.name ASC
```

### second level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #artificerspelllist AND #secondlevel 
SORT file.name ASC
```

### third level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #artificerspelllist AND #thirdlevel 
SORT file.name ASC
```

### fourth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #artificerspelllist AND #fourthlevel 
SORT file.name ASC
```

### fifth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #artificerspelllist AND #fifthlevel 
SORT file.name ASC
```

