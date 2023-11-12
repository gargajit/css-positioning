# css-positioning

==========
**CSS  Positionings**
==========

> - **Static:** (HTML default)

> - **Relative:** (most common one) 
It is relative to it's *own* original position and not with respect to some other element. 

> - **Absolute:** 
> Position relative to *nearest* positioned ancestor or top left corner of the webpage.
> 
> There are 2 parts to this:
> 1.`Position relative to *nearest* positioned ancestor` means that the nearest ancestor should have the position set to relative, i.e. `position: relative` then if the descendant has `position: absolute` then the position will be relative to the ancestor.
> 
> Else, if no ancestor has the position set to relative then,
> 
> 2.`top left corner of the webpage` the descendant with `position: absolute` will be with respect to the webpage.
> 
> - Hence, the tricky thing about `absolute positioning` is that if you want to have it relative to its ancestor, make sure to give `position: relative` to the ancestor.
> 
> - `z-index`: To make the element with `absolute` value lower/below/background to all other information, make sure to add the **`z-index: -1`**. 


> - **Fixed:** Position relative to the top left corner of the browser window
