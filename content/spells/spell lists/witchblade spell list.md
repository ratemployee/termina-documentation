### cantrips
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #witchbladespelllist AND #cantrip
SORT file.name ASC
```

### first level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #witchbladespelllist AND #firstlevel
SORT file.name ASC
```

### second level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #witchbladespelllist AND #secondlevel 
SORT file.name ASC
```

### third level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #witchbladespelllist AND #thirdlevel 
SORT file.name ASC
```

### fourth level
```dataview 
TABLE WITHOUT ID link(file.link, title) AS "spell name", concentration, ritual
FROM #witchbladespelllist AND #fourthlevel 
SORT file.name ASC
```


