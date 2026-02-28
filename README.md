<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tutorials</title>
    <style>
    body {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;line-height: 1.6;
margin: 20px 40px;
}
h1,h2 {
color: blueviolet;
}
ul {
list-style-type: square;

}
a { 
text-decoration: none;
color: brown;
font-weight: bold;
}
a:hover { 
text-decoration: none;
color:black;

}
p1 { 
text-decoration: none;
color: brown;
font-weight: bold;
}
p1:hover { 
text-decoration: none;
color:black;

}
pre{
background-color: rgb(249, 249, 249);
border-left: 4px solid blueviolet;
white-space: pre-wrap;
}
footer {
background-color: black;
Margin-top: 50px;
padding: 10px; 
text-align: center;
color: #ffffff;
border: 8px solid black;
}
    </style>
</head>
<body>
 <h1> </h1>  
 <p> Welcome to the HTML tutorial. Click on the topics below to start learning: </p>  
<h2>Topics</h2>
<ul>
<li><a href="#Introduction">Introduction to HTML</a></li>
<li><a href="#structure">HTML Document Structure</a></li>
<li><a href="#Heading">Heading</a></li>
<li><a href="#Formatting">Text Formatting</a></li>
<li><a href="#Links">Creating Links</a></li>
<li><a href="#Lists">Lists (Ordered and Unordered)</a></li>
<li><a href="#Adding">Adding Images</a></li>
<li><a href="#Creating">Creating Tables</a></li>
<li><a href="#Forms">HTML Forms</a></li>
<li><a href="#Semantic">Semantic HTML</a></li>
<li><a href="W10_01_blogweb.html">BlogWeb</a></li>
</ul>
<hr>
<h2 id="structure">HTML Document Structure</h2>
<p>An HTML document has the following basic structure...</p>
<pre>
  คำอธิบาย:
    &lt;!DOCTYPE html&gt;: ระบุว่าเป็นเอกสาร HTML5
    &lt;html&gt;: เป็นรากของเอกสาร HTML ทั้งหมด
    &lt;head&gt;: ส่วนที่ใช้เก็บข้อมูลเมตา เช่น &lt;title&gt; ชื่อหน้าเว็บ
    &lt;body&gt;: ส่วนที่จะแสดงผลบนหน้าเว็บ
    องค์ประกอบส าคัญของ HTML
    แท็ก (Tags):
    - แท็กเริ่มต้น (Opening Tag): เช่น &lt;h1&gt;
    - แท็กปิด (Closing Tag): เช่น &lt;/h1&gt;
    แอตทริบิวต์ (Attributes): คุณสมบัติของแท็ก
    - ใช้เพื่อก าหนดคุณสมบัติเพิ่มเติม เช่น href, src, width, height
    ตัวอย่าง: &lt;h1&gt;Hello, World!&lt;/h1&gt;
    &lt;img src="image.jpg" alt="A description of the image"&gt;

</pre>
<a href="#">Top</a>
<hr>
<h2 id="Introduction">Introduction to HTML</h2>
<p></p>
<pre>
  - HTML stands for Hyper Text Markup Language
 - HTML is the standard markup language for creating Web pages
 - HTML describes the structure of a Web page
 - HTML consists of a series of elements
 - HTML elements tell the browser how to display the content
 - HTML elements are represented by tags
 - HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
 - Browsers do not display the HTML tags, but use them to render the content of the page
 - HTML can embed programs written in a scripting language such as JavaScript, which affects the behavior and
content of web pages
 - HTML is not a programming language, but a markup language

</pre>
<a href="#">Top</a>
<hr>
<h2 id="Heading">Heading</h2>
<a href="w4.html">workshop</a>
<p>HTML headings are defined with the <h1> to <h6> tags..</p>
<pre>
        - &lt;h1&gt;: Heading 1
    - &lt;h2&gt;: Heading 2
    - &lt;h3&gt;: Heading 3
    - &lt;h4&gt;: Heading 4
    - &lt;h5&gt;: Heading 5
    - &lt;h6&gt;: Heading 6


</pre>
<a href="#">Top</a>
<hr>
<h2 id="Paragraph">Paragraph</h2>
<p >workshop</p>
<pre>
    HTML paragraphs are defined with the <p> tag...
 - &lt;p&gt;: 


</pre>
<a href="#">Top</a>
<hr>
<h2 id="Formatting">Text Formatting</h2>
<a href="w4_2.html">workshop</a>
<p>HTML provides various elements to format text...</p>
<pre>
 - &lt;h1&gt; to &lt;h6&gt;: Headings
