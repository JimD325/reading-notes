**Day 5 Reading Notes**

[CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

CSS: Stands for Cascading style sheets. HTML applies a very simple format to the content you make, CSS lets you alter that format. 

[Additional Default Styles Info](https://youtu.be/spK_S0HfzFw)

Document: Typically a text file structured useing a markup language, of which HTML is the most commonly used. 
Presenting a document means converting the content of your file into a form that is more usable by your audience. Browsers are used to present documents visually. 

**CSS Syntax**
CSS is ruled based, and you define rules specifying groups of styles thats hould be applied to elements of your page ie, the main heading of the page should be in large red text. 
Rule starts with a selector, which pics the element we are going to style. 
For example, if you are selecting \<h1> you type in h1 {CSS rules go here}. 
The CSS rules go here part iside of the curly braces are the declarations
Declarations take the form of propery and values, ie you say property: value; 

CSS styles will have many rules in them, depending on the end goal you have for how you want the document to look visually. 

[MDN CSS REFERENCE](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

**CSS Modules** 

Language is broken down into modules to keep track of just how many things you can do in CSS. 

All webhsite technologies are defined in diant documents called specifications, which are published by industry standard organizations and define exactly how the technoligies are supposed to behave. 
[CSS working group](https://www.w3.org/Style/CSS/)

The above link goes to a CSS working group, which is responsible for the new features that are developed for CSS. 

**(How to add CSS)[https://www.w3schools.com/css/css_howto.asp]** 

3 ways to insert CSS
1. external css
2. internal css
3. inline css

External Css: allows you to change the look of an entire webiste by changing just one file. Each HTML page has to include a reference to the external style sheet file inside the \<link> element inside the head section.  
Basically, you can have a default style you want the CSS to impose on the page. 
Property: PropertyValueUnit; no space between value and unit. 

Internal CSS is used if one single HTML page is to have a unique style. The internal style is define inside the \<\style> element in the head section of the HTML page. 

Inline CSS allows for you to apply a unique style for a single element on the same page. In this case, you add the \<style> attribute to the element of interest. They recommend you do not use this very often. 

**whichever style is read last is the one that will take effect. ie if you have an external style telling it to be red, but you have an inline CSS telling it to be blue, it will be blue. 

**Cascading Order** 

What style will be used when there is more than one style specified for an HTML element? 

1. Inline style (inside HTML element)
2. External and internal Style Sheets (in head section)
3. Browser default