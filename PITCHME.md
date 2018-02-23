@title[Turtle]
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
```
gå ett steg frammåt
sväng vänster
gå ett steg frammåt
sväng vänster
gå ett steg frammåt
sväng vänster
gå ett steg frammåt
sväng vänster
hoppa
```
---

### Vad är skillnaden med detta program:

```
upprepa(4):
    gå ett steg framåt
    sväng vänster
hoppa
```

--- 
### Fixat?

```{tidy=FALSE}
upprepa(4):
    om ingen vägg framför
        gå ett steg framåt    
    sväng vänster
hoppa
```

--- 

### upprepa i python:

```
upprepa(n):
    gör något
```


```python
i = 0
while i < n:
    gör något
    i += 1
```

---
### alternativ i python:

```
om a större än b:
    gör något
annars:
    gör något annat
```

```python
if a > b:
    gör något
else:
    gör något annat
```
---
### Kan vi ha något annat än större än?
Ja!
- I python kan vi ha vilket boolskt uttryck som helst efter while och if.
```python
if a%2 == 0 and not x%5 == 1:
```
```python
if (a%2 == 0) and (not (x%5 == 1)):
```
- om en ifsats exekverades var dess villkor `True`
- annars `False`

---
### Turtle graphics!


- Online-miljö för turtle graphics: [repl.it/@exoji2e/TurtleGraphics](https://repl.it/@exoji2e/TurtleGraphics)
- Uppgifter: [www.lth.se/programmera/](http://www.lth.se/programmera/)
    + klicka på lös våra uppgifter steg för steg

---

### Funktioner
```python
def funktionsnamn(parameter1, parameter2):
    gör saker med parametrarna
    return funktionsvärdet
```

---
### Funktioner exempel:
```python
def add(a, b):
    return a + b
```
```python
def kvadrat(sidlängd):
    i = 0
    while i<4:
        t.forward(sidlängd)
        t.left
```
```python
def stortprimtal():
    return 10**9 + 7
```

---

### SARA-uppgifter

Skriv ett program som:
- skriver ut de tio första positiva talen
- skriver ut de tio första positiva udda talen
- berärknar det n:te fibonacci-talet
