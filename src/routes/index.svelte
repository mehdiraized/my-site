<script>
  // $('.navbar').on('click', 'a[href^="#"]', function (event) {
  //     event.preventDefault();
  //     $('html, body').animate({
  //         scrollTop: $($.attr(this, 'href')).offset().top
  //     }, 500);
  // });
</script>

<svelte:head>
  <title>Mehdi Rezaei</title>
  <link
    rel="stylesheet"
    href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
    integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z"
    crossorigin="anonymous" />
  <link
    rel="stylesheet"
    href="https://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css" />
</svelte:head>

<nav class="navbar fixed-top navbar-expand-lg navbar-dark page-navbar gradient">
  <div class="container">
    <a class="navbar-brand logo" href="http://mehd.ir">Mehdi Rezaei</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav mx-auto">
        <li class="nav-item item">
          <a class="nav-link" href="#work-experience">Work Experience</a>
        </li>
        <!-- <li class="nav-item item">
                    <a class="nav-link" href="#education">Education</a>
                </li> -->
        <li class="nav-item item">
          <a class="nav-link" href="#skills">Skills</a>
        </li>
        <li class="nav-item item">
          <a class="nav-link" href="#hobbies">Hobbies</a>
        </li>
      </ul>
    </div>
    <button
      on:click={() => {
        window.print();
      }}
      class="btn btn-danger download-template"
      role="button"
      aria-disabled="true">
      Download
    </button>
  </div>
