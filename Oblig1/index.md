<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" charset="utf-8">
    <title>Homepage?</title>
    <link href = "style.css" rel = "stylesheet">
    <style>
      /*Css code that cant be global*/
      body, html {
        height: 100%;
        color: #777;
      }
      div {
        display: block;
      }
      h3 {
        letter-spacing: 5px;
        text-transform: uppercase;
        font: 20px "Lato", sans-serif;
        color: #111;
      }
      p {
        display: block;
        margin-block-start: 1em;
        margin-block-end: 1em;
        margin-inline-start: 0px;
        margin-inline-end: 0px;
      }
      @media only screen and (max-device-width: 1024px) {   /*Code for mobile since the effect of the code might not work on mobile browsers*/
        .bgimg-1, .bgimg-2, .bgimg-3 {
          background-attachment: scroll;
        }
      }
    </style>
  </head>
  <body>
    <div align = "center" class = "heading">

    <h1>Mikhail Gorbatsjov</h1>
      <ul>
        <li>
          <a href="Introduction/introduction.html">Introduction</a>
        </li>
        <li>
          <a href="Resume/resume.html">Resume</a>
        </li>
        <li>
          <a href="Portfolio/portfolio.html">Portfolio</a>
        </li>
        <li>
          <a href="About/about.html">About</a>
        </li>
      </ul>
    </div>
    <div class="bg1">
      <div class="tema">
        <a href="Introduction/introduction.html"><span class="border">Introduction</span></a>
      </div>
    </div>
    <div id="tema2">
      <a href="Resume/resume.html"><h3 style="text-align: center;">Resume</h3></a>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam aliquid quia possimus,
         vitae necessitatibus tenetur ad perspiciatis tempore autem voluptatum architecto beatae a optio magnam atque,
         eveniet similique dolore? Maiores? Lorem ipsum dolor sit amet consectetur adipisicing elit.
         Autem corporis error exercitationem molestias ullam, officiis,
         et officia aspernatur maxime sint in eveniet ex quia ad, unde possimus id consequuntur doloremque!
      </p>
    </div>
    <div class="bg2">
      <div class="tema">
        <a href="Portfolio/portfolio.html"><span class="border" style="background-color: transparent; font-size: 40px; color: #f7f7f7;">Portefolio</span></a>
      </div>
    </div>
    <div style="position: relative;">
      <div>
        <div style="color: #ddd; background-color: #282E34;text-align: center; padding: 50px 80px; text-align: justify;">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
            Ea officia accusamus harum praesentium itaque doloremque repellat pariatur quod voluptatem veritatis,
             dolore totam nostrum perferendis cupiditate vitae quisquam possimus autem? Commodi.
          </p>
        </div>
      </div>
    </div>
    <div class="bg3">
      <div class="tema">
        <a href="About/about.html"><span class="border" style="background-color:transparent;font-size:25px;color: #f7f7f7;">About</span></a>
      </div>
    </div>
    <div style="position: relative;">
      <div style="color:#ddd;background-color:#282E34;text-align:center;padding:50px 80px;text-align: justify;">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Omnis ex ad aut similique expedita incidunt ducimus suscipit asperiores aspernatur sapiente, 
          eos, fugiat non inventore debitis quas iure fugit molestias nobis?
        </p>
        </div>
    </div>
    <div class="bg1">
      <div class="tema">
        <span class="border">The end</span>
      </div>
    </div>
  </body>
</html>
© 2021 GitHub, Inc.
