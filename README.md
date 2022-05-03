<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />

    <title>Index Html with Nerds Lesson</title>

    <!--Link to FONT AWESOME CDN - Content Delivery Network -->
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.3.1/css/all.css"
      integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU"
      crossorigin="anonymous"
    />
    <style>
      body {
        background-image: url("images/whitestairs2.jpg");
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
        font-family: arial, sans-serif;
        border-collapse: collapse;
        width: 50%;
      }

      td,
      th {
        border: 1px solid #dddddd;
        text-align: center;
        padding: 8px;
      }

      tr:nth-child(even) {
        background-color: #dddddd;
      }
    </style>
  </head>

  <body>
    <h1>&#9854;Coding I learned so Far&#9854;</h1>

    <a href="#section-fontawesome">FONT AWESOME</a>
    <a href="#section-socialmedia">SOCIAL MEDIA</a>
    <a href="#section-embedded">EMBEDDED VIDEO</a>
    <a href="#section-video">MOM'S ARRIVAL in DUBAI</a>
    <a href="#section-tables">TABLES</a>
    <hr />

    <h3 id="section-fontawesome">FONT AWESOME</h3>
    <a href="http://fontawesome.com" target="_blank">
      <i class="fas fa-address-card fa-3x"></i
    ></a>

    <hr />
    <h3 id="section-socialmedia">SOCIAL MEDIA LINKS</h3>
    <a href="http://www.twitter.com" target="_blank" aria-label="Twitter"
      ><i class="fab fa-twitter fa-3x"></i
    ></a>

    <a href="http://www.facebook.com" target="_blank" aria-label="Facebook"
      ><i class="fab fa-facebook fa-3x"></i
    ></a>

    <a href="https://www.instagram.com" target="_blank" aria-label="instagram"
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

    <hr />
    <h3 id="section-embedded">
      How embedded videos work. Web Development Class by
      <i>Colleen Van Lent.</i>
    </h3>
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/TdqQqyc7pfU"
      title="YouTube video player"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe>
    <hr />
    <h3 id="section-video">SAMPLE VIDEO</h3>

    <video width="600" height="500" controls>
      <source src="welcometodubainay.MOV.mp4" type="video/mp4" />
      <source src="mov_bbb.ogg" type="video/ogg" />
    </video>
    <p>
      This is the Video of my mom's arrival in Dubai International Airport last
      December 20, 2021.
    </p>
    <p>Video courtesy of my bro in law.</p>
    <hr />
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
    <p><a href="#">Jump to top</a></p>
    <hr />

    <br />
    <p>
      Thank you for visiting my website. For feedback and suggestions please
      click the link &#9759;.
    </p>
    <a href="mailto:suscitatio87@gmail.com">Email me &#9787;</a>
    <img src="images/ramir.jpeg" alt="Beautiful" />
  </body>
</html>
