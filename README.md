# Week-1-HTML-and-CSS-Introduction-to-HTML-and-CSS-
Notes on Week 1 HTML and CSS: Introduction HTML to CSS

1. Introduction to HTML

- HyperText Markup Language short for HTML is used for formating or showing content such as texts, images and videos on the web. HTML is a declarative language it does not use programming logic, loops or functions.
   
- Cascading Style Sheets short for CSS is used to style a web page. Adding background color, font size and text styling and etc are examples of the functions of CSS.
- When there is a CSS syntex error the browser skips that part and moves on to the next part.

- The web uses three different languages - HTML, CSS and JavaScript. Using these three languages developers can achieve resilience, robustness and power in their websites.

Question and Answers
- Which is the most powerful and fragile of the browser programming languages ?
  - JavaScript
- What happens when HTML is broken because of a bug in the code ?
  - The browser guesses what you meant, and does its best to fix the bug itself.
- How many elements are there in the following HTML code?
  h1 The End of the World is Nigh /h1 article Musings on our Current Social Predicament, by em Trans I. Tory /em p Random content…./p /article
  - Four, because there are four tags.

2. HTML Text Formatting

- HTML uses tags to structure web pages, tags are enclosed using less-than and greater-than symbols to mark different elements. For example displaying a paragraph on the web browser using HTML we'd use <p> </p> and then in between these tags will be the text to be displayed. HTML has many other tags that can be used to structure or format a webpage.
- HTML has 6 levels of Headline tags, h1 is the biggest headline and can be used as the main title. h2, h3.. can be used as subtitles.
- There are four elements in HTML that are used for styling text as bold and italic, these are the em and strong tags. And the other two tags are i and b.
- There are three types of Lists in HTML, Ordered lists, Unordered list and defination list.
- the li tags are used to list each item and then the ul is used to wrap around the li tags for an unordered list. ol would be used for an ordered list.
- Another type of list is the definition list. It is used to list items with terms and definitions.
-  the dt tag is used for the term and the dd tag is used for the definition. The dl tag is used to wrap around the dt and dd tags.
- Quotes in HTML are created using the blockquote tag in HTML. The text of the quote is enclosed using p tags and the attribute the quote to a person we use the cite quote. We can also use the q tags for creating inline quotes.
- HTML date and time ...   
- To display code snippets we use the code tags. Sometimes the code tags do not work when working with HTML and therefor we have to use "&lt;" of less than sign and "&gt;" sign so that HTML does execute the HTML code.
- We use the &lt; br &gt; tag to break lines in HTML and we use &lt; pre &gt; &lt; /pre&gt; tag for the browser to respect.
- In HTML subscripts, superscripts and small text are used to write text such as math and science formulae. We use the sub tag to write text below the baseline for text and we use sup tag to rise a number to a power for example. We can use the small tag to convey that something has little prominence.

Question and Answes
- How do we use HTML elements in combination with each other?
  - &lt;p&gt;Here's some text that &lt;em&gt;should&lt;/em&gt; be emphasized.&lt;/p&gt;
- Which two elements are used to mark-up subscript and superscript text?
  - &lt;sub&gt;
    &lt;sup&gt;
- Which HTML code snippet produces the output shown in this image?
  &lt;p&gt; This is a &lt;/p&gt; demonstration &lt;p&gt; of the paragraph &lt;p&gt; tag &lt;/p&gt; &lt;/p&gt;.
- When deciding which headline level to use (h1, h2, h3, h4, h5, h6) which of these statements is true?
  - We should use the level of headline that makes sense, based on the semantic meaning of content.
- Which markup is correct?
  &lt;time datetime="2025-10-08"&gt;October 8, 2025&lt;/time&gt;

3. HTML Capabilities
   
- Most web browsers have a feature called developer tools which can be used to inspect and debug HTML CSS and JavaScript code. The inspecter uses the Document Object Model short for DOM.
-  HTML attributes add power to any element an example of an attribute is the datatime attribute used on the time tag.
-  There are four highly useful global attributes. The class attribute is the most commonly used attribute.
-  It allows us to assign a reusable name to any element which can be styled using CSS for all elements sharing that class.
-  The ID attribute is similar to the class attribute, the difference is we can only use unique names once on the entire HTML. IDs are used for CSS targeting. The other two global attributes are lang and dir, the lang attribute is used to specify language of the content using a short language code. The dir attribute explicitly indicates the direction in which the text flows.
-  the ARIA roles short for Accessible Rich Internet roles are HTML attributes that provide information to assistive technologies like screen readers, braille displays and magnifiers to ensure the website is fully accessible even to people with disabitity.
-  In HTML comments are inserted by typing <!-- at the start and --!> at the end.
- We can use &nbsp; in HTML to keep words together regardless of screen display changes.
  
Questions and Answers
- How does a user gain access to the debugging features of a browser?
   - By accessing developer tools.
- Which of these attributes is NOT a global attribute?
   - datetime
- What sort of efforts require the use and understanding of ARIA attributes?
   - Those involving accessibility issues.
- How does the output from the following code appear?
  - &lt;h1&gt; This is a test. &lt;/h1&gt; &lt;p&gt; If this were an actual emergency, <!-- Should there be an actual emergency? --> there would be panic. &lt;/p&gt;

4. HTML Navigation and Linking
   
- To create a link we use the anchor element 'a', inorder for the link to work we use the href attribute with a valid URL. The URL is where the link will take us.
- href attribute stands for hypertext reference.
- Absolute URLs are URLs that point to a precise location on the web. In an absolute URL the Hypertext Transfer Protocol, HTTP or HTTPS must be included.
- Relative URLs are used to link to local web pages and media files that are used by the same website.
- Link text is between the a tags or elements, the link address is used by the href attritube.
- No more notes needed...

Questions and Answers
- The navigation items in the image below are elements in an unordered list. How is the appearance of a navigation bar created?
   - By using CSS
- Which HTML elements are commonly used in marking up navigation?
  - &lt;nav&gt;
    &lt;ul&gt;
    &lt;li&gt;
    &lt;a&gt;
- What is wrong with the following code? http://transferfink.com
  - The positions of the link text and the link address have been interchanged.
- How do we make a basic link in HTML?
  - &lt;a href="https://example.com" &gt;text to click&lt;/a&gt;
- Which address points to a different file than the others?
 - "/people/"


