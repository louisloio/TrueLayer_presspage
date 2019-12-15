<img src="https://user-images.githubusercontent.com/29161010/70810937-99d2af00-1dbc-11ea-851f-69e5460e6d42.png" alt="landing">

# Creating the TrueLayer Press Page - Product design perspective.

> **Brief:** We would like you to create a new static page for our website called "Press". The page should collect links to all the articles out there that talk about TrueLayer. Your goal is to create a page that "shows" rather than "telling".<br><br>At TrueLayer we love to stay up to date with what is hot in web design and we like our brand to reflect this passion of Ours.

## Problem
Brief analysis definition of the problem.
* TrueLayer want to show their expertise to boost their visibility.

## Goals
* Enhance connection with clients, partners and entrepreneurs.
* Attract job seekers. 
* Facilitate the work of journalists to be more featured into press.

## Personas
Following the goals, I identified 4 types of users with specific needs and pain:
* __Client__- he is Looking for trust, through visibility and reputation of TrueLayer brand.
* __Job seeker__- he  is Looking for company culture articles and product articles to project himself into the next job he will apply for.
* __Media contact__ -  he is looking for some articles to help him to write one. He needs press kit and guidelines to write about TrueLayer.
* __Internal__ - he is part of TrueLayer, he comes to have a look on his articles and colleagues articles, he needs to quickly find a specific article.

## Proposal
Instead of proposing a Google news feed based on publishing date, I split every articles on 3 categories to fix the needs of each personas identified. 
<br><br>
This method, allows user to directly switch into the topic is interested in and facilitate is journey in the website to help him to quickly find what is looking for.

### 3 categories
* __Press__- All external articles.
* __Insider__- All enterprise culture and story telling articles.
* __Product__- All case study and new release.

For internal user, I suggest a search bar to enter articles titles or authors, and a "sort by" input to sort article into date, authors, or others criteria.

## Prototype
To build the prototype of TrueLayer' press page, I used simple interaction flow to focus into micro-interactions.

### User journey
When the user accesses the website, he can read an article with a single click, the most recent article is highlighted to improve his visibility.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70810954-a0f9bd00-1dbc-11ea-85f7-876af142b31c.png" alt="user journey">
<br><br>

### Immersive landing animation
The top of the page is falling from the top to the bottom, it unconsciously indicate to the user the way to read the interface.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70812554-c2a87380-1dbf-11ea-8bb7-6bda873afe9d.gif" width="300" alt="animation top">
<br><br>

### Contextuel illustration
The illustration represent a book into a laptop, it enhance the context of digital magazine. When the user browse multiple TrueLayer's website, it creates a semiological language to quickly recognise where he is.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70810969-a8b96180-1dbc-11ea-8e97-9167695ca43a.png" width="300" alt="illustration top">
<br><br>

### Rounded cards
Using border-radius into components will be perceive by users such as clickable area, in fact, users equate round shape to their finger and want to touch it to trigger somethings.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70813158-f637cd80-1dc0-11ea-9791-f800cb561d34.png" width="300" alt="Rounded corner">
<br><br>
### Hover call to action
When the user hover an article, 3 elements will trigger.

* The featured image of the article is elevating to immerse the user into the article.
  
  <img src="https://user-images.githubusercontent.com/29161010/70813662-c3420980-1dc1-11ea-895a-5a5b1cc147d6.gif" width="300" alt="elevation">
  
* The title is underlined.
  
  <img src="https://user-images.githubusercontent.com/29161010/70813632-b7564780-1dc1-11ea-9f4f-43f51df49a92.png" width="300" alt="title underlying">
  
* An animated arrows appear to enhance the call to action.
  
  <img src="https://user-images.githubusercontent.com/29161010/70813694-d05ef880-1dc1-11ea-92c3-131b1eaee7d8.gif" width="300" alt="arrow moving">

All this design artefact allows the user to link every elements of one article and avoid confusion.
<br><br>

### Responsive interface
To maximise the traffic on the page I adapt the design of the interface for all devises.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70814590-b4f4ed00-1dc3-11ea-9f5f-ea9e88272dfc.png" width="300" alt="iphone">
<br><br>

## Design System
Along my research in existing TrueLayer website, I identified a few kink that can be improve especially about accessibility. To keep TrueLayer branding experience entire, I didn't modify them but I think is important to notice them.

### Gradient background
The usage of gradient for large parts of your interface is pretty tricky cause of the accessibility contrast ratio between each side.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70815587-ac9db180-1dc5-11ea-9cfd-dddb6ec348c3.png" alt="gradient">
<br><br>

### Branding colour $Sun 
The branding colour $sun is hard to use, indeed button $sun and text $sun do not reach the AA grade of the [WCAG]. So, it wont be readable for disabled users and it wont be confortable for any users.
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70815628-bcb59100-1dc5-11ea-9ecc-b5d6aed4ad55.png" alt="sun accessibility">
<br><br>

### Typography
Through my experience at Societe Generale I've made significant research on typeface and I wanted to share with you the outcome of this research. this is the reason I used Inter font to build the interface:
<br><br>
<img src="https://user-images.githubusercontent.com/29161010/70815754-fc7c7880-1dc5-11ea-86bc-a7c425330004.png" alt="inter font">
<br><br>
During a long time designers were using same fonts for print and web but a lot of study described different user behaviour with a physical or digital products. So, the first Google font was initially made to perfectly fit on screen and later in 2015 Apple created the first dynamic font SF pro which is using every Opentype feature but also font feature specifically made for digital usage. Inter and more recently Helvetica now are following this trend and has implemented those feature into there font kit.
<br><br>
The most interesting font feature is certainly the [Dynamic Metrics].

> There's of course no absolute right or wrong when it comes to expressing yourself with typography, but Inter Dynamic Metrics provides guidelines for how to best use Inter. You simply provide the optical font size, and the tracking and line height is calculated for you.

Today, as far as I know there are 3 fonts which is following this trend:
* [SF Pro] - Property of Apple Inc can't be used by any one else.
* [Helevetica Now] - The most used font family you need to pay a licence to use it.
* [Inter]- Designed by [Rasmus Andersson] Figma Designer. the font is made for design systems and is Open source.

## Conclusion
I hope you find this study interesting and I hope I will have the opportunity to go deeper in the details during face to face meeting.

You can see the interface at this url:
https://louisloio.github.io/TrueLayer_presspage/

[WCAG]: https://contrastchecker.com/
[Dynamic Metrics]: https://rsms.me/inter/dynmetrics/
[SF Pro]: https://developer.apple.com/fonts/
[Helevetica Now]: https://www.monotype.com/fonts/helvetica-now
[Inter]: https://rsms.me/inter/
[Rasmus Andersson]: https://rsms.me/about/
