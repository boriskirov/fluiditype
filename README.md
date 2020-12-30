![alt text](https://s5.gifyu.com/images/hero-fluiditype8b94beab91d8e8db.gif)

# 👁 Fluiditype
Fluiditype a simple fluid typography css helper for reading experience
  <p>Fully fluid <code>Headings</code>, <code>Paragraphs</code>, <code>Blockquotes</code>, <code>Lists</code>, <code>Highlights</code>, <code>Code snippets</code>, etc.</p>
  <p>This small CSS library serves to avoid responsive web but focus more on fluidity and systematic approach which will let the interface to communicate with the environment and not to be broken by rules. This would work great for blogs, portfolio websites and simple pages.</p>
  
## 👟 How to run
- You can download the package directly from Github.</li>
- You can run the git clone command in your Terminal to get the package.
   
   ```shell
   git clone https://github.com/Fluiditype/fluiditype.git 

   ``` 

## 🔬 What's inside
You will find a simple ``` .css ``` file which would ideally make your typography fluid and responsive to the screensize, without breaking your layout, it would impact only the typography styles. 

The main rules are set in a ``` :root ``` selector, because of it's high specificity. There we declare the global CSS variables, which can be changed and customised to answer the needs of your project.

```shell 
:root {
  --font-size: calc(12px + 0.698vw); /* The character count on */  
  --line-height: calc(var(--font-size) * 1.4);
  --letter-spacing: calc(var(--font-size) * 0.0015);
  --font-weight: 300;
}
```

### 🔠 Font-size 
Everything in the ``` fluiditype.css ``` file is dependant and connected to the :root selector font-size calculation. 

Example:
``` shell
p, li, b, i, strong, a, mark {
  font-size: var(--font-size);
  line-height: var(--line-height);
  letter-spacing: var(--letter-spacing);
  font-feature-settings: normal;
  font-family: var(--font-family);
}
```

# 🕸 Fluiditype schema 
<br>

![alt text](https://i.ibb.co/2NPb58X/Headings.png)

The Headings elements representing six levels of section headings. The ``` h1 ``` defines the most important heading. The ``` h6 ``` defines the least important heading.
<br>

![alt text](https://i.ibb.co/qdCf0bp/Paragraphs.png)

There are different text elements which are part of the Fluiditype such as ```p```paragraph element, ```blockquote``` quote element and all different styles that can be used for text like ```bold```, ```underlined```, ```deleted``` and ```mark```.
<br>

![alt text](https://i.ibb.co/9WMQNLd/Lists.png)

Ordered ```ol```and underodered ```ul```lists with the ```li``` element.
<br>

![alt text](https://i.ibb.co/b6Zq179/Code-Snippets.png)

For better documentation and reading experience we added special definitions for some main HTML elements. 
The HTML ```code``` element displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code.
The HTML ```pre``` element represents preformatted text which is to be presented exactly as written in the HTML file.
<br>

![alt text](https://i.ibb.co/b3H7Rzg/Links.png)

We also covered the behaviour of the HTML ```a``` element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address for consistency and better experience with the web typography. 


## 📝 License
Licensed under the [MIT License](./LICENSE).

## 🌐 Thanks
You can always check the cool animations on our own [Gatsby](https://gatsbyjs.com) developed website, visit [Fluiditype](https://fluiditype.com).

## 👨‍💻 Always improving
We are always working on improving [Fluiditype](https://fluiditype.com), if you want you can always contribute and ask for more, this would help us create something more meaningful.

