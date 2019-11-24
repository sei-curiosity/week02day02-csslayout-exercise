[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

## Exercise Intro:


All exercises based on the following HTML structure (do not change the HTML structure, or it will lose the meaning of practice), all you need to do is to add css code in *layout* area to change the layout of the page. 


HTML:
```html
<div id="container">
	<div id="header">Header</div>
	<div id="wrapper">
		<div id="content">Content</div>
	</div>
	<div id="navigation">Navigation</div>
	<div id="extra">Extra stuff</div>
	<div id="footer">Footer</div>
</div>
```

CSS:
```css
/*basic style*/
#container { 
    font-size: 12px; 
    font-family: arial, sans-serif;
}
p { 
    margin: 0 10px 10px;
}
#header {
    height: 80px; 
    background-color: rgb(238,238,238); 
    color: rgb(122,177,36); 
    padding-left: 10px; 
    line-height: 80px; }
#header h1 {
    margin: 0;
}
#navigation {
    background-color: rgb(186,203,253);
}
#extra {
    background-color: rgb(253,133,67);
}
#footer {
    height: 14px;  
    padding:5px 10px 5px 10px; 
    color: #FFF; 
    background-color: #333;
}
#footer p {
    line-height: 14px; 
    margin: 0px;
}

/* layout */

```

## Exercises

### 1.Three percentage columns(n.1)

There are three elements: *wrapper*, *navigation* and *extra*

Guide:

1. Set the width of *wrapper* to 50% and horizontally center the *wrapper* element.
2. Set width of *navigation* and *extra* to 25%, *navigation* on the left side of *wrapper*, *extra* on the right.

Example:

![image](/images/40LayoutExercise-master_exrcise_1.html.png)


### 2. Three percentage columns(n.2)

Guide:

1. Exchanges positions of *navigation* and *extra* on the basis of exercise 1.

Example:

![image](/images/40LayoutExercise-master_exrcise_2.html.png)


### 3.Three percentage columns(n.3)

There are three elements: *content*, *navigation* and *extra*

Guide:

1. Set the *wrapper* aligned left and width to 50%,
2. Set width of *navigation*, *extra* to 25%，arrange them on the right side of *content* in order.

Example:

![image](/images/40LayoutExercise-master_exrcise_3.html.png)


### 4. Three percentage columns(n.4)

Guide:

1. Exchanges positions of *navigation* and *extra* on the basis of exercise 2.

Example:

![image](/images/40LayoutExercise-master_exrcise_4.html.png)


### Flexbox

Exercise Guide:

Using the following HTML code and by making use of Flex boxes in your newly created CSS to give the following design to the contents of the HTML.

```
<div class="Instructors">
 <div>
   <h1>Instructor 1</h1>
   <h3>Ahmed</h3>
   <p>SEI-9 Lead</p>
 </div>
 <div>
   <h1>Instructor 2</h1>
   <h3>Maha</h3>
   <p>SEI-9 Lead</p>
 </div>
 <div>
   <h1>Instructor 3</h1>
   <h3>Sami</h3>
   <p>SEI-9 IA</p>
 </div> 
  <div>
   <h1>Instructor 4</h1>
   <h3>Salman</h3>
   <p>SEI-9 IA</p>
 </div> 
</div>
```
Example:

![image](/images/flex.png)
