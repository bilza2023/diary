Today i understood 
  - what is component based system. i understood after created a data-structure that had
    enough flexability to be usable in the future without change. once this mutual data-structure
    (called slide_data )was decided upon suddenly there was an explosion of possibilities. now i can just write 2 type of
    components 1: the Draw components will draw the slide_data where as 2: Edit Components will edit the slide_data
    and then same edited data will be consumed by Draw componensts.
    - So now that we have slide_data we can fit in any sort of data structure inside slide_data and run it using
    draw components.
    - I can contain Canvas based slides as well . nothing stopping  us all we have to do is place a canvas
      inside a component and draw on it.  
Future Idea:
I can have an engine that run slides randomly based on user interaction. so we can create a self contained
internactive lesson / internactive presentation which user can click around. keep in mind these components
may or may be just draw types.

The main feature of my current project "Presentation Module" in svelte , javascript is time based swapping 
of slides, this each slide run sequentially just like a movie with no user interaction. it just PRESENTSSSS
--do not go wrong with the main idea since if you add interactivity then that needs different type of
structure .. the current structure (by structure i mean the count wrapper that generate incrementially
increasing pulse singl from 0 to onwards) is not suitable for interactivity.
- THERE SHOULD BE NOT CHANGE IN THE INCOMMING DATA INTERFACE OF DRAW (AND HENCE ALSO EDIT) COMPONENTS
- (it means slide_data structure must not change ). HOWEVER YOU CAN GO NUTS WITH THE SLIDE ITEMS ARRAY AND
- SLIDEXTRA , ALSO YOU HAVE ITEMEXTRA IN EACH ITEM OBJECT AS WELL. YOU SHOULD PACK YOUR DATA IN THIS
  STRUCTURE...PERIOD
  
  
