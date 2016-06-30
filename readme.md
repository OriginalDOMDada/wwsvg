WWSVG

magical world of svg’s 


SVG stands for Scalable Vector Graphics.

It is an XML-based vector image format for 2D graphics that has support for interactivity and animation.

Today major browsers for SGV support are as the following:

Internet Explorer 9+
Firefox 4+
Chrome 4+
Safari 4+
Opera 9.5+


Why is SVG a deal now? 
What are the benefits for using SVG today? 

People access the Internet from different devices with different screen size and resolution. Meaning scalability and responsive techniques are more important in web design. Because SVG is vector graphic base, it can scale any size to fit web pages.
<img>


SVG is defined by XML format. 
Unlike bitmap image formats such as JPG or PNG, it does not consist of a fixed set of dots, but of shapes and their attributes, 
SVGs can be saved as the smallest size possible. 
<img>
No matter how large the graphic gets, the XML that describes the graphic is the only thing transmitted to the client. It can be bandwidth friendly.
<img>


SVG images and their behaviors are defined in XML text files. This means that they can be searched, indexed, scripted, and compressed. 
<img>
As XML files, SVG images can be created and edited with any text editor, but are more often created with drawing software like Adobe Illustrator or Sketch.


SVG drawings can be dynamic and interactive. Time-based modifications to the elements can be described in SMIL, or can be programmed in CSS or JavsScript.

Inline w/ SVG
CSS
Javascipt


h1 Animation


simple animationts inline and css

Translate 
Scale
Rotate
Skew

<code>
Explain perameters and what not



With SVGs browser support is generally excellent...with one glaring exception: CSS transforms. This is particularly painful when it comes to animation because scale, position, rotation, and skew are so fundamental.

Think of the transform-origin as the point around which all rotating and scaling occurs, as if a pin was holding it in place there..

