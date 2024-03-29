# Frontend Mentor - Pricing component with toggle solution

This is a solution to the [Pricing component with toggle challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pricing-component-with-toggle-8vPwRMIC). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

-This is a project to make a pricing widget with a toggle function to look at yearly and monthly prices for an unknown business. This project will also include a template of how to make the widget I have created. The guidlines said to make the widget as close to the images provided, but being the creative spirit I am, I made it look even better. How do I know its better? I have 10+ years of marketing experience, so I used my past experience to make the design desicions. You can look at these images to see the guidelines I was provided [/ReadME/desktop-preview.jpg] [/ReadME/mobile-design-monthly.jpg]

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- Control the toggle with both their mouse/trackpad and their keyboard
- **Bonus**: Complete the challenge with just HTML and CSS
  Note: I used JS to make the toggle button because I wanted hands on experience to learn JS better.

### Screenshot

Links to screenshots:

- [AnnualDesktopView](https://ibb.co/8rJKHPd)
  Embed: <a href="https://ibb.co/8rJKHPd"><img src="https://i.ibb.co/8rJKHPd/Annualtoggleview.png" alt="Annualtoggleview" border="0" /></a>
- [MonthlyDesktopPreview] (https://ibb.co/sQpcR7t)
  Embed: <a href="https://ibb.co/sQpcR7t"><img src="https://i.ibb.co/Qn7hQ0X/Desktoppreview.png" alt="Desktoppreview" border="0"></a><br /><a target='_blank' href='https://dedupelist.com/'>find duplicate words in text file online</a><br />
- [MobilePreview] (https://ibb.co/dt8h4dm)
  Embed:<a href="https://imgbb.com/"><img src="https://i.ibb.co/9hQMHFZ/Mobiledesign-SS.png" alt="Mobiledesign-SS" border="0" /></a>

### Links

- Solution URL: [GitHub Link To Coded Solution](https://natthedev.github.io/Pricingwidget/)
- Live Site URL: [Live site URL](https://natthedev.github.io/PricingWidgettoggle/)

## My process

I know seasoned Devs are going to snicker at this, but I started with the desktop layout over the mobile first design process.
--- Comment: When I was completeing my UX/UI Google certification, they reccommended to use mobile first design. I did that for the first project, but it was much harder for me logically to transfer mobile first to desktop. I understand the concept and why its important to do it that way for a majority of devs, but I also found out that if you know what your doing its not complicated to do it via desktop to responsive mobile design. I personally think (this is just my opinion) that the mobile first design practice is why desktop websites tend to be missing components or they lack in user first design. I will continue my practice of desktop to mobile, until it becomes apparent that I have to do it the other way around. To me personally, It makes more sense to build a desktop layout then add in responsive mobile designs. This is because logically to me, since code is read top to bottom the mobile design would be a bottom category, plus its less confusing that way to anyone reading the code. Now Ill continue with the steps.

-Step 1: Brainstorm layout, sizing, and strategy using Figma. I use Figma for anything that I create that will need to be coded. The dev mode helps out extremely when it comes to sizing and functionality. Figma is also integrated into VScode, allowing me to look at the design and styling as I code. -**(OPTIONAL:) Install live server five server extension, so you can see everything as you code instead of saving and refresh everytime you make a change in the code down the line. Also, make sure autosave is on, so you can just focus on the project and not the tedious task of save and refresh.**
-Step 2: Start with the base containers styling, mine are called:{.backgroundcont} Background container {.innerbox} Inner container that holds the main design {.priceboxcont} The container that holds the pricing containers {.pricehead} A container that holds the headings and any extra styling for the price boxes.

-Step 3: Then I created the styles for the actual pricing boxes, Toggle button, and buttons. I named the price container boxes with the plan to keep track of which was which. The 3 plans were basic, professional, and master. **ADVICE: Make all the containers a different vibrant color, you will go back and recolor later, but for now to get a good look at all the containers and each piece of the puzzle you are creating once you start the HTML coding step.**

-Step 4: This is when you have all the other styling that you think you need done, and you are ready to start coding in HTML go ahead and review the styles and make sure everything looks ready. **ADVICE: Do not separate the CSS and HTML files yet. If you are like me, then you want the styles on the same page to manipulate the styles as you go and it makes the HTML proccess go smoother because you have a checklist of the containers right there. When its all complete then separate the CSS, and clean up the HTML file.**

-Step 5: Code in HTML. I like using Div.class for this part, but the combo of div.class and div.flex is good to use too. I just prefer to have one div type when making widgets like this. Start from the top of your styling and work your way down! leave the buttons, toggle-button, and toggle labels out until the end so you can get a nice wireframe of the widget going. Once you are satisfied with how the widget looks, then continue to the next step.

-Step 6: Add in the toggle button containers, buttons, labels for the toggle, and anything else you left out. This is where it becomes more complicated. Once everything is in the right spot and laid out the way you want it to be, then its time to make the toggle switch actually work. You can use CSS and HTML only for this, but if you are wanting to get your hands dirty with JS then this is the time to do it. Bootstrap also has toggle buttons you can just copy the code and paste it in, but I suggest at least for the first 50 projects you do, do it the long way and code it all out. Just like when you are learning math in school, show your work not an outside resources work. I promise its more rewarding this way. You can use the Bootstrap code as a reference if you get stuck, or ChatGPT, but dont cut corners if you are learning. Once you have the Toggle functioning like it needs to be, and you are satisfied with everything you added in then continue to the next step.

-Step 7: This is the step I call Visual Flair Prework. This is when you fix the colors, add in images, add the favicon, and review what you have done. Go ahead and change the colors & add in the visual flair images to spruce it up. If the images are .svg files you can use this resource to get the code for the images: [URLencoder] (https://yoksel.github.io/url-encoder/) That is not considered cutting corners, this is a tool to make life simpler. To add a favicon you link it in the header. If the favicon image is a .png or .jpg drag that into VS code or what you are using and then drag the popup to the file explorer, this links the image to the root allowing you to reference it into the code using <link>.

-Step 8: Now once you have a nice prototype going, It looks the way its supposed to and it functions you can now work on the resposive design. I like to use the @media only screen (min-width:) {} function to do this step. You can do this in JS but its more complicated and messier than it needs to be. This is another reason to keep the styles on the same page so it doesnt overcomplicate this task. The reccomended mobile width is 600px, but 775px covers small tablets, so I use 775px for the responsive switch making it more user friendly. Then you can manipulate the styles to accomidate the goal screen size which was 375px for mobile. Follow the checklist and it should work perfectly. Once the design is responsive and functional move on to the next step.

-Step 9: This is Spring Cleaning. You have now finished the design! YAY! The code is still messy, so this is when you make a seperate style sheet. After copying and pasting in the styles into a CSS file you can delete the styles on the HTML file. This also includes seperating the JS, but that is optional depending on how much JS is in the file. If you are like me and made comments on the branding design, styles, and woordage at the bottom of the file you can remove that now. **DO NOT FORGET: To reference the CSS file and any other files you separated out in the heading. The favicon reference comes first then the separated files.** After all of this is done you can make a folder and put all of it into the folder. I already had github set up, but generally you would start a new repo on the main branch and sync changes as you go. Then you can push the changes to github as you go along, so this is the final change that needs to be synced and pushed.

-Step 10: YOU ARE DONE!!! If you want the widget to be an actual link instead of a local file link you can use a webhosting service like 0000Webhost or Github to do this. I chose github because its easier. For GitHub you go to the repo that you made, and go to the settings. Under pages in the settings you can set up your public link. After all of this... you are Officially Done With The Project! I suggest making a readme file like this one after you finish everything, this is optional but it is a standard business practice so its good to continue that practice. Business standard read me files are an outline usually that cites references, a breakdown summary, and covers any topic that needs to be explained in your code along with goals and insights. It also can serve as a way to take notes of acomplishments, reflect on making whatever, and a way to log things that you may forget about later on.

_Pro Tip: If the company lets you go for any reason, but has a policy about keeping the projects, read me files are documents that are protected as personal documents by law in the US. So a good practice to start, is making a copy of the team read me file, name it like ReadMe:projectname:PersonalReflections and add in all the extra things you want to say but can't (because generally the ReadMe is used by the team) in the personal file and keep the personal files in a flash drive or a drive. This allows you to have a diary of your projects, personal thoughts and feelings on a project, and what you did so if a layoff does happen you can always reference the readme files to update your resume, use the feelings and challenges you wrote about in interviews, and use them for job searching. If your boss attempts to retrieve the personal readme files, you can reference the confidentiality (privacy) act of 1974, that was updated in 2020 to accomidate technological changes and added ammendments to cover issues like personal documents and things you have created. Never use full names if you send the documents to anyone, always remember to use your resources when people are trying to take away your personal things._

### Built with/Resources

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [React](https://reactjs.org/) - JS library
- [Figma] (https://www.figma.com) - For Layout, brainstorming, and styling
- [URLencoder] (https://yoksel.github.io/url-encoder/)- for .svg images to code elements using background-image

### What I learned

- I didnt run into any challenges for the first 5 steps of my process, it seemed like smooth sailing all the way. Until I got to step 6 things started to get messy. First thing I learned was that I should've done what I said to do in my steps for step 5 & 6. I didnt leave out the buttons, toggle button, or the labels for the toggle. The buttons were part of the smooth sailing so that wasnt the issue, it was the label that gave me the most trouble. I could not for the life of me make the labels sit horizontally with the toggle button, but that wasn't a huge issue yet until I moved on to make the toggle button work. I got the JS done, which that must have been beginners luck becasue I did a fantastic first try, no debugging needed, and this is the first real project I have done using JS. Thats when I realized I had swapped the monthly and annually pricing. Honestly, Im happy that I did because it makes more sense to have monthly on the right and annually on the left. Whatever its fine. That's when I went back to the label issue. I realized I could use the display:flex to try and troubleshoot the issue, and nothing was happening. **THIS IS WHERE I FIRST LEARNED SOMETHING**: I should have left the stuff out and came back, and that flex-direction is EXTREMELY important when running into a simple issue like this. I thought the default was column and I wouldnt have to use anything, but I found out that I was wrong, and the reason the labels didnt move at all no matter what I clicked or typed was because I never set a flex direction for this variable. In the HTML I also made the mistake of <h2>monthly Annually</h2> putting them together in a single line like that was going to work. I thought maybe gap or margin would space them apart but NOPE. Big rookie mistake. Remember the yap session about using styles as a checklist and that code is read from top to bottom? Well that was the biggest mistake I made, because I didnt go by the checklist, I got ahead of myself and put it together when logically it should go how I have it now:
<div class="backgroundcont">
       <div class="innerbox">
           <div class="pricehead">
               <h1>Our Pricing</h1>
               <center>
                   <div class="toggleswitchandlabels">
                       <col style="display: flex; flex-direction: row; align-items: center;">
                       <div class="priceboxhead">
                           <h2 style="margin: 15px;">Monthly</h2>
                       </div>
                       </col>
                       <col>
                       <label class="switch">
                           <input type="checkbox" id="togglePricing">
                           <span class="slider round"></span>
                       </label></col>
                       <col>
                       <div class="priceboxhead">
                           <h2 style="margin: 15px;">Annually</h2>
                       </div>
                   </div>
               </center>
           </div>

- The next learning curve I fixed was the favicon. I would like to shout out W3 schools for explaining nothing about a _Root Directory_ I ended up scowering google to find a blog QA forum about this. Its the main folder in your files. So, generally you save code in documents then a folder, mine is called Natsdocs, yeah thats the root directory. I thought it was some fancy file named root directory that I had never seen before. NOPE. I also left adding the favicon to the end because I missed the part where it was required to add. Anyways, I also found a WAYYYY easier way to get this .png image into my _root directory_ (I really hate that term, its dumb.) you can just drag the image if its .jpg or .png into VS code and then drag that popup tab into the explorer and reference it in the header. BAM its done.

- The last learning experience I had was local file host VS webhosting (AKA an actual public website.). I thought my live server link was an actual link until I tried to open it on my phone. That prompted me to ask my friend that is also a frontend dev wtf am I doing wrong. He explained the Local file is only visible from your computer and that the public link I was trying to get has to be hosted by a webhost. Which makes sense now. I want to thank the heavens and the person that made github for making this easier on me. I stayed up until 2am central time reading about servers and webhosting before I asked my friend, and turns out I was just unseasoned to this topic and its actually way more simple if I use a 3rd party webhost.

### Continued development

- I plan to keep learning JS and Node.JS to continue my journey. I learned HTML and CSS in a month and this week was the first time actually using JS and diving in deep reading the technical docs and guides. Its a very interesting language, and actually minimizes BS I run into sometimes with HTML. My brother got so good at Go and some other languages that he actually developed his own solution to a coding issue in the logic of one framework, and now hes a multi-millionare. I aspire to use my inventive spirit that our dad blessed us with and maybe invent soemthing new or find a solution to a root problem like my brother did. I feel thats the only way to keep myself interested in backend coding as well.

- I really loved finding out how to make a local file into a webpage, but I dont fully understand the logistics. Thats something I plan to really sink my teeth in and learn.

- I want to keep improving my HTML and CSS skills even if I do feel comfortable doing it. I know theres things that I can improve on and perfect like my rookie mistake made while doing this project.

### Useful resources

- [W3Schools] (https://www.w3schools.com/) - While I know it doesnt explain everything, its an extremely great resource to learn from and use for debugging issues. This resource is how I learned HTML and CSS in a month and now I am super comfortable with it.
- [URLencoder] (https://yoksel.github.io/url-encoder/)- for .svg images to code elements using background-image. Its a great tool to decode SVG files.
- [imgbb] (https://imgbb.com/#google_vignette) This resource is a tad shady, but if you need a link for an image this is the best free tool out there besides figma.
- [Figma] (https://www.figma.com) - For Layout, brainstorming, and styling. Figma is magical, and ever expanding as a resource. If you think you know figma, I promise you dont. I love using figma to just draw things out or to actually create working prototype wireframes. I love figjam for brainstorming, collaboration, problem solving, branding formats, and evrything in between. Figma has changed my life. I thought whiteboard and Unreal Engine was cool until I was introduced to figma. I have now used it for years and I still find cool features to this day.
- [MozillaMDN] (https://developer.mozilla.org/en-US/) This website is like W3, but it explains every single term used. Its a great resource to learn from and have fun while learning to code.

## Author

- Website - [Natalee Redding](https://natthedev.github.io/PricingWidgettoggle/)
- Frontend Mentor - [@natthedev](https://www.frontendmentor.io/profile/Natthedev)
