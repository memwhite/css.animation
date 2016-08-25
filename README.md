# css.animation

This is based on a Net Ninja Tutorial on CSS Positioning


CSS Positioning Notes:

Stacking order:
//the further down the html page you are, the higher stacked something is
//ex: the element at the very bottom of the html page will stack on the very top of
//everything else

Z-index:
//this can override the normal stacking order
//default is z-index:0;
//z-index: 2; will stack on top of z-index: 1 or 0
//don't get too crazy with this, use the normal stacking order as much as possible
//must have a position assigned to assign a z-index


Position: fixed
//this will pin something to a spot and it will stay there as you scroll
//ex: nav bar at the top of the page
//fixed position takes the element out of normal document flow


Position: absolute vs. relative
//absolute takes it out of regular document flow

//relative does not take it out of regular document flow
  //relative is still within the space/div/container, but this allows it to be offset a bit
  //from top, bottom, right, left

//if a parent element position is set to relative, and the child element is set to
  //absolute, the child element's new (0,0) coordinate is the upper left hand corner
  //of the parent element instead of the whole page

/******************************************/

Box-Model:
//<h> & <p> tags by default take up 100% of the width of the page

//a href isn't block by default, you have to put
display: block; in the CSS
to get them to format the same as a p tag when you're adding things
like border, width, margin, and padding

//In-line styles left to right
//Block styles on top of each other

<div class="wrapper" - look up


/***********************************/

Float:
//takes elements out of the normal document flow

