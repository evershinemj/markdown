```flowchart
s=start: start
e=end: end
op=operation: isHotToday() == true?
ex=operation: exception
cond=condition: yes or no?
io=inputoutput: input/output

s-op-cond
cond(yes)-io-e
cond(no)-ex-e
```