</nav>
<main class="page cv-page">
  <section class="cv-block block-intro border-bottom">
    <div class="container">
      <div class="avatar">
        <img
          class="img-fluid rounded-circle"
          alt="Mehdi Rezaei"
          src="./avatar.jpg" />
      </div>
      <p>
        Hello! I am
        <strong>Mehdi Rezaei</strong>
        .
        <br />
        I am a JavaScript developer, in Tehran, Iran. I have delved into
        numerous programming languages. My interest in designing and developing
        engaging user interfaces is what drove me to specialise in Frontend
        Development.
      </p>
      <a href="tel:+989120336636" class="btn btn-outline-primary">Hire Me</a>

      <div class="row">
        <div class="col-1"><i class="ion-ios-telephone icon" /></div>
        <div class="col-5">
          <span class="text-left">+98 912 033 66 36</span>
        </div>
        <div class="col-1"><i class="ion-at icon" /></div>
        <div class="col-5">
          <span class="text-left">me@mehd.ir, mehdiraized@gmail.com</span>
        </div>
      </div>
    </div>
  </section>
  <section class="cv-block info">
    <div class="container">
      <div class="work-experience group" id="work-experience">
        <h2 class="text-center">Work Experience</h2>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>UI UX Designer</h3>
              <h4 class="organization">Tehran Graphic.</h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">10/2013 - 04/2015</time> -->
            </div>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Full Stack Developer</h3>
              <h4 class="organization">Deviant Color.</h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">05/2015 - 12/2017</time> -->
            </div>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Front End Developer</h3>
              <h4 class="organization">
                <a href="http://www.toranjit.ir/" target="_blank">Toranj IT.</a>
              </h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">05/2015 - 12/2017</time> -->
            </div>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Full Stack Developer</h3>
              <h4 class="organization">
                <a href="http://ivahid.com/" target="_blank">Ivahid.</a>
              </h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">05/2015 - 12/2017</time> -->
            </div>
          </div>
          <div class="text-muted">
            <ul>
              <li>
                <a href="http://parsfootball.com" target="_blank">
                  http://parsfootball.com
                </a>
              </li>
              <li>
                <a href="https://ahanonline.com" target="_blank">
                  https://ahanonline.com
                </a>
              </li>
              <li>
                <a href="https://khabarfarsi.com" target="_blank">
                  https://khabarfarsi.com
                </a>
              </li>
              <li>
                <a href="http://erfanmix.com" target="_blank">
                  http://erfanmix.com
                </a>
              </li>
              <li>
                <a href="http://iran-mavad.com" target="_blank">
                  http://iran-mavad.com
                </a>
              </li>
              <li>
                <a href="http://nokhbegandc.com" target="_blank">
                  http://nokhbegandc.com
                </a>
              </li>
              <li>
                <a href="http://florist.ir" target="_blank">
                  http://florist.ir
                </a>
              </li>
              <li>
                <a href="https://www.sibsms.com/site" target="_blank">
                  https://www.sibsms.com/site
                </a>
              </li>
              <li>
                <a href="http://paypax.info" target="_blank">
                  http://paypax.info
                </a>
              </li>
              <li>
                <a href="https://epanasonic.net" target="_blank">
                  https://epanasonic.net
                </a>
              </li>
              <li>
                <a href="http://dailymobile.ir" target="_blank">
                  http://dailymobile.ir
                </a>
              </li>
              <li>
                <a href="http://temp98.com" target="_blank">
                  http://temp98.com
                </a>
              </li>
              <li>
                <a href="http://myyazd-music.ir" target="_blank">
                  http://myyazd-music.ir
                </a>
              </li>
              <li>...</li>
            </ul>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Front End Developer</h3>
              <h4 class="organization">
                <a href="http://astiag.ir/" target="_blank">Astiag.</a>
              </h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">05/2015 - 12/2017</time> -->
            </div>
          </div>
          <div class="text-muted">
            <ul>
              <li>
                <a href="http://hotelsaray.ir" target="_blank">
                  http://hotelsaray.ir
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Front End Developer</h3>
              <h4 class="organization">
                <a href="https://hamitrip.com/" target="_blank">
                  Hami Andishe.
                </a>
              </h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">05/2015 - 12/2017</time> -->
            </div>
          </div>
          <div class="text-muted">
            <ul>
              <li>
                <a href="http://hipotrip.com" target="_blank">
                  http://hipotrip.com
                </a>
              </li>
              <li>
                <a href="http://tour.hipotrip.com" target="_blank">
                  http://tour.hipotrip.com
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Front End Developer</h3>
              <h4 class="organization">
                <a href="https://www.irantalent.com/" target="_blank">
                  Iran Talent.
                </a>
              </h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">12/2017 - Present</time> -->
            </div>
          </div>
          <div class="text-muted">
            <ul>
              <li>
                <a href="http://talentcoach.ir" target="_blank">
                  http://talentcoach.ir
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="item">
          <div class="row">
            <div class="col-md-6">
              <h3>Product Manager, Back End Developer</h3>
              <h4 class="organization">
                <a href="https://www.doctop.com/" target="_blank">Doctop.</a>
              </h4>
            </div>
            <div class="col-md-6">
              <!-- <time class="period">12/2017 - Present</time> -->
            </div>
          </div>
          <div class="text-muted">
            <ul>
              <li>
                <a href="http://rc.doctop.com" target="_blank">
                  http://doctop.com
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <!-- <div class="education group" id="education">
            <h2 class="text-center">Education</h2>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <h3>High School</h3>
                  <h4 class="organization">Albert Einstein School</h4>
                </div>
                <div class="col-md-6">
                  <time class="period">09/2005 - 05/2010</time>
                </div>
              </div>
              <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean eget velit ultricies, feugiat est sed, efficitur nunc, vivamus vel accumsan dui.</p>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <h3>Applied Physics</h3>
                  <h4 class="organization">Stephen Hawking College</h4>
                </div>
                <div class="col-md-6">
                  <time class="period">09/2010 - 06/2015</time>
                </div>
              </div>
              <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean eget velit ultricies, feugiat est sed, efficitur nunc, vivamus vel accumsan dui.</p>
            </div>
          </div> -->
      <div class="group" id="skills">
        <h2 class="text-center">Skills</h2>
        <div class="skills info-card">
          <h3>UI & UX (Adobe Photoshop, Sketch, Adobe XD)</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="75"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:75%" />
          </div>
          <h3>
            Front-end (Html, Css(Sass, Less), Js(ES5, ES6+), React, Vue,
            Angular)
          </h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="98"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:98%" />
          </div>
          <h3>Back-end (Nodejs, PHP, SQL, NoSQL)</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="88"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:88%" />
          </div>
          <h3>
            SEO (Analytical Mindset, Search Engineers, Secham, Internet Works,
            Content)
          </h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="85"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:85%" />
          </div>
          <h3>
            React-Native (ios, Android), Cordova (Android , ios , Window),
            NativeScript
          </h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="80"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:80%" />
          </div>
          <h3>Electron, NWJS</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="65"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:65%" />
          </div>
          <h3>Module Bundler (Webpack, Parcel) ,Task Runner (Gulp, Grunt)</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="93"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:93%" />
          </div>
          <h3>Version Controller (Git, bitbucket, gitlab, github, ...)</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="97"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:97%" />
          </div>
          <h3>Task Manager (Jira ,Tfs ,Trello ,...)</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="95"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:95%" />
          </div>
          <h3>Agile (Scrum, Kanban)</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="90"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:90%" />
          </div>
          <h3>Wordpress ( Theme, Plugin, Developer )</h3>
          <div class="progress">
            <div
              class="progress-bar"
              role="progressbar"
              aria-valuenow="95"
              aria-valuemin="0"
              aria-valuemax="100"
              style="width:95%" />
          </div>
        </div>
      </div>
      <div class="hobbies group" id="hobbies">
        <h2 class="text-center">Hobbies</h2>
        <p class="text-center text-muted">
          I love job ⅓ time life other family and friendssssss , sleep ,
          football , Berioni
        </p>
      </div>
    </div>
  </section>
  <footer class="page-footer">
    <div class="container">
      <div class="social-icons">
        <a href="https://www.facebook.com/mehdiraized">
          <i class="ion-social-facebook" title="Facebook" />
        </a>
        <a href="https://instagram.com/mehdiraized/">
          <i class="ion-social-instagram-outline" title="Instagram" />
        </a>
        <a href="https://twitter.com/mehdiraized">
          <i class="ion-social-twitter" title="Twitter" />
        </a>
      </div>
    </div>
  </footer>
</main>
