## FIGMA to Astro
___

### FIGMA notes

#### To create color style (variable) click on 4 dots (style) of the Fill property on the right and + of the color styles. Name your new color style and click on Create Style button

#### To color in a new element into a newely created color variable element, select element, click on the color under fill, and choose a local colors in the drop down menu at the bottom of a opened small window.

#### To create a componet set, select elements and click on the create component set at the dropdown at the top of the screen (button on the left).

#### To add effects to an element, like blur effect, click the + next to a effects tool on the right panel, choose blur from the drop down and click on the sun icon on the right to enter values of the effect.

#### Simpleicons plugin has Brand icons.


### Astro notes

#### We will use BaseLayout in layouts folder for any page we build on our site

#### To use template literals in Astro, wrap it in { }
<code><pre>
    <a href={link.url} class={`nav-link btn btn-${link.style}`}>{link.name}</a>    
</pre></code>

#### Setting max width for the body for very wide monitors
<code><pre>
  body {
    max-width: 2000px;
  }
</pre></code>

####

####

####

####

####

### SideNote 
#### Using filter property affects performance. Don't go crazy with it!

