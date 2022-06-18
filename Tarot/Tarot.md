# Tarot

```dataview
table without id file.link as "Major Card"
from ""
where fileType="Tarot" and tarotType="Major"
```


```dataview
table without id file.link as "Minor Card", synopsis as "Signifies"
from ""
where fileType="Tarot" and tarotType="Minor" 
sort  suite
```