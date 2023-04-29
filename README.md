# Website Overview

The website I have created is a history website about the history of human evolution. Its purpose is to provide information to anyone interested in history and keep them updated on any human evolution news. The website has three pages:

- Home
- News
- Contact

![UI Image](https://i.postimg.cc/QN0NtYc9/UI.png)

## Navigation
The navigation is located at the top of each page, linking all the pages together. When hovering over a page name, the text color changes, and when clicking on a page, it changes to a different color. The colors used complement each other well.

![Navigation Image](https://i.postimg.cc/QMF0zJTn/Nav.png)

## Home Page
Underneath the header on the home page, there is a column split into two. On the left side, there is text giving an explanation of human evolution, and on the right side, there is a photo of humans from many years ago. Below these two columns is the main section of the website - the timeline. The timeline is created using a list and gives a brief description of the event, some of which include images. The images are placed in columns to take up half of the screen. The timeline uses a combination of orange, white, and yellow text. At the bottom of the home page, there is a video that can be played.

![Home Page Image](https://i.postimg.cc/vBRLNFMc/Home.png)

## News Page
The news page provides up-to-date information on human evolution, perfect for anyone interested in history and wanting to stay informed. Like the home page, the news page uses a list and similar colors. Each updated news entry includes a date, so users know how recent the information is.

![News Page Image](https://i.postimg.cc/05nDpJ66/News.png)

## Contact Page
The contact page has a form for users to send messages, usually for business purposes. The form includes three fields: Name, Email, Subject, and Message. Each field is required, and if left blank, a message will appear.

![Contact Page Image](https://i.postimg.cc/6Qx8s92J/Contact.png)

## Bugs
There was an issue getting the image to be the correct size in the columns on the home page, which was fixed by adding this code to the CSS file:

```css
img {
  max-width: 100%;
  height: auto;
}

 All of the bugs have been fixed. 

## Testing

I opened my website in the Safari and Brave browsers, and it works. I used media enquiries to make the website responsive and tested it on smaller devices.

## Validation

I put my code into the HTML and CSS validators and had no errors:

- HTML Validator: https://validator.w3.org/#validate_by_input
- CSS Validator: https://jigsaw.w3.org/css-validator/#validate_by_input

The website's accessibility score was great on Lighthouse.

![Lighthouse Score Image](https://i.postimg.cc/brtgvyT0/Lighthouse.png)


## Deployment
I uploaded my code to github and the website can be seen on github pages - https://hkhawaja1.github.io/Project-1/

## Credits

External code from w3schools was used to help build the website, and links to those resources are commented in the code. The text on each page was found online and rewritten in my own words, with links to the sources commented in the respective pages. The images used have a CC license, and the authors are attributed under each image.
