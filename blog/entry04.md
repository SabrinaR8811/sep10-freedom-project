
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Blog Entry</title>
</head>


# Entry 4
##### November 24th, 2023
<div class="first-division">
<h1>Testing, testing, this section is for html?</h1>
<h2>Alright, good.</h2>
<p>So. I have been missing a lot of assignments, so I'm making up for it right now. I believe a blog entry was one of the missing assignments, no?</p>
<p>Well lucky for you, this is going to contain as much information as possible from all my missing FreeCodeCamp stuff!</p>
</div>
<h2>What I learned so far</h2>
<p>You may not see it, but all the text above this paragraph was wrapped in a div. I tried to give it some color, but apparently Github says no to CSS, even if it's wrapped inside of some style tags. Style tags are used to give a website CSS properties, such as color, background, fonts, and text sizes. Here is an example of something you can use to decorate a specific division:</p>
<p>
  <style><br>
    .first-division{<br>
      background-color: pink;<br>
      font-size: 16px;<br>
      }<br>
  </style>
</p>
<p>As you can see on the top, I also added a head. Unfortunately, the title tags appeared, which was not what I intended at all. Github is weird when it comes to HTML, and only seems to allow the very basics.</p>
<p>Speaking of which, usually there's a bunch of invisible stuff at the top of a webpage that we normally never get to see. This determines how the code will function as a whole. This typically includes the tag < doctype html> followed by the tags <-html></-html>. Usually the Doctype tag has the word "doctype" in all capital letters, and an exclamation mark before the word doctype. The html tags also don't have that little dash. However, I edited the tags to make them visible on this webpage.</p>
<p>The head usually contains a meta-charset tag, along with your style elements. Here are some more examples of things you can put within your style elements:</p>
<ol>
  <li>Background-color: this is used to give your element's background a specific color</li>
  <li>font-size: this is used to edit the size of your font, to make it easier to read or to make text smaller so you can write more</li>
  <li>font-color: this is used to give the text of your element a specific color</li>
  <li>transform: this can allow you to put your element's text in ALL CAPS, all lowercase, Or Capitalize The Beginning Of Each Letter</li>
  <li>Border: this can give your element a border to separate it from other element</li>
  <li>Border-color: this can determine the color of your border</li>
  <li>Border-radius: this can make your border have round or sharp edges</li>
  <li>Border-type: this can make your border dotted or solid</li>
  <li>Border-size: this can be used to adjust the size of your border</li>
  <li>Margin: this can put space between your element and the elements around it</li>
  <li>Padding: this can control the space between your element and its border</li>
</ol>
<p>For colors, you have several options on how you can select a color. You could use specific words, such as "color: red", "color: raspberry", "color: yellow", etc. However, you can also use hex codes to use shades of colors that might not have specific words, such as "color: #808080", "color: #ff0000", or "color: #f28500". Finally, you can use an RGB color selector to insert extremely specific shades of color. RGB has the most variety, and can be adjusted however you wish. Some examples are "color: rgb(124, 70, 173)", "color: rgb(255, 151, 69)" or "color: rgb(39, 57, 125)"</p>
<p>Usually when you use a style element, you would assign it to a specific class or ID. If you wanted to assign a style element to a class, your code would look like this:</p>
<p>
  <style><br>
  .example-class{<br>
  background-color: rgb(255, 151, 69);<br>
  }<br>
  </style>
</p>
<p>Then, you would assign the class to a specific element, such as a list, paragraph, or div. For example:</p>
<p> <-div class="example-class"><br>
  <-p>Example text</-p><br>
  Typically you wouldn't have dashes in the tags, but once again, this was the only way to make it visible.
</p>
<p>
  You can also use certain tags to make text <strong>Bold using the "strong" tag</strong>, underline text <u>using the "u" tag</u>, italicize text <em>using the "em" tag</em>, or even cross it out <s>with the help of an "s" tag</s>.
</p>
<hr>
  <p>The line right above this paragraph was made using the "hr" tag. hr is a void tag, so you don't have to add an /hr in order for it to work. This tag is very good for organizing your page into different sections. You can also make text appear semi-transparent by adjusting the opacity. This is a style element that typically looks like this:</p>
  <p>
    opacity: 0.5;
  </p>
  <p>You can also use a line-height element to adjust the space between the lines of your text. That way, your elements won't look like giant blocks of text. This is especially useful for your paragraphs, specifically the longer ones. If you're trying to write a book through webpages, or write an essay, this can help make it easier on the eyes. Here is an example of what this would look like:</p>
  <p>
    line-height: 50px;
  </p>
  <p>Of course, sometimes you might want to make your webpage interactive. You can add little buttons and checkboxes to your webpage if you want to make it into a form!</p>
  <p>
     <-form action="example-link"><br>
    <-input type="text" placeholder="example-placeholder" required><br>
    <-button type="submit">Submit</button><br>
    <-label for="exampleOption1"> <br>
  <-input id="exampleOption1" type="ex." name="exampleOption1-exampleOption2">exampleOption1<br> 
<-/label><br>
<-label for="exampleOption2"><br> 
  <-input id="exampleOption2" type="ex" name="exampleOption1-exampleOption2">exampleOption2<br> 
<-/label><br>
  <-/form><br>
  </p>
    <p>Usually, this would add a form to your website. You would need to add in a link for the results to go into. You can use this to make quizzes, texts, and surveys.</p>
    <p>When it comes to colors, though, you may not always want to use a singular, solid color. In that case, you can make your color a gradient. A gradient will make your element fade between as many colors as you'd like. One example of this is a linear gradient. The code for a linear gradient would look something like this:</p>
    <p>
      background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);
    </p>
    <p>You can also further adjust the position of your text by using the skewX and skewY properties. These properties can make your text slanted in certain ways. For example, if you were to put "transform: skewX(70deg);", your text would be slanted to the left. If you made it -70 degrees, the text would slant to the right.</p>
    <p>skewY will make your text go up or down in a diagonal, like an arrow. Negative degrees will make your text go in an upwards diagonal, positive degrees will make it a downwards diagonal.</p>
    <p>You can also use @keyframes to animate elements! You can use this to make shapes such as hearts, circles, and crescent moons! @keyframes can be used to make your elements change color, bounce up and down, etc.</p>
    <h2>Challenges</h2>
    <p>...oh boy. Challenges. This entire process was one giant challenge.</p>
    <p>I'd definitely say the most challenging part of this was making shapes. Animation itself is easy. Keyframes, infinite loops, I can handle all that. What I cannot handle is shapes because it requires so much adjustments of, well, everything. Specifically, you need border-radius, box-shadow, overlapping shapes, spread-radius, blur-radius... I managed to overcome that though. How? Through sheer force of will, blood, sweat, tears, and google. Thank you, google.</p>
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)

</html>
