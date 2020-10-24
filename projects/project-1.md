---
layout: project
type: project
image: images/PR1.jpg
title: Tribute Page 
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2020-10-21
labels:
 HTML5
 CSS
 Markdown
 Jekyl
---
 
 __A project using responsive web design to show the use of HTML and CSS using Markdown with Jekyl to display__   
<br>
[Preview Rendered Code Project 1 at this Location] (https://htmlpreview.github.io/?https://github.com/Kevinrispoli/Kevinrispoli.github.io/blob/master/images/            index.html).
 {% highlight html %}
 <!DOCTYPE html>
 <html lang="en" >
 <head>
  <meta charset="UTF-8">
  <title>TRIBUITE PAGE</title>
  <link rel="stylesheet" href="./style.css">

 </head>
 <body>
 <!-- partial:index.partial.html -->
 <main id=main>

 <h1 id="title">Terrance Mckenna</h1>
 <p>Author and Free Thinker</p>
 <figure id="img-div">
 <img
  id="image"
 src="http://www.wakingtimes.com/wp-content/uploads/2017/05/Cosmos-Terence-McKenna.jpg" 
    alt= "Terrance Mckenna Profile Picture"
  />
   <figcaption id="img-caption">
   <cite>  "The Cost of Sanity in this Society is Certainly a level of Alienation" Terrance Mckenna
     </cite>  </figcaption>
   <section id="tribute-info">
     <h3 id="headline"> Terrance Mckenna researched many topics here are a few.</h3>
     <ul>
       <li>Language</li>
       <li>Philosophy</li>
       <li>Mysticism</li>
       <li>Culture</li>
       <li>Technology</li>
       <li>Ethnobotany</li>
       <blockqkuote
                    cite=https://www.insightstate.com/quotes/terence-mckenna-quotes/#:~:text=50%20Terence%20Mckenna%20Quotes%20About%20Love%2C%20Culture%2C%20Dreams%2C,you%20take%20off%20your%20clothes.%20More%20items...%20>
         <p> Terrance Mckenna had many radical ideas and concepts.<cite>“My technique is don’t believe anything. If you believe in something, you are automatically  precluded from believing its opposite.”</cite> </p>
         </blockquote>
       <h3>Pleae spend the time to open yourself to new ideas and concepts by reseaching this philosopher just click this
          <a
            id="tribute-link"
            href="https://en.wikipedia.org/wiki/Terence_McKenna" target="_blank"
            >Wikipedia Page</a>
       </h3>
       </main>
 <!-- partial -->
   <script  src="./script.js"></script>

 </body>
 </html>
{% endhighlight %}
__CSS STYLE SHEET__
{% highlight css %}
html{font-size:10px;}
body{font-family: Arial, sans-serif;
     font-size: 1.6rem;
     line-height: 1.5rem;
     text-align: center;
     color: #333;
     margin: 0;
  
}
h1{ font-size: 4rem;
    margin-bottom: 0;
}
@media (max-width: 460px; ){h1{
        font-size: 3.5rem;
  line-height: 1.2; }
}
  
h2{font-size 3.2rem}
a{color: #771e52;}
#main { margin 30px 8px;
         padding: 15px;
          border-radius: 5 px;
          background: #eee;
           }
@media (max-width: 460px ) { #main { margin: 0;}}
img{ max-width: 100%;
     display: block;
      height: auto;
      margin: 0 auto;
  
        }
#img-div{
  background:white;
  padding: 10px;
  margin: 0;
}
#img-caption {
  margin 15px 0 5px 0;
}
@media(max-width: 460px){#img-caption{ font-size: 1.4rem}
        }
#headline{ margin 50px 0;
            text-align: center;}
ul{max-width: 550px 
    margin: 0 auto 50px auto;
     text-align: left; 
      line-height: 1.6;}
li{ margin 16px 0;}
blockquote{
  font-size: italic;
  max-width: 545px;
  margin:0 auto 50px auto;
  text-align:left;
}
{% endhighlight %}
