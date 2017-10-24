# Javascript30Challenge
30 day challenge - every day new application

What I learned from the 30 day challenge.

Day 1 - Javascript Drum Kit:
    1) How to use the <audio> tag in HTML and how to play it with JS
    2) How to catch a 'transitionend' even, which was cool and made me research the transition events as a whole.
  
Day 2 - CSS JS Clock:
    1) Using the CSS transform and transition properties
    2) Using the 'rotate(Xdeg)' function in JS
    
    
Day 3 - Woah! CSS Variables
    1) Here I first got a glance at the CSS Variables technology (--somevariable: value)
    2) It looks seems like a cool thing(WE HAVE VARIABLES IN CSS THAT CAN BE ACCESSED THROUGH JS), but there are some issues
        - Code can get messy fast
        - There is still a compability issue with some older browsers (77% in caniuse.com)
    3) Here are some FAQs and good practices when using CSS Variables:
        - Using :root as a selector is a good practice because we have collect all our variables in one place and thus making our code easier for maintenance
        - Use dashes or underscope for naming convention as CSS Variables are case sensitive and camel case can be hard to spot when debugging css code
        
Day 4 - JavaScript Array Cardio Practice
        1) It was a good practice to remind how the some of the Array Manipulation methods for ES6 are applied. More particularly I liked the exrcise with the sort() function and the last one with the reduce() in which I used the object to store the data.
        
Day 5 - Flexbox image gallery
        1) Very good exercise for showing how the Flexbox CSS functionality works
        2) The JS part was relatively simple - using an event lister for a click event
        
Day 6 - Ajax Type Ahead with fetch()
        1) Using the browser fetch() function go GET Api response - it returns a promise. Then we can manipulate the data with .then() function which works with the data after the api call with fetch() has finished
        2) Using JS regex for matching text with RegExp object and the function match(regex)
        3) Appending html with template literals and innerHTML
        4) Using the input event to trigger when there is an input in a box

