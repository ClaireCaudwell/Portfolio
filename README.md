# Portfolio project 🌼
This week's project was about us building our portfolio page, where we can showcase ourselves as frontend developers, our skills and projects we’ve created so far on the bootcamp. As I have signed up for the career coaching program I had to follow the design template that was outlined. 

## The requirements:
The blue requirements expected us to 
* Build our page using HTML and CSS.
* Use flexbox for the layout.
* Fully responsive, mobile, tablet and desktop.
* Should look and function the same on Chrome, Firefox and Edge.
* Should work well for people that use screen readers and keyboard navigation.
* The HTML code should validate in the validation tool. 

## Steps taken:
1. Started by reading up on HTML semantics and accessibility. This was so I could from the outset use elements that would be best suited to the task of making the page as accessible as possible via the HTML elements. 
2. Created my HTML structure based on the design template. Thinking about keeping it as simple as possible. I then validated this structure in the HTML validator tool. Here I had to make a few changes before the site was fully validated.
3. Once I had done this I decided to try testing the accessibility for screen readers and people using a keyboard. I focused on testing this in Chrome and seemed to work ok. And some elements such as the a element allowed you to as default to tab in to it and read it out using the screen reader. 
4. I read up on the aria attributes. I decided to use tabindex=”0 “on elements that were per default not tabbable/read so they would be inline with elements that had this function as per default. 
5. I also used the aria-hidden=”true” so certain elements wouldn’t be read out or focused on. This was useful to use for example on the image-container on the project cards that were wrapped in an a tag. This meant that the alt wasn’t read out by the screen reader as and only the text area. Otherwise it was too much information to be read out. And for users using the keyboard they could still focus on the a tag if they wanted to use enter to open the link. 
6. Once I felt happy with the accessibility I started working on creating my class names in HTML and implementing the CSS. Even though the page looks quite simple design wise, it actually has a lot of styling and components to it. Such as making the header area with the background image and the other elements on top of it and showing/hiding areas in the portfolio and other thoughts sections. I started with mobile first and just worked through the mobile design section by section. Once I had done this for mobile, tablet and desktop making changes inline with the design templates, I had so much CSS code. So I realised that I’d need to optimise my classes and CSS, which is something I did in the end stages. 
7. When my styling was complete I checked my page in Firefox and Edge. The styling was working the same as in Chrome, which was nice to see. 
8. Then I tested the accessibility in these browsers. In Firefox it works the same as in Chrome, but in Edge I had an issue with the Cluedo and pizzabot project cards. On the mobile view they are hidden using display: none. In the tablet and desktop view they are made visible using display: block. But when I tried to tab on these areas, the outline that you get around the content wasn’t showing. However I could tab onto them and I saw this as the tab didn’t move to the next area that had the tab outline for two tabs. Also I pressed enter on those areas individually and this opened the links for those areas. 
9. I tried fixing this issue with help from Van. I used tabindex on those cards in the text area of the card. This did allow for the text area to have a tab outline around it. However the area was then tabbable twice in Chrome. The issue with this was that the screen reader would read out this section twice, which I didn’t want. I still have to find a solution for this so the tabbing works the same across all browsers. 
10. But then I turned on the Microsoft narrator screen reader. And this actually highlighted these areas when they were tabbed on. So that worked much better then just letting the Edge browser show you the tabbed on elements. 
11. Then I cleaned up my CSS so there weren’t as many duplications and checked my HTML code in the validator to make sure that it was still ok. I did get one error relating to a header, but I tried to fix this and there was still an error. 

## Things I’ve learnt:
1. Which semantic HTML elements to use when making a site that needs to meet accessibility requirements. 
2. If the HTML elements don’t support keyboard and screen reader accessibility, which aria attributes can be used to make these elements accessible. And which can be used to not read through an element e.g. aria-hidden.
3. How to follow a design created by someone else, and make this look as intended using HTML and CSS. And how to think logically when it comes to structuring your HTML and applying classes and using these in an efficient way so the CSS code is optimised. 
4. How to keep my code clean and refactor CSS code so there are no duplications.
5. How to use more than one class name in an HTML element.
6. How to test accessibility across different browsers. And how to tackle issues that arise. 
7. Using different browser dev tools. 
8. How to present myself, my skills and projects created thus far. 
9. More experience using the display: hide and none.
10. Practising how to structure my workflow and achieve small tasks based on the outlined requirements and brief. 

## What I’d like to understand better or get feedback on:
1. More information on how to tackle cross browser issues in terms of accessibility and styling.
2. The standard process for people who are working with accessibility on websites. If they use a screen reader on their computer or one that can be added as an extension in the browser. 
3. How do blind people who are using screen readers use touch screen devices.

## Link to deployed site
https://modest-lamarr-f6ca06.netlify.app/