- &lt;p&gt;: Paragraph
- &lt;pre&gt;: Preformatted text
- &lt;b&gt;: Bold text
- &lt;strong&gt;: Important text
- &lt;i&gt;: Italic text
- &lt;em&gt;: Emphasized text
- &lt;u&gt;: Underline text
- &lt;ins&gt;: Inserted text
- &lt;del&gt;: Deleted text
- &lt;s&gt;: Strikethrough text
- &lt;strike&gt;: Strikethrough text
- &lt;small&gt;: Smaller text
- &lt;big&gt;: Big text
- &lt;mark&gt;: Marked/highlighted text
- &lt;sub&gt;: Subscript text
- &lt;sup&gt;: Superscript text
- &lt;blockquote&gt;: Block quotation
- &lt;q&gt;: Inline quotation
- &lt;code&gt;: Code snippet


</pre>
<a href="#">Top</a>

<hr>
<h2 id="Links">Creating Links</h2>
<p1>workshop</p1>
<p>HTML links are defined with the < a > tag...</p>
<pre>
   - &lt;a href="url" target=""&gt;Link text&lt;/a&gt;
- The href attribute specifies the URL of the page the link goes to
- The target attribute specifies where to open the linked document
- _self: Open the linked document in the same window/tab
- _blank: Open the linked document in a new window/tab
- _parent: Open the linked document in the parent frame
- _top: Open the linked document in the full body of the window
- The link text is the visible part of the link
- Anchor links:
- Use the href attribute with the # symbol to link to a specific part of the page
- Use the id attribute to define the section to link to
- Example: &lt;a href="#section"&gt;Go to Section&lt;/a&gt;
- Example: &lt;h3 id="section"&gt;This is the Section&lt;/h3&gt;
- Email links:
- Use the mailto: prefix to create an email link
- Example: &lt;a href="mailto:support@example.com">email us&lt;/a&gt;
- Download links:
- Use the download attribute to create a download link
- Example: &lt;a href="file.txt" download&gt;Download Text File&lt;/a&gt;


</pre>
<a href="#">Top</a>
<hr>
<h2 id="Lists">Lists (Ordered and Unordered)
</h2>
<p1>workshop</p1>
<pre>
 HTML lists are defined with the &lt;ul&gt;, &lt;ol&gt;, and &lt;li&gt; tags...   - &lt;ul&gt;: Unordered list
- &lt;ol&gt;: Ordered list
- &lt;li&gt;: List item
- Unordered list:
- Use the &lt;ul&gt; tag to create an unordered list
- Use the &lt;li&gt; tag to create each list item
- Example:
&lt;ul&gt;
&lt;li&gt;Coffee&lt;/li&gt;
&lt;li&gt;Tea&lt;/li&gt;
&lt;li&gt;Milk&lt;/li&gt;
&lt;/ul&gt;
- Ordered list:
- Use the &lt;ol&gt; tag to create an ordered list
- Use the &lt;li&gt; tag to create each list item
- Example:
&lt;ol&gt;
&lt;li&gt;Coffee&lt;/li&gt;
&lt;li&gt;Tea&lt;/li&gt;
&lt;li&gt;Milk&lt;/li&gt;
&lt;/ol&gt;
- List style types:
- Use the list-style-type property to define the style of the list
- Example: &lt;ul style="list-style-type: disc;"&gt;
- Example: &lt;ul style="list-style-type: circle;"&gt;
- Example: &lt;ul style="list-style-type: square;"&gt;
- Example: &lt;ul style="list-style-type: none;"&gt;
- Example: &lt;ol type="1"&gt;
- Example: &lt;ol type="A"&gt;
- Example: &lt;ol type="a"&gt;
- Example: &lt;ol type="I"&gt;
- Example: &lt;ol type="i"&gt;
- Example: &lt;ol type="A" start="3"&gt;
- Example: &lt;ol type="1" start="3"&gt;
- Example: &lt;ol style="list-style-type: decimal;"&gt;
- Example: &lt;ol style="list-style-type: upper-alpha;"&gt;
- Example: &lt;ol style="list-style-type: lower-alpha;"&gt;
- Example: &lt;ol style="list-style-type: upper-roman;"&gt;
- Example: &lt;ol style="list-style-type: lower-roman;"&gt;


</pre>
<a href="#">Top</a>
<hr>
<h2 id="Adding">Adding Images</h2>
<p1>workshop</p1>
<p>HTML links are defined with the < a > tag...</p>
<pre>
  - &lt;img src="url" alt="description"&gt;
