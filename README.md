sibling-spacing
===============

Sibling Spacing addon for Anki 2

When you answer a card, it may give the card a boost or a penalty, 
to prevent siblings showing up with too little (or too much) spacing.

- if a sibling is due within +-15% of the designated due date, 
  give the card an extra 50% boost to space them apart 

- if the designated due date results in an interval larger 
  than four times of one of its siblings, 
  give the card a 50% penalty to space them closer together

This addon is geared towards a standard use case (front+back, 
i.e. two cards per note) and may not work at all well with 
more siblings.

The boost / penalty values are hard coded at the moment.

This addon may be incompatible with the load balancer addon.
