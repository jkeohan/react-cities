# React State

You've been asked to refactor the HTML into a single Component and then add event listeners and state to implement the logic in this [codepen](https://codepen.io/jkeohan/pen/850f8454693590e9772f8d0f6c2f44c8) written in plain vanilla JS

![Products Section](https://i.imgur.com/ojy4N8d.png)

## Instructions

1. Fork this [codesandbox](https://codesandbox.io/s/react-cities-starter-create-datajs-x63y0?file=/src/App.js)
1. Fulfill the listed requirements.
1. Submit the assignment (instructor to provide guidance)

## Requirements

1. Your desgn must include a single **App** component that renders all the HTML and supporting functionality.  
1. Examine the html in <b>public/index.html</b> as it contains 
the all the static HTML and when your ready to begin comment out all the code. 
1. Create a <b>data.js</b> file in **src** folder. In the **data.js** file create a new array called **images** and populate it with the 4 images found in the html. 
2. Import **data.js** into **App.js** and map over the array to render the small images.
3. Render the large image and set it's initial value to the first image in the array.
4. Add a single click event to the small images that will set state to the url of the image that was clicked. 


## Suggestions To Getting Started

- Copy all the HTML from public/html and paste it into App's return() statement. Resolve any possible errors regarding className or otherwise
- Write some pseudocode to work through the logic
- Think about how you can use the array's index position to keep track of which image was clicked

## Bonus 1 - Traffic Light

Convert the following [CodePen](https://codepen.io/jkeohan/pen/MWYEyMV?editors=1010) into a single React Component and implement the logic for click events and adding state.

## Bonus 2 - Memory Game

Convert the following [CodePen](https://codepen.io/jkeohan/pen/opvVGN?editors=0010) into a single React Component and implement the logic for click events and adding state.

## Bonus 3 - Lifting State

This is an advanced bonus and requires that you do additional research on lifting react state. 

Try creating additional components for the images. You will most certainly run into issues with breaking the **onClick** functionaltiy. 

Here are some resources on lifting react state:

- Easy Read: [change-parent-component-state-from-child-using-hooks-in-react](https://webomnizz.com/change-parent-component-state-from-child-using-hooks-in-react/)
- Difficult Read: [react-lift-state](https://www.robinwieruch.de/react-lift-state)


## Plagiarism

Take a moment to refamiliarize yourself with the
[Plagiarism policy](https://git.generalassemb.ly/DC-WDI/Administrative/blob/master/plagiarism.md).
Plagiarized work will not be accepted.

## License

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.



