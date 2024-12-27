# Javascript-Learning
To understand the basics of javascript i have put the information and also a 2 videos

# Information about javascript
JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which [HTML](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content) and [CSS](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics) we have covered in much more detail in other parts of the Learning Area. HTML is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

The three layers build on top of one another nicely. Let's take a button as an example. We can mark it up using HTML to give it structure and purpose:
```
<button type="button">Player 1: Chris</button>
```
![image](https://github.com/user-attachments/assets/a8c43be1-fd9b-459a-98bc-3a65389c8be3)

Then we can add some CSS into the mix to get it looking nice:
```
button {
  font-family: "helvetica neue", helvetica, sans-serif;
  letter-spacing: 1px;
  text-transform: uppercase;
  border: 2px solid rgb(200 200 0 / 60%);
  background-color: rgb(0 217 217 / 60%);
  color: rgb(100 0 0 / 100%);
  box-shadow: 1px 1px 2px rgb(0 0 200 / 40%);
  border-radius: 10px;
  padding: 3px 10px;
  cursor: pointer;
}
```
![image](https://github.com/user-attachments/assets/40954a22-3b6e-40b5-be83-2740154db68c)

And finally, we can add some JavaScript to implement dynamic behavior:
```
const button = document.querySelector("button");

button.addEventListener("click", updateName);

function updateName() {
  const name = prompt("Enter a new name");
  button.textContent = `Player 1: ${name}`;
}
```
# Full code and live demo

Here's the full code if you want to view:
```
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>JavaScript label example</title>
    <style>
      button {
        font-family: "helvetica neue", helvetica, sans-serif;
        letter-spacing: 1px;
        text-transform: uppercase;
        text-align: center;
        border: 2px solid rgb(200 200 0 / 0.6);
        background: rgba(0, 217, 217, 0.6);
        color: rgb(100 0 0 / 1);
        box-shadow: 1px 1px 2px rgb(0 0 200 / 0.4);
        border-radius: 10px;
        padding: 3px 10px;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <button type="button">Player 1: Chris</button>

    <script>
      const button = document.querySelector("button");

      button.addEventListener("click", updateName);

      function updateName() {
        const name = prompt("Enter a new name");
        button.textContent = `Player 1: ${name}`;
      }
    </script>
  </body>
</html>`

```
And if you want to run it
go and do it in this link 👉🏼 →[Live Demo](https://mdn.github.io/learning-area/javascript/introduction-to-js-1/what-is-js/javascript-label.html)

 # Videos

[Video_1](https://www.youtube.com/watch?v=FtaQSdrl7YA)



[Video_2](https://www.youtube.com/watch?v=W6NZfCO5SIk)

### More videos 
[Check it now for mor understanding](https://www.youtube.com/results?search_query=JavaScript+Crash+Course+-+Tutorial+for+Complete+Beginners)

###### Have a good day
