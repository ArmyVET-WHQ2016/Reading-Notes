
# **What is CSS**

 *CSS* Cascading Style Sheets allows you to create great-looking web pages.Using CSS, you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.  
 *CSS* is a language for specifying how documents are presented to users — how they are styled, laid out, etc.A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages.
 *CSS* can be used for very basic document text styling. It can even be used for effects such as animation. Have a look at the links in this paragraph for specific examples.  

## **CSS Syntax**

*CSS* is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

The following code shows a very simple CSS rule that would achieve the styling described above:

h1 {
    color: red;
    font-size: 5em;
}

*CSS*  properties have different allowable values, depending on which property is being specified.A CSS stylesheet will contain many such rules, written one after the other.

### **CSS Modules**

As there are so many things that you could style using CSS, the language is broken down into modules.At this stage, you don't need to worry too much about how CSS is structured; however, it can make it easier to find information if, for example, you are aware that a certain property is likely to be found among other similar things, and is therefore, probably in the same specification.

#### **CSS Specification**

All web standards technologies: HTML, CSS, JavaScript, etc. are defined in giant documents called specificationsor "specs", which are published by standards organizations such as the W3C, WHATWG, ECMA, or Khronos and define precisely how those technologies are supposed to behave.

CSS is no different — it is developed by a group within the W3C called the CSS Working Group.New CSS features are developed or specified by the CSS Working Group — sometimes because a particular browser is interested in having some capability, other times because web designers and developers are asking for a feature, and sometimes because the Working Group itself has identified a requirement.

##### **Browser Support**

After a CSS feature has been specified, then it is only useful for us in developing web pages if one or more browsers have implemented the feature.*This means that the code has been written to turn the instruction in our CSS file into something that can be output to the screen*

The browser support status is shown on every MDN CSS property page in a section named "Browser compatibility" — use information in this section to check if the property can be used on your website
