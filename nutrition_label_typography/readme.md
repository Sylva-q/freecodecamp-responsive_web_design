learning summary

1. new semantic tag learned (span): to group or style small portions of text or elements. Combined with CSS to apply styles or behaviors. example: 
'<p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>'
/In this p element, 'total fat 8g' was grouped de separated from '10%', so that '10%' can be styled to bold. And in inside 'total fat 8g', 'total fat' was nested as another group again aso that it can be bold./
2. Combination use of flexbox and span for layout, example:
p {
  margin: 0;
/* The flex property enables flexible layouts by distributing space among items in a container, allowing alignment and spacing adjustments. */
  justify-content: space-between;
/* spreads children horizontally, pushes the first child (<span><span class="bold">Total Fat</span> 8g</span>) to the far left and the last child (<span class="bold">10%</span>) to the far right.
Result:*/
}
3. how to combine different classes in one element
4. box-sizing: border-box; ensures that the padding and border are included within the element’s total width and height.
This makes sizing more predictable and prevents elements from overflowing their containers when you add padding or borders.