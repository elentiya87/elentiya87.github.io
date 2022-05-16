<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />

    <title>HTML CSS Javascript</title>

    <!--Link to FONT AWESOME CDN - Content Delivery Network-->
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.3.1/css/all.css"
      integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU"
      crossorigin="anonymous"
    />
    <style>
      nav a {
        display: inline-block;
        font-weight: bold;
        color: #ffffff;
        background: #0006cc;
        width: 200px;
        text-align: center;
        padding: 4px;
        text-decoration: none;
        margin-bottom: 15px;
        margin-top: 10px;
      }
      a:hover {
        background: #b3b3b3;
        color: #0006cc;
      }

      a:active {
        border: 3px solid #000000;
      }
    </style>

    <style>
      div {
        float: inline-end;
        margin: 1%;
        padding: 1%;
      }
    </style>

    <style>
      header {
        text-align: center;
        font-size: 130%;
        font-style: oblique;
        color: rgb(68, 85, 135);
      }
    </style>

    <style>
      details {
        background: #cabcbc;
        text-align: right;
        font-size: 100%;
        color: royalblue;
      }
    </style>

    <style>
      section {
        background: #b3b3b3;
        text-align: right;
        font-size: 100%;
        color: royalblue;
      }
    </style>

    <style>
      h3 {
        color: rgb(126, 152, 229);
        font-family: Arial, Helvetica, sans-serif;
        line-height: 200%;
      }
    </style>
    <style>
      em {
        color: royalblue;
        font-weight: bolder;
        font-size: 120%;
        text-align: right;
      }
    </style>
    <style>
      body {
        background-image: url("images/sunrise.jpg");
        background-repeat: no-repeat;
        background-size: cover;
      }
    </style>

    <style>
      img {
        width: 50px;
        border-radius: 25px;
        float: left;
        margin-right: 10px;
        object-fit: cover;
      }
    </style>

    <style>
      table {
        color: wheat;
        font-family: arial, sans-serif;
        border-collapse: collapse;
        border-style: solid;
        border-color: cadetblue;
        width: 50%;
      }

      td,
      th {
        border: 1px solid #dddddd;
        text-align: center;
        padding: 8px;
      }

      /* tr:nth-child(even) {
        background-color: #dddddd;
      }*/
    </style>

    <style>
      footer {
        color: royalblue;
      }
    </style>
  </head>

  <body>
    <header>Elentiya D. UnbreakableSoul</header>
    <h2 style="color: rgb(86, 121, 226)">
      &#9854;Coding I learned so Far&#9854;
    </h2>
    <p>test only for the upper part of the code</p>
    <p>
      When coding always remember POUR guidelines: Percievable Operable
      Understandable Robust.
    </p>

    <details open>
      These are only just examples of my Progress. In approximated manner....
      <br />
      <section>
        Progress in this course is (45%) <progress value="2" max="5"></progress
        ><br />
        Progress in Specialization is (25%)
        <progress value="1" max="6"></progress><br />

        Progress in life goals is (50%) <progress value="1" max="2"></progress
        ><br />
      </section>
    </details>
    <nav>
      <a class="button" href="#section-fontawesome">FONT AWESOME</a>
      <a class="button" href="#section-socialmedia">SOCIAL MEDIA</a>
      <a class="button" href="#section-embedded">EMBEDDED VIDEO</a>
      <a class="button" href="#section-video">MOM'S ARRIVAL</a>
      <a class="button" href="#section-tables">TABLES</a>

      <h3 id="section-fontawesome">FONT AWESOME</h3>
      <a href="http://fontawesome.com" target="_blank">
        <i class="fas fa-address-card fa-3x"></i
      ></a>

      <h3 id="section-socialmedia">SOCIAL MEDIA LINKS</h3>
      <div>
        <a href="http://www.twitter.com" target="_blank" aria-label="Twitter"
          ><i class="fab fa-twitter fa-3x"></i
        ></a>

        <a href="http://www.facebook.com" target="_blank" aria-label="Facebook"
          ><i class="fab fa-facebook fa-3x"></i
        ></a>

        <a
          href="https://www.instagram.com"
          target="_blank"
          aria-label="instagram"
          ><i class="fab fa-instagram fa-3x"></i
        ></a>

        <a href="https://youtube.com" target="_blank" aria-label="youTube"
          ><i class="fab fa-youtube fa-3x"></i
        ></a>

        <a href="https://web.whatsapp.com" target="_blank" aria-label="whatsapp"
          ><i class="fab fa-whatsapp fa-3x"></i
        ></a>

        <a href="https://www.amazon.com" target="_blank" aria-label="amazon"
          ><i class="fab fa-amazon fa-3x"></i
        ></a>

        <a href="https://github.com/" target="_blank" aria-label="github"
          ><i class="fab fa-github fa-3x"></i
        ></a>

        <a href="https://www.google.ae" target="_blank" aria-label="google"
          ><i class="fab fa-google fa-3x"></i
        ></a>
        <a
          href="https://www.goodreads.com/"
          target="_blank"
          aria-label="goodreads"
          ><i class="fab fa-goodreads fa-3x"></i
        ></a>

        <a
          href="https://accounts.snapchat.com/"
          target="_blank"
          aria-label="snapchat"
          ><i class="fab fa-snapchat fa-3x"></i
        ></a>
        <a href="https://www.audible.com/" target="_blank" aria-label="audible"
          ><i class="fab fa-audible fa-3x"></i>
        </a>

        <a href="https://www.apple.com/" target="_blank" aria-label="apple"
          ><i class="fab fa-apple fa-3x"></i
        ></a>
      </div>
    </nav>

    <h3 id="section-embedded">
      How embedded videos work. Web Development Class by
      <i>Colleen Van Lent.</i>
    </h3>
    <iframe
      width="560"
      height="280"
      src="https://www.youtube.com/embed/TdqQqyc7pfU"
      title="YouTube video player"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe>

    <h3 id="section-video">SAMPLE VIDEO</h3>

    <video width="600" height="500" controls>
      <source src="welcometodubainay.MOV.mp4" type="video/mp4" />
      <source src="mov_bbb.ogg" type="video/ogg" />
    </video>
    <p>
      <em
        >This is the Video of my mom's arrival in Dubai International Airport
        last December 20, 2021.</em
      >
    </p>
    <p>Video courtesy of my bro in law.</p>

    <h3 id="section-tables">How to create Tables</h3>

    <table>
      <tr>
        <th>First Name</th>
        <th>Last Name</th>
        <th>Occupation</th>
        <th>Salary</th>
        <th>Tax</th>
        <th>Other Deductions</th>
        <th>Credited</th>
      </tr>

      <tr>
        <td>Ramir</td>
        <td>Mendigo</td>
        <td>Web Developer</td>
        <td>11,000 Aed</td>
        <td>Non-Taxable</td>
        <td>100</td>
        <td>10,900 aed</td>
      </tr>

      <tr>
        <td>Elentiya</td>
        <td>Suscitatio</td>
        <td>Web Developer</td>
        <td>11,000 Aed</td>
        <td>Non-Taxable</td>
        <td>300</td>
        <td>10,700 aed</td>
      </tr>
      <tr>
        <td>Ramir</td>
        <td>Mendigo</td>
        <td>Web Developer</td>
        <td>11,000 Aed</td>
        <td>Non-Taxable</td>
        <td>100</td>
        <td>10,900 aed</td>
      </tr>

      <tr>
        <td>Elentiya</td>
        <td>Suscitatio</td>
        <td>Web Developer</td>
        <td>11,000 Aed</td>
        <td>Non-Taxable</td>
        <td>300</td>
        <td>10,700 aed</td>
      </tr>
      <tr>
        <td>Ramir</td>
        <td>Mendigo</td>
        <td>Web Developer</td>
        <td>11,000 Aed</td>
        <td>Non-Taxable</td>
        <td>100</td>
        <td>10,900 aed</td>
      </tr>

      <tr>
        <td>Elentiya</td>
        <td>Suscitatio</td>
        <td>Web Developer</td>
        <td>11,000 Aed</td>
        <td>Non-Taxable</td>
        <td>300</td>
        <td>10,700 aed</td>
      </tr>
    </table>
    <p id="only"><a href="#">Jump to top</a></p>

    <footer>
      <p>
        Thank you for visiting my website. For feedback and suggestions please
        click the link &#9759;.
      </p>
      <nav>
        <a href="mailto:suscitatio87@gmail.com">Email me &#9787;</a>

        <img src="ramir.jpeg" alt="Beautiful" />
      </nav>
    </footer>
  </body>
</html>
