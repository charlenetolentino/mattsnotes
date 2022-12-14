# Reading 5 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)

## Images

  An image can help style and give personal touches to a web page. The photos must be relevant to the site and well be presented in an easy to look at manner. When using photos proper credit is imperative when posting. Ask permission for the owner to use the image. This might bring up certain license agreements with them. Stock photos are an option, but you still need to provide credit to the artist. 

Using the \<img> tag you can call an image locally in the web file. Inside the \<img> tag you can also name a few attributes. 

<ul>
      <li> scr = - This tells the browser where to find the image </li>
      <li> atl= - Provides a description of an image </li>
      <li> title= - This provides a title for the image on the backend </li>
    </ul>

You can also specify the height and width inside the HTML

<ul>
      <li> width= - Specify the width in pixels  </li>
      <li> height= - Specify the height in pixels  </li>
    </ul>

<b> NOTE WHEN ADDING A PHOTO:</b>

<i>Make sure that the image is the highest quality that you can obtain. When resizing or cropping a photo a high-res photo can look great big or small but a low-res photo will look pixilated and distorted if resized to big. To resize or crop you will need to use a third part application. </i>
___

## Color

Color is an integral part to adding more style to the web page. Choosing the right color palate or theme will drastically change the mood of the user. Colors can bring out emotions or change the feelings of the person looking at it. The contrast and opacity also need to be considered when thinking about readability and style. Low contrast between colors can be hard to read where a high contrast is the easiest to read but is harder on the eyes. A medium contrast will provide the best of both worlds, easy to read and not too hard on the eyes for longer reading periods. 

There are few ways to call a color to an element in CSS. 

<ol>
      <li> RGB values - { rgb(100,200,90) }; </li>
      <li> Hex codes - { #ffffff }; </li>
      <li> Color name - { yellow }; </li>
    </ol>

In CSS3 there are a few more ways to denote color using HSL, HSLA, and RGBA. HSL stands for Hue Saturation and Lightness. Using a color wheel denoted between 0-360 degrees you can select a color. Saturation and lightness are both denoted in percentages. The A in HSLA and AGBA both mean Alpha (opacity) or the transparency of the color denoted in a number between 0 and 1.0.

<ol>
      <li> HSL ??? { hsl(75,56%,50%); } </li>
      <li> HSLA ??? { hlsa(75,56%,50%,0.5);   </li>
      <li> RGBA ??? { rgba (100,200,90,0.5); </li>
    </ol>

___

## Typeface

In short, a typeface is a specific design of type. Adding specific styling to bold or italics is a from of typeface, different kinds of fonts such as Ariel and Time New Roman, spacing around words and letters, as well as text decoration like underlining, overlining, and strike through. In CSS you can easily add stylings like bold, underline and spacing to elements but denoting specific fonts can cause some issues like licensing and eventual output to the user due to copywrite. On every computer there is a preinstalled typeface. Therefore, some pages or applications on a Mac will look different on a Windows machine. Depending on the kind of type face you can use, the way you code in CSS will vary.

___

## JPEG vs. PNG vs. GIF

<ul>
      <li> JPEG ??? Photo containing natural scene where color variation is wide varying like a photo on your last vacation </li>
      <li> PNG ??? Image that works well with transparency for text and images with logos and shapes </li>
      <li> GIF ??? An Image that makes up and animation like your favorite moving meme </li>
    </ul>

NOTE:
These are the main differences between the most popular image types in web development. Formatting these types of file will result in different outcomes. Since so much there tends to be more detail in a JPEG photo compressing it can result in less details. A PNG file can scale big or small but will lack color variety. Finally a GIF is unsuitable for transparent backgrounds. Choose the best file for your specific purpose. 


