# Challenge1-coding
## built up a website based on AS AN / I WANT / SO THAT format.
below is the final output

https://bleachevil.github.io/Challenge2-coding/

## Acceptance Criteria
### need to sample a potential employee's previous work and present with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

#### below is the header for this page
![](https://github.com/bleachevil/Challenge2-coding/blob/main/pics/1.png?raw=true)
#### below is the code to support the header section
```
    <header>  
        <h1>Jeff</h1>    
        <main>
            <ul>
                <li> 
                    <a href="#section1">About me</a>
                </li>
                <li> 
                    <a href="#section2">Work</a>
                </li>
                <li> 
                    <a href="#section3">Contact me</a>
                </li>
                <li> 
                    <a href="#section4">Resume</a>
                </li>
            </ul>
        </main>
    </header>
```
##### *Note: link of each section with the each section below to meet UI scrolls to the corresponding section*

### lick one of the links in the navigation and UI scrolls to the corresponding section

#### below is sample code for "about me" and "work" section
```
    <section>
        <article id="section1">
            <h2>About me</h2>
                <p> my name is Jeff</p>
        </article>
        <article id="section2">
            <h2>Work</h2>
            <span>
```
##### *Note: when you selected any items on navigation bar it will direct you to the corresponding section*

### click on the link to the section about their work, application's image should be larger in size than the others and taken to that deployed application

#### below is the work section for this page
![](https://github.com/bleachevil/Challenge2-coding/blob/main/pics/2.png?raw=true)
#### below is the code to support the work section
```
<section class="card">
<h4>Challenge1-website</h4>
<a href="https://bleachevil.github.io/Challenge1-coding/"><img src="../Challenge2-coding/assets/pics/1.jpg" alt="camera"/></a>
</section>
```
#### below is the scc code to support the work section
```
.card {
    flex: 1 0 0;
    padding: 10px;
    text-align: center;
    border-style: solid;
    border-width: 1px;
  }
  .card img {
    width: auto;
    height: auto;
    /* The client insists that images be at least 400px */
    min-width: 100px;
    max-width: 100%;
    align-items: left;
  }

img:hover {
    background-color: #772014;
    color: #fff;
    transition-duration: 1s;
    height: 250px;
    width: 250px;
}

img:active {
    background: red
  }
```
##### *Note: when you howvered picture, it will inlarge and when you collected picture, it will direct you to Challenge1 website*


### resize the page or view the site on various screens and devices

#### all the section with the following code and have the size of image and text adjust based on size

#### below is the sample code
```
@media screen and (max-width:768px) {
h1 {
    font-size: 70px;
}
h2 {
    font-size: 95%
}
.card {
    max-width: 80%
  }
}
```

