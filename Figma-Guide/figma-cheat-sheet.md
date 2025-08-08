## Figma Cheat Sheet Overview

Day-to-day shortcuts and tricks for rapid design and prototyping in Figma.


### Shortcut Finder and grid show/hide:
cmd/ctrl + / (slash) to search shortcuts

grid show/hide: ctrl + g

### Vector:

Vector Primitives
> ctrl + e

place Image:
> shift + ctrl + k

copy/paste property:
> ctrl + alt + c | ctrl + alt + v

Resizing:
> ctrl + alt + shift and drag for center focused resize and shift drag for corner focused

Swap fill and stroke:
> shift + x

Paint Bucket Fill / Remove seagment
> b

Non destructive node removal:
> shift + delete

Pen Curve Toggle
> Shift + click | alt + drag

Node Join:
> ctrl + j | ctrl + shift + j

### Auto Layout:
Help retain consistent and responsive structure respecting container or bounding box

Make Auto Layout:
> shift + a

Snap draging
> spacebar + drag

O height hack
> 0.001 px

### Design System Component:
> Can create multiple component at a time.

> Remove and pull deleted component:
```txt
right click on a instance of the component, go to main component, then restore the main component
```

### Responsive Component:
```xlm
<container Horizontal="Fill Container || Fixed Width" Vertical= "Hug Content" >
    <atom tab="resizing" 
    Horizontal="Fill Container || Fixed Width" 
    Vertical= "Hug Content" 
    />
</container>
```
> For vertical responsiveness, reverse the horizintal and vertical values