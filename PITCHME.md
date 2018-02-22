@title[Python som miniräknare]
## Turtle
#### Måns Magnusson UVS progläger 2018

---

#### En introduktion till SARA

- Sekvens
- Alternativ
- Repetition
- Abstraktion

---

### Kan X (Måns väljer) exekvera följande program?
```python
gå ett steg frammåt
svägn vänster
gå ett steg frammåt
svägn vänster
gå ett steg frammåt
svägn vänster
gå ett steg frammåt
svägn vänster
hoppa
```

---

### Vad är skillnaden med detta program:
```python
upprepa(4):
  gå ett steg framåt
  sväng vänster
hoppa
```

---


### Fixat?
```python
upprepa(4):
  om ingen vägg framför:
    gå ett steg framåt
  sväng vänster
hoppa
```

---

### I python:
```
upprepa(n):
    do something
```

```python
i = 0
while i < n:
    do something
```

---

