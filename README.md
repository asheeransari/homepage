# homepage
this is websites
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Codemate Education</title>
    <link rel="stylesheet" href="hs.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Nunito:wght@700&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    />
  </head>
  <body>
    <!--    nav bar start -->
    <nav class="navbar">
      <div class="logo">
        <img src="profile.jpg" alt="Logo" />
      </div>
      <div class="links">
        <ul id="list">
          <li><a href="home.html" target="">Home</a></li>
          <li><a href="http://" target="">About</a></li>
          <li><a href="responsiveproject.html" target="">Blog</a></li>
          <li><a href="ext.html" target="">Courses</a></li>
          <li><a href="http://" target="">Contact</a></li>
          <li><a href="signup.html" target="">Join for Free</a></li>
          <li id="close"><i class="fa-solid fa-circle-xmark " onclick="untoggle()" ></i></li>
        </ul>
      </div>
      <div class="menu">
        <img src="menu.png" onclick="toggle()" alt="">
      </div>
    </nav>
    <!--    nav bar end -->
    <!-- main part of website -->
    <main>
      <!-- page1 start -->
      <div class="page1">
        <div class="inside">
          <h1>Enhance Your Future With <span>Codemate</span></h1>
          <p>
            Unlock Your Potential, Embrace Knowledge's Might. <br />
            Explore, Learn, and Illuminate Your Mind's Light. <br />
            Empowering Minds, Enriching Lives Every Day.<br />
            Join Our Journey, Education's Endless Array.
          </p>
            <a href="ext.html" target="">Explore Our Program</a>
            <!-- <a href="http://" target="">Visit Courses</a> -->
        </div>
        <div class="inside-image">
          <img src="ninja.webp" alt="">
        </div>
      </div>
      <!-- page1 end -->
      <!-- page2 start -->
      <div class="page2">
        <div class="center">
          <h1>Awesome Features</h1>
        </div>
        <div class="cards">
          <div class="card">
            <i class="fa-solid fa-briefcase fa-lg"></i>
            <h3>Internship Opportunity</h3>
            <p>Providing Online/Offline Internship Opportunity</p>
          </div>

          <div class="card">
            <i class="fa-solid fa-graduation-cap fa-lg"></i>
            <h3>Online Learning</h3>
            <p>Providing Online/Offline Learning Courses on different Tech</p>
          </div>

          <div class="card">
            <i class="fa-solid fa-file-circle-check"></i>
            <h3>Global Certification</h3>
            <p>
              Complete Online/Offline Internship or courses and get
              Certification
            </p>
          </div>
        </div>
      </div>
      <!-- page2 end -->
      <!-- page3 start -->
      <div class="page3">
        <div class="center">
          <h1>Our Popular Courses</h1>
        </div>
        <div class="c-card">
          <div class="left">
            
            <i class="fa-solid fa-angle-left" onclick="leftScroll()"></i>
          </div>
          <div class="courese-cards">
            <div class="courses">
              <div class="img">
                <img src="c1.jpg" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>Javascript Advance Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="c2.jpg" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>HTML & CSS Advance Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="c3.jpg" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>Python Beginers Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="c4.jpg" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>Frontend Development Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="c5.jpg" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>Backend Development Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="ai-ml.png" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>AI & ML Beginers Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="c6.jpg" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>AngularJs Beginers Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="vue.png" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>VueJs Beginers Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="courses">
              <div class="img">
                <img src="ds.png" alt="" srcset="" />
              </div>
              <div class="content">
                <p>Updated 21/07/2023</p>
                <h3>Data Science Beginers Course</h3>
                <div class="rp">
                  <div class="rating">
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-solid fa-star"></i>
                    <i class="fa-regular fa-star"></i>
                  </div>
                  <div class="price">
                    <p>$49.99</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="right">
            <i class="fa-solid fa-angle-right" onclick="rightScroll()"></i>
          </div>
        </div>
      </div>
      <!-- page3 end -->
      <div class="wyjoinus">
        <div class="part-1">
          <h3>Why Join Us?</h3>
          <h2>Great Student deserve best skills</h2>
          <p>Codemate Makes it Happen..</p>
        </div>
        <div class="part-2">
          <div class="reson">
            <h2>10+</h2>
            <p>Student started their own companies</p>
          </div>
          <div class="reson">
            <h2>50+</h2>
            <p>Student having 5 stars on CodeChef</p>
          </div>
          <div class="reson">
            <h2>100+</h2>
            <p>Student working in best companies</p>
          </div>
          <div class="reson">
            <h2>15+</h2>
            <p>Student received 10+ LPA package</p>
          </div>
        </div>
