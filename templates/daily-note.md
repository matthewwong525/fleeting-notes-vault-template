## Fleeting Notes
```dataview
LIST
FROM "fleeting-notes"
WHERE created_date = date({{title}}) 
```

## Tasks from Fleeting Notes
```dataview
TASK
FROM "fleeting-notes"
WHERE !completed
```

## My Notes
