# HTML-CSS

Learning Unit 1-4

1.Introduction to HTML

HTML: is a markup language used by the browser to manipulate text, images, and other content, in order to display it in the required format.
Hypertext defines the link between web pages.  
A markup language is used to define the text document within the tag which defines the structure of web pages.
HTML can be combined with CSS and JavaScript.

CSS:
Cascading Style sheet is used to format the style of the webpage.
You can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out.
There are three ways to add CSS to HTML files:
Inline linking- an inline CSS is used to apply a unique style to a single HTML element
Internal linking- an internal CSS is used to define a style for a single HTML page.
Exarernal linking- an external style sheet is used to define the style for many HTML pages.

JavaScript:
JavaScript is a language used in Web development.
JavaScript is used to make interactive sites.
When working with files for the web, JavaScript needs to be loaded and run alongside HTML markup. 
You can add JavaScript code in an HTML document by employing the dedicated HTML tag <script> that wraps around JavaScript code.

2.HTML Text Formating

Text formatting in HTML refers to the way text is displayed on a web page.
 HTML offers a range of tags that can be used to format text including:
 Bold text: `<b>` or `<strong>`. We can make the text bold using the `<b>` tag. The tag uses both opening and closing tags. The text that needs to be made bold must be within `<b>` and `</b>` tag
 Italicised text: `<i>` or `<em>`. The `<i>` tag is used to italicise the text. It opens with `<i>` and ends with `</i>` tag and `<em>` tag is used to emphasize the text, with added semantic importance. It opens with `<em>` and ends with `</em>` tag. 
 Superscript and subscript text: `<sup>` or `<sub>`. The `<sup>` element is used to superscript a text and the `<sub>` element is used to subscript a text. They both have an opening and a closing tag.\

 HTML Elements:
 An element is a section of an HTML document. Some HTML elements represent visible components on a web page, such as text, images, or buttons.
 HTML elements tell the browser how to display the text, images, and other content on the page, as well as tell the browser other useful bits of information.
 HTML elements are created with tags. An HTML tag consists of text between angle brackets (<>). for an example an HTML paragraph elememnt looks like this `<p>`This is a paragraph.`</p>`
 
 HTML Headlines/Headings:
 HTML headings are used to define the headings of a page.
 There are six levels of headings defined by HTML. These 6 heading elements are h1, h2, h3, h4, h5, and h6; with h1 being the highest level and h6 being the least.

 HTML Lists:
 Lists are used to specify lists of information. 
 All lists must contain one or more lists elements.
 There are three types of lists namely:
 Unordered list- present items that do not have a particular sequence or order, they are displayed with bullet points and this is how an unordered list is created:
 <ul>
  <li>Koketso</li>
  <li>Motsikwe</li>
  <li>Moyakhe</li>
</ul>
 Orderedlist- Are used when you want to present items in a specific sequence or order. They are typically displayed by numbers or letters. this is an example of an ordered list:
 <ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
 Definition list- are used to present terms and their corresponding terms. They consist of a list of terms enclosed in ‘<dt>’  (definition term) elements and their associated definitions enclosed in`<dd>` (definition description) elements. Here's an example of a definition list:
 <dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language, used for structuring content on the web.</dd>
  
  <dt>CSS</dt>
  <dd>Cascading Style Sheets, used for styling web documents.</dd>
  
  <dt>JavaScript</dt>
  <dd>A programming language used for adding interactivity to web pages.</dd>
</dl>

HTML Quotes:
They are used to insert quoted text in a web page,for example:
HTML q tag is used to put small quotation.
`<p> Great quote on love and life.</p>`  
`<p> Dr. Seuss once said : <q>Reality is finally better than your dreams.</q></p>`
HTML blockquote tag is used to define a large quoted section.

HTML Time and Date inputs:
The HTML `<input type="datetime">` is a control for entering a date and time (hour, minute, second, and fraction of a second) based on the GMT time zone.

HTML Code, pre and br:
You can add a new line to an HTML page using the `<br>` or `<pre>` tags. The <br> tag adds a break in the page. The `<pre>` tag formats text exactly as the text appears in your code. If there are any new lines within the `<pre>` tag, those will be reflected on the final page.

3.HTML capabilities

HTML Attributes:
An attribute is used to define the characteristics of an HTML element and is placed inside the element's opening tag. All attributes are made up of two parts − a name and a value.

There are four core attributes:
ID-The id attribute of an HTML tag can be used to uniquely identify any element within an HTML page.
Tittles-The title attribute gives a suggested title for the element.
Class-The class attribute is used to associate an element with a style sheet, and specifies the class of element.
Style-The style attribute allows you to specify CSS rules within the element.

ARIA Roles:
are attributes used to enhance the accessibility of web content for users with disabilities, particularly those using assistive technologies like screen readers.

4.HTML navigation and linking

HTML Links: are a connection from one web resource to another. A link has two ends, An anchor and a direction.
The link starts at the “source” anchor and points to the “destination” anchor.

Navigation Menu:
In HTML, navigation menus are often created using lists (<ul> or <ol>) and list items (<li>). You can turn these lists into menus by styling them using CSS. Navigation menus help users navigate through different sections or pages of a website.

Linking within the same page:
You can create links that navigate to different sections within the same page by using the id attribute. This allows users to jump to specific parts of a page without reloading the entire page.

Linking to external pages:
Links in HTML are created using the <a> (anchor) element. When linking to external pages, you specify the URL of the external page in the href attribute of the anchor element. Clicking on such links takes the user to the specified external page.
