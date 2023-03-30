# Octatrack File Format


## Top Level/

- Set directories
- LOG 200409.txt


## TL/SET/

- AUDIO/
- Project1/
- Project2/


## TL/SET/AUDIO/

- Subdirectories
- *.wav
- *.ot


### TL/SET/AUDIO/*.ot

Binary

```
FORM    
DPS1SMPA...
```

## TL/SET/PROJECT/

- project.strd/.work
- markers.stdr/.work
- arr01.strd - arr08.strd/.work
- bank01.strd - bank16.strd/.work


## TL/SET/PROJECT/project.strd/.work

Text!


## TL/SET/PROJECT/bank01/.work

Binary file
Includes some text


Added newlines to make it easier to mark sections, and elipses to mark binary data.
```
FORM    
DPS1BANK     

PTRN    
TRAC     ...
TRAC    ...
TRAC    ...
TRAC    ...
TRAC    ...
TRAC    ...
TRAC    ...
TRAC    ...
MTRA     ...
MTRA    ...
MTRA    ...
MTRA    ...
MTRA    ...
MTRA    ...
MTRA    ...
MTRA    ...
@   

PTRN    
TRAC     ...

...lots and lots of stuff...

ONE    
TWO    
THREE  
FOUR   
H
```


## TL/SET/PROJECT/arr01.strd/.work



## TL/SET/PROJECT/markers.stdr/.work
