3. css variables
  - when you want to make up an attribute for something, you can affix 'data-' to the front of it. for example, data-sizing, data-length. this.dataset shows an object of all these things!
  - css variables can be manipulated with javascript without needing to rerender the page

4. JS array functions
  - filter: returns items from an array based on parameters
    - const fifteen = inventors.filter(inventor => inventor.year >= 1500 && inventor.year <= 1599)
  - map takes an array, does something, returns a new array with the same length
  - sort takes an array and returns a new array with a different order
    - it returns 1 or -1, which changes the positon of the 2 items being compared
  - reduce is a way to solve problems such as adding up all the values from each element of an array
5. flexbox stuff
  - display:flex; this makes the children take up as much space as they need from left to right i think
  - flex: 1; this makes the children take up an equal amount of space
  -flex: 5: this means take 5x the amount of space you need