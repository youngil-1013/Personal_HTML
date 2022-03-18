# Personal_HTML

This repository was created for me to review HTML (Hypertext Markup Language) and CSS (Cascading Style Sheet) concepts. I followed the [Become a Web Developer](https://www.linkedin.com/learning/paths/become-a-web-developer?u=36758476) course from LinkedIn Learning to help me get started.

## HTML elements

In this section, we will look at some HTML elements and their tags. 

All elements are defined using tags and the content of a tag is placed between the opening and closing tag which can be nested:

> `<p> this is an <em> emphasized </em> word </p>` 
>  <p> this is an <em> emphasized </em> word </p>

__Paragraphs__, well, denote where paragraphs begin and end. Without paragraphs, all text is mushed together into one big blob:

> `<p> this is a simple paragraph </p>`
> <p> this is a simple paragraph </p>

__Headlines__ are bigger and bolder than paragraphs. We actually have 6 levels of them:
> `<h1> this is the h1 headline </h1>` 
> 
> `<h2> this is the h2 headline </h2>`
> <h1> this is the h1 headline </h1>
> <h2> this is the h1 headline </h2>

__Accenting Texts__ are used to highlight texts:
> `<i>Harry Potter</i> is <b>my</b> <em>favorite</em> book. Do <strong>NOT</strong> criticize it.`
> 
> <i>Harry Potter</i> is <b>my</b> <em>favorite</em> book. Do <strong>NOT</strong> criticize it.
> 
> Note that the difference lies not in the visual aspect but on what meaning each of the tags represent.

__Lists__ can be unordered, ordered, or definition lists. The former two lists are self-explanatory, whereas definition lists can be understood as dictionaries with terms and definitions:
> <b> Unordered List </b>
> ```
> <ul>
>  <li> apple </li>
>  <li> banana </li>
>  <li> candy </li>
> </ul>
> ```
> <ul>
>  <li> apple </li>
>  <li> banana </li>
>  <li> candy </li>
> </ul>
> 
> <b> Ordered List </b>
> ```
> <ol>
>  <li> uno </li>
>  <li> dos </li>
>  <li> tres </li>
> </ol>
> ```
> <ol>
>  <li> uno </li>
>  <li> dos </li>
>  <li> tres </li>
> </ol>
> 
> <b> Definition List </b>
> ```
> <dl>
>    <dt> term </dt>
>    <dd> definition </dd> 
> </dl>
> ```
> <dl>
>    <dt> term </dt>
>    <dd> definition </dd>
> </dl>

__Quotes__ can be either used as blockquotes (entire paragraphs excerpted) or inline quotes. Note that quote marks are different for different languages:
> `<blockquote> <p> To be or not to be that is the question </p> <cite>Hamlet</cite></blockquote>`
<blockquote> <p> To be or not to be that is the question</p> <cite>Hamlet</cite></blockquote> 

> `<p lang = "en"> He said, <q>Nice to meet you</q> </p>`
> 
> `<p lang = "fr"> He said, <q>Nice to meet you</q> </p>`
> <p lang = "en"> He said, <q>Nice to meet you</q> </p>
> <p lang = "fr"> He said, <q>Nice to meet you</q> </p>
  
__Time__ elements are written between the `<time>` tag. However, we have to use the datetime attribute to specify what time we actually mean:
> `<p>Today is <time datetime = "2022-03-16T12:53">March 16, 2022</time> </p>`
> <p>Today is <time datetime = "2022-03-16T12:53">March 16, 2022</time> </p>

__Code__ can also be included with in HTML:
>`<p> This is how we print "Hello World" in Python: <code> print('Hello World') </code> </p>`
> <p> This is how we print "Hello World" in Python: <code> print('Hello World') </code> </p>
> 
> `<p> We can include < and > signs using &lt and &gt <br> and break text using &ltbr&gt </p>`
> <p> We can include &lt and &gt signs using &amp;lt and &amp;gt <br> and break text using &ltbr&gt </p>

> `<p> <pre> or put 
> silly     text
>   spaces using  the     pre tag </pre> </p>`
> <p> <pre> or put 
> silly     text
>   spaces using  the     pre tag </pre> </p>

__Attributes__ can be used to link CSS with HTML. Classes are reusable, whereas ids are unique:
> ```
> <p class = "intro" id  = "first_line"> This is the first line </p>
> <p class = "intro"> This is <em>NOT</em> the first line </p>
> ```
> Find other attributes at <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes"> MDN Web Docs</a>

__Links__ can be typed with anchor tags. We have to give it a refrence that it accesses with the href attribute:
> `<a href = "https://github.com/youngil-1013"> this is a link to my github repository </a>`
> 
> <a href = "https://github.com/youngil-1013"> this is a link to my github repository </a>
