# Natalie's Portfolio 
## [https://nattan.netlify.com/](http://nattan.netlify.com/)


## Preface
A portfolio website was a project that I had previously conceptualized working on, but somehow avoided as it involved writing about myself. However, in using this project to reflect my inspirations and implementing it only after thorough wireframing, I ultimately had a lot of fun creating it.

In creating this portfolio, I wanted to reflect my skills as a developer, whilst at the same time reflecting my tastes and personality. 

## Goals
### Audience
* Prospective Employers:  Showcase a range of my technical skills, projects, abilities and interests, which allows prospective employers to determine if I am a right fit for their company.
* Fellow developers: I look forward to collaborating & working with other developers. The portfolio also serves as a platform to connect with fellow developers, through displaying the personable side of me, which otherwise cannot be gleaned from professional platforms like "linkedin".

### Primary Goals
* Provide concise, yet informative details about myself
* Light-weight / Loads quickly
* Compability across a range of devices


### Secondary Goals
* Elegant feel
* Consistent look
* Downloadable resume ties in with the portfolio's style guide

## Style Guide
![Style Guide](/assets/readme-img/styleguide.png "Style Guide")

## Design
### Logo
In designing my logo, I somehow wanted to capitalize on the fact that my name is a palindrome (NAT TAN, and drafted several geometric logo designs based on this.
![logos](/assets/readme-img/logo.jpg "Logos")


### Mood
The natural beauty found in nature provides me with a sense of amazement and a feeling of serenity.  Hence, I based my design inspiration from some the many breathtaking photos of marevellous landscapes that I had managed to find on pinterest.


![pinterest landscapes](/assets/readme-img/landscapes.png "Pinterest landscape")

[Pinterest Mood Board](https://www.pinterest.com.au/ballflagtree/serenity/)

In addition, I had a picture from a recent trip taken in Snowdonia, which I quite liked (despite it being not quite pinterest nor pro-photographer level)

![Snowdonia](/assets/readme-img/snowdonia.jpg "Snowdonia")

In using these images as inspirations, I had to strike a fine balance between allowing the images overpowering my brand, versus completely losing the context of my inspiration. Eventually settling to use vector traces of the mountains and clouds as backgrounds for some of the page elements.

![Textures](/assets/readme-img/textures.jpg "Textures")


### Fonts
I mixed and matched a number of different combinations of serif & sans-serif fonts. In experimenting with the serif fonts, I noted that their regality tended to lose the 'serenity' of the 'mood' I wanted to convey. 
![Font faces](/assets/readme-img/fontfaces.png "Font faces")

I eventually decided on a sans-serif font - "Quicksand", with the intention of paring it with "Open Sans". On testing in a browser, Quicksand worked so well as a standalone font; simply by shifting font-casing, weights and colors, I was able to denote headings and navigational elements. I thus decided to drop open sans from the font stack altogether, contributing to a more light-weight loading experience.



### Colors
In considering colour schemes, readability and good contrast was a high priority. I came across an article suggesting that [black text on a light background](http://www.allaboutvision.com/cvs/irritated.htm) provided good readability, and was easy on the eyes. 

With the colour palettes I experimented with, the base colours of a black-ish text (#B2B2B2) on a light background (#FFFFFF / #F2F2F2) remained a constant. I then experimented combining them with colours found within some of the the landscape photos.  

I was drawn to lovely shade olive-green, which in combination with my base colours, made for a decent monochromatic color scheme.

![Colors](/assets/readme-img/colors.jpg "Colors")



### Inspiration
In searching for landscape pictures on pintrest, I was fortunate to have thumbnails of websites which had a similar feel to my mood, appear on my feed. These images served as inspiration as they demonstrated how a subtle colour scheme could be used to great effect.

Some common themes of these layouts included their excellent use of whitespacing and subtle notes of grey to break up sections. I sought to incooperate these simple, yet tasteful techniques into my design.

![Inspiration](/assets/readme-img/inspiration.png "Inspiration")

### Wireframe
I created my wireframes using figma. In prioritising the content and mobile views, I quickly realised the content I had drafted was far too verbose, and worked to summarize the information, and group them into categories which made sense.

Using figma, I was also able to trial a few diffferent ways of breaking up the content, before settling on my final iteration of the design.

[Full Figma Link](https://www.figma.com/file/PX5YbCKWPLwc8yxDqeYlEb2V/Natalie's-Portfolio-Project)

![Wireframes](/assets/readme-img/wireframes.png "Wireframes")


### Usability Heuristics Considered
![Heuristics](/assets/readme-img/menubar.png "Heuristics")
1. Visibility of system status
- Navigation bar is always visible, and within easy reach of the user
- Personal brand (my logo) is clearly visible upon loading the page, and is also constantly visible within the nav bar.
- Major sections of the site are clearly labelled
2. Match between system and the real world
- Standard sections that one can expect from a portfolio page (about, portfolio, resume, contact) are labelled with standard language 
3. User control and freedom
- Navigation bar anchored to the page allows user to skip to any section of the page
4. Consistency and Standards:
- Font color for headings & body text are been kept consistent throughout the site.
- Buttons employ a consistent look throughout the page
5. Error prevention
- Contact forms have input fields set to 'required', to prevent users from submitting blank fields. 
- Approriate input field types (e.g. 'email') also helps to validate data.
6. Recognition rather than recall
- Navigation links are labelled with text, as opposed to being left purely as a symbol, as it is well known that very few symbols have a shared universal meaning.
8. Aesthetic and minimalist design
- I pruned extraneous detail from the main content, and made additional information accessible via a link to my full resume. In doing so, it was available for those who were interested, but did not interfere with the gist of the page.

## Code
### HTML / CSS
As my design was fairly minimalistic, it seemed to fit nicely into HTML's box model, and coding the HTML markup was not too troublesome. Utilising CSS flexbox in combination with media-queries allowed my site to be responsive.

In addition, there were some new elements I was able to get learn through coding this page, such as animating inline SVG, and including social media meta tags.

## Challenges
### Content
I often find it a struggle to put my thoughts into words. It was even more difficult to even phathom how to write about myself in a 'marketable' way. We did an exercise within small groups, through which we were asked some questions about ourselves. I found that through talking about ourselves with candour to my friends, I was better able to articulate my interests, passion and motivation. 

### Design 
Who knew that could choosing between fonts & colors could prove such a chore? To me, design is a lot like music. While I can appreciate a good song, I have never understood the full intricacies of what goes into the planning, writing and creation of it. 

I recall looking at a bunch of fonts fairly early on in the design process, with a reaction somewhat akin to this:
```
¯\_(ツ)_/¯
```
 It took a fair bit of experimentation before I eventually came to settle on my style.

### User Interface
Ensuring that mobile, tablet and desktop interfaces maintained a consistent design, whilst maximising 'user - friendliness' within in each device proved challenging.

Due to mobile having limited viewport, I found designing  the navigation-bar for it particularly tricky.

Whilst ubiquitous, there has been discussion that [hamburger bars are far from ideal](https://lmjabreu.com/post/why-and-how-to-avoid-hamburger-menus/). This led me to do some research on [suitable alternatives](https://apptimize.com/blog/2015/07/the-ultimate-guide-to-the-hamburger-menu/). I chanced upon articles discussing designing for mobile, which tocuhed on the concept of keeping navigation in the ["thumb zome"](https://www.smashingmagazine.com/2016/09/the-thumb-zone-designing-for-mobile-users/).


![Thumb Zone](/assets/readme-img/thumbzone.png "Thumb Zone")

Having read the "thumb zone" article, I initially designed a bottom nav-bar in mobile. However, testing it on the mobile browser led me to discover that tapping the bottom nav triggers the browser's native menu, limiting the view. This led to a full circle back to the top nav.

![Bottom Nav](/assets/readme-img/bottomnav.png "Bottom Nav") ![Top Nav](/assets/readme-img/topnav.png "Top Nav")

### Coding
#### Inconsistencies of HTML/CSS between Browsers / Devices
One of the struggles I grappled with was coming to terms with how differently CSS (in particular - some of the newer attributes) could potentially display across browsers and devices. [caniuse.com](https://caniuse.com/) proved to be an invaluable resource in checking for compatibility, as it allowed me to ensure the elements I intended to implement would display correctly.

#### 'CSS hacks' are hacky indeed.
Working purely with CSS and HTML allowed me to have a deeper appreciation for the innate capabilities of CSS. However, I discovered as 'CSS' often displayed inconsistently across platforms, one had to be careful with the 'CSS hacks' employed.

For instance, I had intended for elements within the navigation bar to change colour based on the section of the page that was scrolled to. One of the "CSS hacks" included using `a:hover` on the sections to trigger the effect. Whilst this worked like a charm on the desktop browser, most mobiles respond to `a:hover` only when tapped, and then remains in that state until a subsequent tap.

Another issue compounding this problem, was that media queries checks viewport width, rather than device type. Thus, it was not a straight forward media-query to simply check if the device responded to `a:hover` before implementing a "CSS hack".

I thus opted to omit "CSS hacks" which would display inconsistently.


### Are HTML5 semantic elements truly semantic ?
In attempting to use HTML5 semantic elements, I found numerous conflicting resources on how to use the `<article>`, `<section>` and `<header>` tags.

![Sematic 1](/assets/readme-img/semantic1.jpg "Semantic 1")

![Sematic 2](/assets/readme-img/semantic2.jpg "Semantic 2")

![Sematic 3](/assets/readme-img/semantic3.jpg "Semantic 3")

I ended up following an [article](https://codepen.io/mi-le/post/an-overview-of-html5-semantics) which was semantic to me.

### What is the best practice?
In trying to learn and practice HTML, I tried to incorporate the "best practices". However there was a multitude of conflicting information on what was truly the best practice.

Some of the conflicts I found included:
1. Keeping css styles in-line vs. each style gets its own line.

e.g.
```
.someDiv { background: red; padding: 2em; border: 1px solid black; }
```

vs.

```
.someDiv {
  background: red;
  padding: 2em;
  border: 1px solid black;
}
```

2.  Ems/Rems vs. Pixels
- Argument for Ems: ems are more scalable with different browser sizes and mobile devices
- Argument for pixels: With browser zooming, designers are defaulting to pixel based layouts

3. Using CSS shorthand

## Plans for Future Improvements
* Implementing a back-end error handling & processing of forms
    *  Deployment on netlify allows an easy set-up for form handling using netlify-forms, but allows little customisability
* Implementing a back-end content management system to allow easy updating of portfolio.

* Front-end javascript elements to optimise user experience
    * In the repeated testing of this site, I have grown quite used to the 'light-weight' load-time and feel of static elements
    * However it is possible to implement javascript to detect scroll position  and implement animations or colour changes based on this.

* Deployment on own EC2 instance, with a custom domain


## Acknowledgements
In creating this portfolio, I have my friends, teachers and family to thank. Through them, I have learnt many things. I  have learnt things ranging from how to draw with vectors to how to craft a resume. Without their love, laughs and support, this process of crafting this portfolio would not have been enjoyable.


## Final Product
The final product has been deployed on [https://nattan.netlify.com/](http://nattan.netlify.com/)
![Screencapture](/assets/readme-img/screencapture.png "Screencapture")