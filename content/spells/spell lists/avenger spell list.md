### first level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #avengerspelllist AND #firstlevel
SORT file.name ASC
```

### second level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #avengerspelllist AND #secondlevel 
SORT file.name ASC
```

### third level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #avengerspelllist AND #thirdlevel 
SORT file.name ASC
```

### fourth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #avengerspelllist AND #fourthlevel 
SORT file.name ASC
```
