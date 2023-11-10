# Portfolio-website
#SOURCE CODE
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PERSONAL PORTFOLIO</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
    }

    body {
      background-color: rgb(0, 0, 33);
      color: white;
      font-family: 'poppins', sans-serif;
    }

    nav {
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 80px;
      background-color: rgb(18 18 62);
    }

    nav ul {
      display: flex;
      justify-content: center;
    }

    nav ul li {
      list-style: none;
      margin: 0 23px;
    }

    nav ul li a {
      text-decoration: none;
      color: white;
    }

    nav ul li a:hover {
      color: rgb(153, 153, 226);
      font-size: 1.04rem;
    }

    main hr {
      border: 0;
      background: #9c97f1;
      height: 1.2px;
      margin: 60px 84px;
    }

    .left {
      font-size: 1.5rem;
    }

    .firstSection {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 120px 0;
    }

    .firstSection>div {
      width: 30%
    }

    .leftSection {
      font-size: 2rem;

    }

    .btn {
      background-color: #1e2167;
      color: white;
      border: 2px solid white;
      border-radius: 6px;
      font-size: 20px;
      cursor: pointer;
    }

    .rightSection img {
      width: 80%;

    }

    .purple {
      color: blueviolet;
    }

    .text-gray {
      color: gray;
    }

    #element {
      color: blueviolet;
    }

    .SecondSection {
      max-width: 80vw;
      margin: auto;
      height: 80vh;
    }

    .SecondSection h1 {
      font-size: 1.9rem;
    }

    .SecondSection .box {
      background: white;
      width: 76vw;
      height: 2px;
      margin: 56px 0;
      display: flex;
    }

    .SecondSection .vertical {
      height: 93px;
      width: 1px;
      background-color: white;
      margin: 0 120px;
    }

    .image-top {
      width: 23px;
      position: relative;
      top: -32px;
      left: -9px;
    }

    .vertical-title {
      position: relative;
      top: -30px;
      width: 150px;
      ;
    }

    .vertical-desc {
      position: relative;
      top: 90px;
      color: gray;
      width: 100px;
      font-size: 12px;
    }

    footer {
      background-color: #0e0e1a;

    }

    .footer {
      display: flex;
      padding: 23px 122px;
      justify-content: space-evenly;
    }

    .footer ul {
      list-style: none;
    }

    .footer>div {
      width: 233px;
    }

    footer .footer-rights {
      text-align: center;
      color: gray;
      padding: 12px 0;
    }
  </style>
</head>

<body>
  <header>
    <nav>
      <div class="left">NAVYA'S PORTFOLIO</div>
      <div class="right">
        <ul>
          <li><a href="/">HOME</a></li>
          <li><a href="/">ABOUT</a></li>
          <li><a href="/">SERVICES</a></li>
          <li><a href="/">PROJECTS</a></li>
          <li><a href="/">CONTACT ME</a></li>
        </ul>
      </div>
    </nav>
  </header>
  <main>
    <section>
      <div class="firstSection">
        <div class="leftSection">
          Hi,My name is <span class="purple">Navya Mudgal</span>
          <DIV>And I am a passionate</DIV>
          <div>Web Developer</div>
          <span id="element"></span>
          <div class="buttons">
            <button class="btn">download resume</button>
            <button class="btn">visit github</button>
          </div>

        </div>
        <div class="rightSection">
          <img src="IMG-20211206-WA0006.jpg" alt="">
        </div>
      </div>
    </section>
    <hr>
    <section class="SecondSection">
      <span class="text-gray">What I have done so far</span>
      <h1>Work Experience</h1>
      <div class="box">
        <div class="vertical">
          <img class="image-top" src="html.png" alt="">
          <div class="vertical-title">
            HTML
          </div>
          <div class="vertical-desc">
            I have studied HTML till advanced level.
            I have completed it in 10 days.
          </div>
        </div>
        <div class="vertical">
          <img class="image-top" src="css.png" alt="">
          <div class="vertical-title">
            CSS
          </div>
          <div class="vertical-desc">
            I have studied CSS till advanced level.
            I have completed in 20 days.
          </div>
        </div>
        <div class="vertical">
          <img class="image-top" src="js.png" alt="">
          <div class="vertical-title">
            JAVASCRIPT
          </div>
          <div class="vertical-desc">
            I have studied Javascript till intermediate level.
            I have completed in 30 days.
          </div>
        </div>
        <div class="vertical">
          <img class="image-top" src="bootstrap.png" alt="">
          <div class="vertical-title">
            BOOTSTRAP
          </div>
          <div class="vertical-desc">
            I am learning bootstrap till now.
          </div>
        </div>
      </div>
      </div>
    </section>
  </main>
  <footer>
    <div class="footer">
      <div class="footer-first">
        <h3>NAVYA'S PORTFOLIO</h3>
      </div>
      <div class="footer-second">
        <ul>
          <li>Email:navyamudgal2003@gmail.com </li>
          <li>Instagram :navyamudgal</li>
        </ul>
      </div>
    </div>
    <div class="footer-rights">
      Copyright &#169.navya'sportfolio.com |All Rights Reserved
    </div>
  </footer>
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed('#element', {
      strings: ['BCA Last year student', 'future web developer'],
      typeSpeed: 50,
    });
  </script>

</body>

</html>
