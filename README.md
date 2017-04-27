Havent managed to complete everything, but got what I could done in 4 hours. 

Things to note.

Where possible I tried to use BEM for naming css classes. This fits in with the 'component' way of thinking that everyone is moving to so it means that you are unlikely to 'accidentally' override styles intended for one class and have it affect another component.

I have done it as a flat file as I didnt want to just spin up an Angular 2 (or 4 as its now known) project and do it in there as that might indicate thats all I can do, so Ive used native javascript and a flat file to display the page.

I have created a scss file which I then compiled into a styles.css file. The original scss file directory is up on my github account for you to look at. In truth, had I had more time, I would have moved more items into variables (ie font family names, sizes etc) but I think it shows you that Im comfortable using either sass or less to generate .css files.

Used the bootstrap carousel for the images to go left or right, then added my own bespoke javascript to hide / show the text for each image. Again some stuff missing (ie a close button), but I do have the functionality to close if you click anywhere on the page once the modal is up. I did this in native javascript on the page itself just to show you I can do this with native javascript and arent reliant on a library to create a modal and open / close it.

I think some elements towards the bottom of the page I havent included as I ran out of time, however I wanted to make sure I got in the carousel , modal and the main parts in as the carousel and modal did seem to be the most important part of this, and the bits I missed are just more elements with layout.

Speaking of layout, I used Bootstrap, as thats what a lot of people are using these days however in truth Ive been using a lot more flexbox these days and probably halfway through I wish I had have just used flexbox for this, as every browser caters for it now (ie10 being the last of the non-conformists). 

