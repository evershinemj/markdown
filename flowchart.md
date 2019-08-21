```flowchart
s=>start: start
e=>end: end
op=>operation: isHotToday() == true?
sub=>subroutine: subroutine
cond=>condition: yes or no?
io=>inputoutput: input/output
st->op->cond
cond(yes)->io->e
cond(no)->sub(right)->op
```
