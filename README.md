# curriculum-datasets
Curriculums in a friendly format.

Most curriculums at the *Universidad Nacional de Colombia* are distributed as
grid based guides, which do not properly represent each of the subjects prerequisites.

In order to have a better visualization, they must be available in a decent format.

### List of available curriculums and their source:
- [Ingeniería de Sistemas y Computación](sistemas-computacion): [Acuerdo 026 de 2014][legal-sistemas-unal]

### Notation
We can think of a curriculum as a directed acyclic graph, with Subjects as
nodes and Prerequisites as links.

#### Subjects:
```
id      : Mnemonic name of the subject
name    : Full name of the subject
code    : Subject code
cred    : Number of academic credits
comp    : Component of the subject (such as: `F`undamentación, `D`isciplinar)
group   : Grouping of the subject (shortened)
term    : Suggested term of the subject
```

#### Prerequisites:
This terminology is adopted from D3.
```
source  : (subject.id) Prerequisite of the target subject 
target  : (subject.id) Subject with required prerequisite
```


## Contributing

The *Universidad Nacional de Colombia* offers 94 undergraduate, 56 doctoral,
152 masters, 83 specializations and 38 medial specialty degrees, so this list isn't
expected to be comprehensive.

Contribution of additional curriculums is more than welcome.


[legal-sistemas-computacion]: http://www.legal.unal.edu.co/rlunal/home/doc.jsp?d_i=73711)
