# Index

#### Part I: Data analysis
- [1.0 | Intro into the dataset](1-0_Intro-Dataset.md)
- [1.1 | Setup your data analysis environment](1-1_Environment-Setup.md)
- [1.2 | Further readings on data analysis](1-2_Collection-Data-Analysis-Libraries.md)

#### Part II: Animated data stories
- [2.0 | About data stories](2-0_Intro-Datastories.md)
- [2.1 | Further readings on animated data stories](2-1_Collection-Animated-Datastories.md)

---
# 2.1 Further readings on animated data stories:


## Web Animation Libraries
A possible way to build animated data stories is to use modern web animation frameworks (like `gsap`or `anime`). 
This offers you a lot of flexibility when you want to ship the content to the user. 
You could either provide an animated website, or you could generate a video out of that. 
As those frameworks are able to deal with anything JavaScript can touch, they should be able to interact with charting libraries, SVGs and other web elements. 


| Library      | Purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Docs/Repo                                           |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
|`gsap`| Think of GSAP as the Swiss Army Knife of javascript animation...but better. It animates anything JavaScript can touch (CSS properties, canvas library objects, SVG, React, Vue, Angular, generic objects, whatever) and it solves countless browser inconsistencies, all with blazing speed (up to 20x faster than jQuery), including automatic GPU-acceleration of transforms. See the "Why GSAP?" article for details. Most other libraries only animate CSS properties. Plus, their sequencing abilities and runtime controls pale by comparison. | https://greensock.com/gsap/ |
|`anime`| Anime.js (/ˈæn.ə.meɪ/) is a lightweight JavaScript animation library with a simple, yet powerful API. It works with CSS properties, SVG, DOM attributes and JavaScript Objects.| https://animejs.com |

## HTML5 Video Rendering
| Library      | Purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Docs/Repo                                           |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
|`html5-animation-video-renderer`| A Node.js script that renders an HTML5-based animation into a high-quality video (supports at least 1080p60). It renders the animation in a frame-by-frame basis using Puppeteer. So, even very CPU-intensive animations can be rendered without skipping frames (unlike screen recording solutions). | https://github.com/dtinth/html5-animation-video-renderer |


## Charting Libraries
| Library      | Purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Docs/Repo                                           |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| `ECharts`    |Apache EChartsTM is an open-sourced JavaScript visualization tool, which can run fluently on PC and mobile devices. It is compatible with most modern Web Browsers, e.g., IE9/10/11, Chrome, Firefox, Safari and so on. ECharts depends on ZRender, a graphic rendering engine, to create intuitive, interactive, and highly-customizable charts. |https://echarts.apache.org/examples/en/
| `Google Charts` | Interactive charts for browsers and mobile devices. | https://developers.google.com/chart |
| `RoughViz` | The rendered charts are almost like crayon drawings, with rough borders and coloring, it actually really pleases the eye. The library is super-easy to work with utilizing array-based data sets and various options easily modified. | https://github.com/jwilber/roughViz  |
| `ApexCharts.js` | ApexChart.js comes with a variety of elegant features to bring beautiful data analysis to your web pages. On paper, this library ticks nearly all the boxes you would usually want it for. With annotation capability which is relatively rare in free-to-use packages. Responsiveness and animations and to top all that off, it looks pretty great too. | https://apexcharts.com |
| more...| A good overview of java script charting libraries | https://www.codewall.co.uk/best-javascript-chart-libraries/ |


## Code Examples

### GSAP
- https://greensock.com/get-started/
- https://codepen.io/nickspiel/pen/LpepvQ
### Anime
- https://codepen.io/hussard/pen/PrpgBB
- https://codepen.io/juliangarnier/pen/mWdraw

