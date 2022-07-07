![believe-in-yourself](https://raw.githubusercontent.com/RascarKapHack/RascarKapHack/37dd31f736dc4c91a8eaa813f7826a39fbe0dad8/img/if-you-believe-in-yourself-you-can-succeed.svg?style=centerme)

## 📚 1. Study Guides

<p float="left">
    <a href="https://github.com/RascarKapHack/Doc/blob/main/1.%20Study%20guide/1.%20Official%20study%20guide%20-%20Ninth%20Edition.epub">
        <img src="https://images-na.ssl-images-amazon.com/images/I/81tzCSVZrKL.jpg"
            alt="Markdown Monster icon"
            style="float: left; margin-right: 10px;"
            width="210px"
            height="297px"/>
    </a>
    <a href="https://github.com/RascarKapHack/Doc/blob/main/1.%20Study%20guide/CISSP%20All%20in%20One%20Exam%20Guide%20-%208th%20Edition.pdf">
        <img src="https://pictures.abebooks.com/isbn/9781260142655-fr.jpg"
            alt="Markdown Monster icon"
            style="float: left; margin-right: 10px;"
            width="210x"
            height="297px"/>
    </a>
    <a href="https://github.com/RascarKapHack/Doc/blob/main/1.%20Study%20guide/CISSP%20in%2021%20days%20-%20Second%20Edition.pdf">
        <img src="https://images-na.ssl-images-amazon.com/images/I/51tqaNkGpnL._SX404_BO1,204,203,200_.jpg"
            alt="Markdown Monster icon"
            style="float: left; margin-right: 10px;"
            width="210x"
            height="297px"/>
    </a>
</p>

## 📝 2. Practice questions


<p float="left">
    <a href="https://github.com/RascarKapHack/Doc/blob/main/2.%20Practice%20questions/Official%20Practice%20Tests%20-%20Third%20Edition.pdf">
    <img src="https://media.wiley.com/product_data/coverImage300/37/11197876/1119787637.jpg"
        alt="Markdown Monster icon"
        style="float: left; margin-right: 10px;"
        width="210px"
        height="297px"/> 
    </a>
    <a href="https://github.com/RascarKapHack/Doc/blob/main/2.%20Practice%20questions/Cissp%20practice%20exams%20-%20Fifth%20Edition.pdf">
    <img src="https://d1w7fb2mkkr3kw.cloudfront.net/assets/images/book/lrg/9781/2601/9781260142679.jpg"
        alt="Markdown Monster icon"
        style="float: left; margin-right: 10px;"
        width="210x"
        height="297px"/>
    </a>
</p>

## 📖 3. Additional courses
<p float="left">
    <a href="https://github.com/RascarKapHack/Doc/blob/main/3.%20Additional%20courses/Official%20ISC2%20guide%20to%20the%20cissp%20CBK%20-%20Fourth%20Edition%20-%202015.pdf">
    <img src="https://images-eu.ssl-images-amazon.com/images/I/41uq6ImdYzL._SY264_BO1,204,203,200_QL40_ML2_.jpg"
        alt="Markdown Monster icon"
        style="float: left; margin-right: 10px;"
        width="210px"
        height="297px"/>
    </a>
</p>


<style>
    * {
    box-sizing: border-box;
    }

    .slider {
    width: 300px;
    text-align: center;
    overflow: hidden;
    }

    .slides {
    display: flex;
    
    overflow-x: auto;
    scroll-snap-type: x mandatory;
    
    
    
    scroll-behavior: smooth;
    -webkit-overflow-scrolling: touch;
    
    /*
    scroll-snap-points-x: repeat(300px);
    scroll-snap-type: mandatory;
    */
    }
    .slides::-webkit-scrollbar {
    width: 10px;
    height: 10px;
    }
    .slides::-webkit-scrollbar-thumb {
    background: black;
    border-radius: 10px;
    }
    .slides::-webkit-scrollbar-track {
    background: transparent;
    }
    .slides > div {
    scroll-snap-align: start;
    flex-shrink: 0;
    width: 300px;
    height: 300px;
    margin-right: 50px;
    border-radius: 10px;
    background: #eee;
    transform-origin: center center;
    transform: scale(1);
    transition: transform 0.5s;
    position: relative;
    
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 100px;
    }
    .slides > div:target {
    /*   transform: scale(0.8); */
    }
    .author-info {
    background: rgba(0, 0, 0, 0.75);
    color: white;
    padding: 0.75rem;
    text-align: center;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    margin: 0;
    }
    .author-info a {
    color: white;
    }
    img {
    object-fit: cover;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    }

    .slider > a {
    display: inline-flex;
    width: 1.5rem;
    height: 1.5rem;
    background: white;
    text-decoration: none;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    margin: 0 0 0.5rem 0;
    position: relative;
    }
    .slider > a:active {
    top: 1px;
    }
    .slider > a:focus {
    background: #000;
    }

    /* Don't need button navigation */
    @supports (scroll-snap-type) {
    .slider > a {
        display: none;
    }
    }

    html, body {
    height: 100%;
    overflow: hidden;
    }
    body {
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(to bottom, #74ABE2, #5563DE);
    font-family: 'Ropa Sans', sans-serif;
    }
</style>

<div class="slider">
  
  <a href="#slide-1">1</a>
  <a href="#slide-2">2</a>
  <a href="#slide-3">3</a>
  <a href="#slide-4">4</a>
  <a href="#slide-5">5</a>

  <div class="slides">
    <div id="slide-1">
      1
    </div>
    <div id="slide-2">
      2
    </div>
    <div id="slide-3">
      3
    </div>
    <div id="slide-4">
      4
    </div>
    <div id="slide-5">
      5
    </div>
  </div>
</div>