# JavaScript30
Course created by  [Wes Bos](https://github.com/wesbos). Here's the challenge ð [JavaScript30](https://courses.wesbos.com/account), you can join it for free!
<image src="https://camo.githubusercontent.com/07ca65497065dd926bd889c53b7b7652f8ef3cbc4320739cf7ebed3c4d34cb2d/68747470733a2f2f6a61766173637269707433302e636f6d2f696d616765732f4a53332d736f6369616c2d73686172652e706e67">
  
  Hi there ð

I created this repository in order to keep track of my progress in the JavaScript 30 Day Challenge and to commit and log what I learnt every day.
  
  # What is JavaScript 30 Day Challenge ? <br>
  It's a 30-day vanilla JavaScript coding challenge. You will build 30 unique projects in 30 days using fun and easy video tutorials.
  You should already know some JavaScript to take on this challenge.
  
 
   # JavaScript 30-Day 1 
  ## Javascript Drum Kit ð¥
  ### âïž My learnings from this project:
   - key event 
   - transitionend event 
   - ES6 template strings
   
   Methods Learnt:<br>
  ```
  1. addEventListener()
  2. querySelectorAll()
  3. remove()
  4. play()
  ```
  
   âŠ ```classList``` proprty -> The classList property returns the CSS classnames of an element. It returns a DOMTokenList.<br>
   **Found a very useful tool for JavaScript events Keycodes at [keycodes.info](https://keycode.info/)**.<br>
  
   # JavaScript 30-Day 2 
   ## CSS + JS clock ð 
  ### âïž My learnings from this mini-project:
   - Learnt about CSS transitions and transform
   - The ES6 **'const'** keyword
   - Live UI update after few seconds
   - **Element.style** for inline styling

   # JavaScript 30-Day 3 
   ## Update CSS Variables with JSâïž
   âŠ The goal today was to create an Image editor to control the spacing, color, and blur by modifying CSS variables with JavaScript.
  
   CSS variables explained:
   - spacing
   - base 
   - blur
   ### âïž My learnings from this project:
   - How to declare variables in css
   ```
      :root{
      --base: yellow;<br>
      }
      img{
      background-color: var(--base);
  }
   ```
   - Code snippet to select all inputs on the page -> ```const inputs = document.querySelectorAll('.controls input');```
   - **querySelector** gives you a **NodeList**
   - Learnt about **'change'** and **'mousemove'** events
   ```
    Example code:
 
    inputs.forEach(input => input.addEventListener('change', handleUpdate));
    inputs.forEach(input => input.addEventListener('mousemove', handleUpdate));
  ```
   - Learnt about **'dataset'** that can be used to access all data attributes.
    
    
    
   # JavaScript 30-Day 4 
   ## Array Cardio Day 1 ðª
    
    âŠ This lesson is all about Fundamentals of JavaScript(Array methods).
   ### âïž My learnings from this project:
   - Worked with ES6 Arrow functions.
   - Learnt about JavaScript array methods:
     - filter() *is like you give 10 things and it return 2.*
     - map() *returns exact same amount of elements as you give it.*
     - sort() *used for sorting elements in some order.*
     - reduce() *allow you to sort of build something on every single one.*
    
    
   # JavaScript 30-Day 5 
   ## Flex Panels Gallery ðª
    âŠ The image will expand when you click on it and then shrink when you click it off.
    âŠ Today's lesson was about making a photo gallery
   ### âïžMy learnings from this project:
   - Primarily focused on CSS flex property.
   - Transitioned on **flex-grow** and **font-size** to expand images. 
   - Used Funtions:
     - toggleOpen
     - toggleActive
 
âŠ ***Best resourse to learn CSS Flexbox:[Flexbox](https://flexbox.io/)***
  
    
   # JavaScript 30-Day 6 
   ## Type Ahead ð
   ### âïžMy learnings from this project:
   - Fetch API 
   - Getting .json() from fetch response
   - Array spread operator
   - Match() function
                    
   # JavaScript 30-Day 7
   ## Array Cardio ðªðª
   ### âïžMy learnings from this project:
   - Learnt some more Array methods 
     - some()
     - every()
     - find()
     - slice()
     - findIndex()
    
   # JavaScript 30-Day 8
   ## Fun with HTML5 Canvasðš
   ### âïžMy learnings from this project:
   - Learnt the fundamentals of HTML5 canvas.
   - Build a painting canvas where if you hold down the mouse button and drag, you can paint on it. Something like Microsoft Paintð
  
  âŠ You can find a similar project in Book Eloquent JavaScript [Drawing on Canvas](https://eloquentjavascript.net/17_canvas.html).
  
   # JavaScript 30-Day 9
   ## 14 Must Know Dev Tools Tricksð¡
   ### âïžMy learnings from this project:
   - Learnt how to use developer tools in your browser effectively. 
   - Wes shared some amazing tips and tricks for using the developer tools in your browser.

  All methods explained todayð
  <table style=" background-repeat:no-repeat; width:100%;margin:0;" cellpadding="0" cellspacing="0" border="0">
   <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
        Regular
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log('text')        
     </td>
   </tr>
    <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
        Interpolated
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log('text with a %s', 'placeholder')        
     </td>
   </tr>
   <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
        Styled
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log( '%c text styling', background:red)       
     </td>
   </tr>   
    <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         warning!
     </td>
     <td style="height:40px; width:10px; margin:0;">console.warn('warning message')       
     </td>
   </tr>
        <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Error
     </td>
     <td style="height:40px; width:10px; margin:0;">console.error('error message')
     </td>
   </tr>
      <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Info
     </td>
     <td style="height:40px; width:10px; margin:0;">console.info('message info')
     </td>
   </tr>
          <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Testing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.assert(false, 'the word is %s', 'foo')
     </td>
   </tr>
              <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         clearing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.clear()
     </td>
   </tr>
                  <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         clearing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log(p)<br>     console.dir(p)
     </td>
   </tr>
                      <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Grouping together
     </td>
     <td style="height:40px; width:10px; margin:0;">console.group()<br>console.groupCollapsed()<br> console.groupEnd()
     </td>
   </tr>
                          <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         counting
     </td>
     <td style="height:40px; width:10px; margin:0;">console.count('Count')
     </td>
   </tr>
                              <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         timing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.time('fetching data')
     </td>
   </tr>
    
</table>
  
  
 # JavaScript 30-Day 10
 ## Hold Shift to Check Multiple Checkboxes 
 ###  âïžMy learnings from this project: 
  Code Example:
   ```const checkboxes = document.querySelectorAll('.inbox input[type="checkbox"]');```
 - Check if they had the shift key down
 - AND check that they are checking it
  ``` let inBetween = false;
      inBetween = !inBetween;
      checkboxes.forEach(checkbox => checkbox.addEventListener('click', handleCheck));
  ```
  
***âŠ How it works:***
 - When you click a checkbox, hold Shift, and click another checkbox a few rows down or up, all the checkboxes in between those two are checked.
   BOOM!! Wes style :D    
    
  # JavaScript 30-Day 11
  ## Custom Video Player 
  ### âïžMy learnings from this project: 
  - learnt some useful tips on customizing HTML5 video player controls. 
    - Used ```togglePlay``` to play and pause the video.
    - Added ```click``` event.
    - Used event listners ```mousemove```,```mouseup```.
 
    
  # JavaScript 30-Day 12
  ##  Key Sequence Detection
  ### âïžMy learnings from this project:
  - It works in a way when when someone types in a series of keys, something occurs.
  - Learnt about Key Sequence Detection and Konami Code.
      
  # JavaScript 30-Day 13 
  ## Slide in on Scroll
  âŠ Today we used Javascript to add the Slide-In-On-Scroll functionality to a pre-built page.<br>
  âŠ As you scroll down, images slide in from the right or left sides of the page.
  ### âïž My learnings from this project:
  - Learnt about JavaScript ```debounce``` fuction
    - The overhead of a function can be reduced by preventing it from being called repeatedly. This will help to speed up the website.
  
  Sample Code:
  ```
      function debounce(func, wait = 20, immediate = true) {
      var timeout;
      return function() {
        var context = this, args = arguments;
        var later = function() {
          timeout = null;
          if (!immediate) func.apply(context, args);
        };
        var callNow = immediate && !timeout;
        clearTimeout(timeout);
        timeout = setTimeout(later, wait);
        if (callNow) func.apply(context, args);
      };
    };
  ```  
  
  # JavaScript 30-Day 14 
  ## JavaScript References VS Copying
  ### âïžMy learnings from this project: 
  - Learnt the differences between array & object references and actual copies. 
  - A primitive type can be manipulated by its value, whereas a reference type can be modified by its reference.
  
  # JavaScript 30-Day 15 
  ## LocalStorage
  - Today's Challenge is about 2 main things:
    1. Local Storage
    2. Event Deligation

   ### âïžMy learnings from this project: 
   - ```e.preventDefault()``` -> stops the page from reloading.
   - ```JSON.stringify(items)``` -> When you pass items it's going to convert your objects and arrays into a JSON string.
   - ```JSON.parse()``` -> take items from the string and put it back into form whatever it was initially.
   - ```If you addEventListner()``` on something that doesn't exist, you'll know that in future it won't be clicked.
  
  # JavaScript 30-Day 16 
  ## Mouse Move Shadow
  ### âïžMy learnings from this project: 
  - Day-16 is about adding shadow with ```mousemove```.
  - Mainly learnt about ES6 Object destructuring and updating CSS rules, like text-shadow, using javascript.
    

  # JavaScript 30-Day 17 
  ## Sort Without Articles
  ###  âïžMy learnings from this project:
  - Learnt about ```array.sort()``` method to sort a list of band names without *'Articles'*.
  
    
  # JavaScript 30-Day 18 
  ## Adding Up Times with Reduce
  ### âïžMy learnings from this project:
  - See the usability test case scenario for ```Array.prototype.reduce()```. 
  - When used correctly, ```reduce()``` can be quite effective.
    
    
  # JavaScript 30-Day 19
  ## Webcam Fun
  ### âïžMy learnings from this project:
  - Learnt how to make a photo booth using JavaScript.
  - Real-time image pipelining and canvas were new concepts to me.
    
    
  # JavaScript 30-Day 20 
  ## Speech Detection
  ### âïžMy learnings from this project:
  - Learnt about SpeechRecognition something like google voice search. Definitely a good challenge!
    
    
  # JavaScript 30-Day 21 
  ## Geolocation
  ### âïžMy learnings from this project:
  - Learnt abbout Geolocation and Orientation Api.
  - Learnt that mobile devices generally use GPS hardware to locate themselves.
    
    
  # JavaScript 30-Day 22 
  ## Follow Along Link Highlighter
  ### âïžMy learnings from this project:
  - Learnt about ```Element.getBoundingClientRect()``` method and how it works.
  
  âŠ The function returns a [DOMRect](https://developer.mozilla.org/en-US/docs/Web/API/DOMRect) containing information about the size and position of an element in relation to the [viewport](https://developer.mozilla.org/en-US/docs/Glossary/Viewport).
    
  # JavaScript 30-Day 23 
  ## Speech Synthesis
  ### âïžMy learnings from this project: 
  - Learnt about speech Speech Synthesis CSS radial-gradient.
  - Method Used:
    - addEventListener()
    - toggle()
    - querySelectorAll()
    - querySelector()
    - includes()
    
    
  # JavaScript 30-Day 24
  ## Sticky nav
  ### âïžMy learnings from this project:
  - Learnt how to fix a nav using JavaScript when you scroll to it.
  - You use ```nav.OffsetHeight``` -> to grab the height of the pixels.
    
    
  # JavaScript 30-Day 25 
  ## Event Capture, Propagation, Bubbling, and Once
  ### âïžMy learnings from this project:
  - Learnt about ```propagation```, ```bubbling```, ```event capturing```, and new property ```once```.
    - Bubbling refers to the browser being able to determine what you clicked on, as well as trigger clicks to ripple up every time you click. For example:
Whenever you click on a nested element, it actually starts from the top and then captures all of those events. It then starts at the bottom and starts doing something called a bubble.
    - The capture happens from top to bottom and then the events, the events haven't started yet. It only captures where you clicked, and is storing them. As you go up, it will begin to bubble up, which means it will start triggering events as you go up.
  
  - ```e.stopPropagation();```-> *stop bubbling this event up*
  
- If you set once to true it will listen for a click and unbind itself and unbinding itself is the same thing as ```div.removeEvent.Listener('click', logText)```
- You can use it for buttons when someone clicks that button more than once. (Example: Store checkouts)
``` 
  button.addEventListner('click', () =>{
   console.log('click!!!');
 },{
  once: true
});
  ```  
    
  # JavaScript 30-Day 26 
  ## Stripe Follow Along Dropdown
  ### âïžMy learnings from this project
  - Learnt how to make a "Follow Along" Navigation. 
  - Learnt about ```getBoundingClientRect()```.
  
  *âŠ [SEJ- Search Engine Journal](https://www.searchenginejournal.com/): Best website I have found for finding SEO information which has Stripe Follow Along Dropdown navigation. Check it out for inspiration.*
  
    
    
  # JavaScript 30-Day 27
  ## Click and Drag to Scroll
  ### âïžMy learnings from this project:
  - Learnt logic behind *Click and Drag to Scroll* using that plays main role ```element.offsetLeft```.
  - It's just a combination of mouse down, mouse leave, mouse out, mouse up, and mouse move.
  ```
  CSS code:
     .item.active{
      background: rgba();
      cursor: grabbing;
      cursor: -webkit-grabbing;
      transform: scale(1);
}
```
    
  # JavaScript 30-Day 28 
  ## Video Speed Controller UI
  ### âïžMy learnings from this project:
  - Learnt how to use offset techniques for design presentations. By making use of the offset property, you can align elements exactly where you want them.
  
  ```
  Code Sample:
  <script>
  const speed = document.querySelector('.speed');
  const bar = speed.querySelector('.speed-bar');
  const video = document.querySelector('.flex');

  function handleMove(e) {
      const y = e.pageY - this.offsetTop;
      const percent = y / this.offsetHeight;
      const min = 0.4;
      const max = 4;
      const height = Math.round(percent * 100) + '%';
      const playbackRate = percent * (max - min) + min;
      bar.style.height = height;
      bar.textContent = playbackRate.toFixed(2) + 'Ã';
      video.playbackRate = playbackRate;
    }
  speed.addEventListener('mousemove', handleMove);
</script>
  ```
    
    
  # JavaScript 30-Day 29
  ## Countdown Clock
  ### âïžMy learnings from this project:
  - Learnt about ```Date.now()```, ```clearInterval()``` functions. 
    
  # JavaScript 30-Day 30 
  ## Whack A Mole Game
  ### âïžMy learnings from this project:
  - Completed today's challenge used ```document. query selector```, ```classList.add('up')``` and ```classList.remove('up')```.
  
  âŠ It is recommended for those who wish to gain a deeper understanding of JavaScript.
  
  ### Give A Star â­
 ***Thank you for sticking with me all the way to the end! Please consider staring this repo on top right of the page if you enjoy it and find it useful!***



  
