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
6. api fetch cities regex
  - fetch is built into html now
  - fetch returns a promise
  - .then(data =>  cities.push(...data)) ADDING spread pushes each data item individually instead of one giant block
  - good for filter, map array
7. more array methods
  - .some checks if there's 1 occurance of something and returns true/false
  - .every checks if every item and return true/false
  - .find is like .filter, but instead of returning a subset of the array it returns the first item it finds that matches
  - inplicit returns!
  - .findIndex finds where something is in an array
8. canvas stuff
9. inline commands
  - console.war, error, info
  - console.assert only runs if something is false
  - console.group groups console logs
10. multiple checkboxes
15. local storange event delegation
  - by default, forms refresh the page once they are submitted
    - stop this by e.preventDefault();
  - forms also have a reset method that clears the fields
    - this.reset();