- The src attribute specifies the URL of the image
- The alt attribute provides a description of the image
- The width and height attributes provide the size of the image
- Example: &lt;img src="image.jpg" alt="description of image"&gt;
- Example: &lt;img src="image.jpg" alt="description of image" width="300" height="200"&gt;
- Image alignment:
- Use the align attribute to specify the alignment of an image
- Example: &lt;img src="image.jpg" alt="description" align="left"&gt;
- Example: &lt;img src="image.jpg" alt="description" align="right"&gt;
- Image border:
- Use the border attribute to add a border around an image
- Example: &lt;img src="image.jpg" alt="description" border="1"&gt;
- Image link:
- Use the &lt;a&gt; tag to create a link around an image
- Example: &lt;a href="url"&gt;&lt;img src="image.jpg" alt="description"&gt;&lt;/a&gt;
- Image gallery:
- Use the &lt;div&gt; tag to create an image gallery
- Use the &lt;img&gt; tag to display each image
- Example:
&lt;div class="gallery"&gt;
&lt;img src="image1.jpg" alt="Image 1"&gt;
&lt;img src="image2.jpg" alt="Image 2"&gt;
&lt;img src="image3.jpg" alt="Image 3"&gt;
&lt;/div&gt;
- flex box:
- Use the display: flex; property to create a flex container
- Use the gap property to create space between flex items
- Example:
.gallery {
display: flex;
gap: 10px;
}
.gallery img {
width: 150px;
height: 150px;
object-fit: cover;
}


</pre>
<a href="#">Top</a>
<hr>
<h2 id="Creating">Creating Tables</h2>
<p1>workshop1 workshop2</p1>
<p>HTML tables are defined with the &lt;table&gt;, &lt;tr&gt;, &lt;th&gt;, and &lt;td&gt; tags...</p>
<pre>
  - &lt;table&gt;: Table
- &lt;tr&gt;: Table row
- &lt;th&gt;: Table header
- &lt;td&gt;: Table data/cell

</pre>
<a href="#">Top</a>
<hr>
<h2 id="Forms">HTML Forms</h2>
<p>HTML forms are defined with the &lt;form&gt; tag...</p>
<pre>
  หัวข ้อเกี่ยวกับฟอร์ม
1. โครงสร้างพื้นฐานของฟอร์ม
- &lt;form>: ใชเ้ป็นตวัครอบขอ้มูลในฟอรม์
- action และ method (GET/POST): การก าหนดปลายทางและวธิสี ง่ ขอ้มลู
2. ชนิดของอินพุต (Input Types)
- &lt;input>: ชนดิ ตา่ ง ๆ เชน่ text, password, email, number,
radio, checkbox, date, file
- &lt;textarea>: ชอ่ งขอ้ความขนาดใหญ่
- &lt;select> และ &lt;option>: เมนูแบบเลื่อนลง
- &lt;datalist>: รายการตัวเลือกที่ก าหนดไว ้ล่วงหน้า
- &lt;optgroup>: กลุ่มตัวเลือก
- &lt;fieldset> และ &lt;legend>: กลุ่มข ้อมูลที่เกี่ยวข ้อง
3. ปุ่ มในฟอร์ม
- &lt;button>: ปุ่ มทั่วไป
- &lt;input type="submit"> และ &lt;input type="reset">: ป่มุ สง่ และลา้งขอ้ มลู
- &lt;input type="button">: ปุ่ มทั่วไป
- &lt;input type="image">: ปุ่ มรูปภาพ
- &lt;input type="file">: ปุ่ มอัพโหลดไฟล์
4. การจัดการป้ายก ากับ (Labels)
- &lt;label>: เพอื่ เชอื่ มกับ &lt;input> (ชว่ ยเพมิ่ การเขา้ถงึ)
- for: ระบุ id ของอินพุตที่เกี่ยวข ้อง
5. การตรวจสอบข ้อมูล (Validation)
- คณุ สมบัติเชน่ required, min, max, pattern
- การใช ้JavaScript เพื่อท าการตรวจสอบ
6. ฟอร์มแบบสมัยใหม่ (HTML5)
- placeholder: ตัวอย่างขอ้ความในชอ่ งอนิ พุต
- autofocus: ให ้ฟอร์มเริ่มต ้นโฟกัส
7. การสง่ ฟอรม์ (Form Submission)
- การสง่ ขอ้มลู ไปยังเซริฟ์ เวอร์
- การใช ้JavaScript (เชน่ onsubmit)
</pre>
<a href="#">Top</a>
<hr>
<h2 id="Semantic">Semantic HTML</h2>
<p1>workshop1 workshop2</p1>
<p>Semantic HTML elements clearly define the content of a web page...</p>
<pre>
 - &lt;header&gt;: Defines a header for a document or section
- &lt;nav&gt;: Defines navigation links
- &lt;section&gt;: Defines a section in a document
- &lt;article&gt;: Defines an article
- &lt;aside&gt;: Defines content aside from the page content
- &lt;footer&gt;: Defines a footer for a document or section

</pre>
<a href="#">Top</a>
<hr>
<h2>Myworkshop</h2>
<p1>workshop1 workshop2</p1>
<p>Semantic HTML elements clearly define the content of a web page...</p>
<ul>
<li><a href="">workshop 01 : rabbit</a></li>
<li><a href="">>workshop 01 : Login</a></li>
</ul>
<a href="#">Top</a>
<hr>
<p1>Learn more about HTML</p1>
<footer>2025 HTML Tutorial by pramot Usuwan</footer>
</body>
</html>
