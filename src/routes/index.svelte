<div class="main-wrapper">
  <header class="header min-header">
    <nav class="navbar navbar-expand-lg header-nav">
      <div class="navbar-header">
        <a id="mobile_btn" href="javascript:void(0);">
          <span class="bar-icon">
            <span />
            <span />
            <span />
          </span>
        </a>
        <a href="index.html" class="navbar-brand logo">
          <img src="assets/img/logo.png" class="img-fluid" alt="Logo" />
        </a>
      </div>
      <div class="main-menu-wrapper">
        <div class="menu-header">
          <a href="index.html" class="menu-logo">
            <img src="assets/img/logo.png" class="img-fluid" alt="Logo" />
          </a>
          <a id="menu_close" class="menu-close" href="javascript:void(0);">
            <i class="fas fa-times" />
          </a>
        </div>
        <ul class="main-nav">
          <li class="active">
            <a href="index.html">Home</a>
          </li>
          <li class="has-submenu">
            <a href="">Mentor <i class="fas fa-chevron-circle-down" /></a>
            <ul class="submenu">
              <li><a href="dashboard.html">Mentor Dashboard</a></li>
              <li><a href="bookings.html">Bookings</a></li>
              <li><a href="schedule-timings.html">Schedule Timing</a></li>
              <li><a href="mentee-list.html">Mentee List</a></li>
              <li><a href="profile-mentee.html">Mentee Profile</a></li>
              <li class="has-submenu">
                <a href="blog.html">Blog</a>
                <ul class="submenu">
                  <li><a href="blog.html">Blog</a></li>
                  <li><a href="blog-details.html">Blog View</a></li>
                  <li><a href="add-blog.html">Add Blog</a></li>
                  <li><a href="edit-blog.html">Edit Blog</a></li>
                </ul>
              </li>
              <li><a href="chat.html">Chat</a></li>
              <li><a href="invoices.html">Invoices</a></li>
              <li><a href="profile-settings.html">Profile Settings</a></li>
              <li><a href="reviews.html">Reviews</a></li>
              <li><a href="mentor-register.html">Mentor Register</a></li>
            </ul>
          </li>
          <li class="has-submenu">
            <a href="">Mentee <i class="fas fa-chevron-circle-down" /></a>
            <ul class="submenu">
              <li class="has-submenu">
                <a href="#">Mentors</a>
                <ul class="submenu">
                  <li><a href="map-grid.html">Map Grid</a></li>
                  <li><a href="map-list.html">Map List</a></li>
                </ul>
              </li>
              <li><a href="search.html">Search Mentor</a></li>
              <li><a href="profile.html">Mentor Profile</a></li>
              <li><a href="bookings-mentee.html">Bookings</a></li>
              <li><a href="checkout.html">Checkout</a></li>
              <li><a href="booking-success.html">Booking Success</a></li>
              <li><a href="dashboard-mentee.html">Mentee Dashboard</a></li>
              <li><a href="favourites.html">Favourites</a></li>
              <li><a href="chat-mentee.html">Chat</a></li>
              <li>
                <a href="profile-settings-mentee.html">Profile Settings</a>
              </li>
              <li><a href="change-password.html">Change Password</a></li>
            </ul>
          </li>
          <li class="has-submenu">
            <a href="">Pages <i class="fas fa-chevron-circle-down" /></a>
            <ul class="submenu">
              <li><a href="voice-call.html">Voice Call</a></li>
              <li><a href="video-call.html">Video Call</a></li>
              <li><a href="search.html">Search Mentors</a></li>
              <li><a href="components.html">Components</a></li>
              <li class="has-submenu">
                <a href="invoices.html">Invoices</a>
                <ul class="submenu">
                  <li><a href="invoices.html">Invoices</a></li>
                  <li><a href="invoice-view.html">Invoice View</a></li>
                </ul>
              </li>
              <li><a href="blank-page.html">Starter Page</a></li>
              <li><a href="login.html">Login</a></li>
              <li><a href="register.html">Register</a></li>
              <li><a href="forgot-password.html">Forgot Password</a></li>
            </ul>
          </li>
          <li class="has-submenu">
            <a href="">Blog <i class="fas fa-chevron-circle-down" /></a>
            <ul class="submenu">
              <li><a href="blog-list.html">Blog List</a></li>
              <li><a href="blog-grid.html">Blog Grid</a></li>
              <li><a href="blog-details.html">Blog Details</a></li>
            </ul>
          </li>
          <li>
            <a href="admin/index.html" target="_blank">Admin</a>
          </li>
          <li>
            <a href="login.html">Login</a>
          </li>
          <li class="login-link">
            <a href="login.html">Login </a>
          </li>
          <li class="login-link">
            <a href="register.html">Register </a>
          </li>
        </ul>
      </div>
      <ul class="nav header-navbar-rht">
        <li class="nav-item">
          <a class="nav-link btn-login btn-primary" href="login.html"
            ><i class="fas fa-sign-in-alt" /> Sign up</a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link btn-login btn-secondary" href="register.html"
            ><i class="fas fa-lock" /> Sign in</a
          >
        </li>
      </ul>
    </nav>
  </header>

  <section class="section section-search">
    <div class="container">
      <div class="banner-wrapper m-auto text-center">
        <div class="banner-header">
          <h1>Search Teacher in <span>Mentoring</span> Appointment</h1>
          <p>
            Discover the best Mentors & institutions the city nearest to you.
          </p>
        </div>

        <div class="search-box">
          <form action="search.html">
            <div class="form-search">
              <div class="form-inner">
                <div class="form-group search-location">
                  <i class="material-icons">my_location</i>
                  <select class="form-control select">
                    <option>Location</option>
                    <option>Japan</option>
                    <option>France</option>
                  </select>
                </div>
                <div class="form-group search-info">
                  <i class="material-icons">location_city</i>
                  <input
                    type="text"
                    class="form-control"
                    placeholder="Search School, Online educational centers, etc"
                  />
                </div>
                <button type="submit" class="btn btn-secondary search-btn mt-0"
                  >Search <i class="fas fa-long-arrow-alt-right" /></button
                >
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <section class="section how-it-works">
    <div class="container">
      <div class="section-header text-center">
        <span>Mentoring Flow</span>
        <h2>How does it works ?</h2>
        <p class="sub-title">
          Are you looking to join online institutions? Now it's very simple,
          Sign up with mentoring
        </p>
        <div class="sec-dots">
          <span />
          <span />
          <span />
        </div>
      </div>
      <div class="row justify-content-center feature-list">
        <div class="col-12 col-md-4 col-lg-3">
          <div class="feature-box text-center top-box">
            <div class="feature-header">
              <div class="feature-icon">
                <span class="circle bg-green"
                  ><i class="fas fa-sign-in-alt" /></span
                >
              </div>
              <div class="feature-cont">
                <div class="feature-text">Sign up</div>
              </div>
            </div>
            <p>
              Are you looking to join online Learning? Now it's very simple, Now
              Sign up
            </p>
            <span class="text-green">01</span>
          </div>
        </div>
        <div class="col-12 col-md-4 col-lg-3 offset-lg-1">
          <div class="feature-box text-center">
            <div class="feature-header">
              <div class="feature-icon">
                <span class="circle bg-blue"
                  ><i class="material-icons">accessibility</i></span
                >
              </div>
              <div class="feature-cont">
                <div class="feature-text">Collaborate</div>
              </div>
            </div>
            <p>
              Collaborate on your own timing, by scheduling with mentor booking
            </p>
            <span class="text-blue">02</span>
          </div>
        </div>
        <div class="col-12 col-md-4 col-lg-3 offset-lg-1">
          <div class="feature-box text-center top-box">
            <div class="feature-header">
              <div class="feature-icon">
                <span class="circle bg-orange"
                  ><i class="material-icons">event_seat</i></span
                >
              </div>
              <div class="feature-cont">
                <div class="feature-text">Improve & Get Back</div>
              </div>
            </div>
            <p>
              you can gather different skill set, and you can become mentor too
            </p>
            <span class="text-orange">03</span>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="section path-section">
    <div class="section-header text-center">
      <div class="container">
        <span>Choose the</span>
        <h2>Different All Learning Paths</h2>
        <p class="sub-title">
          Are you looking to join online institutions? Now it's very simple,
          Sign up with mentoring
        </p>
        <div class="sec-dots">
          <span />
          <span />
          <span />
        </div>
      </div>
    </div>
    <div class="course-sec">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-01.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-02.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-03.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-04.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-05.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-06.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-07.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-3">
            <div class="course-item">
              <a href="search.html" class="course-img">
                <div class="image-col-merge">
                  <img src="assets/img/course/course-08.jpg" alt="learn" />
                  <div class="course-text">
                    <h5>Digital Marketer</h5>
                    <div class="d-flex justify-content-between">
                      <p>400 Mentors</p>
                      <p>10 Courses</p>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>
        </div>
        <div class="view-all text-center">
          <a href="search.html" class="btn btn-primary btn-view">View All</a>
        </div>
      </div>
    </div>
  </section>

  <section class="section profile-section">
    <div class="section-header text-center">
      <div class="container">
        <span>MOST VIEWED</span>
        <h2>Featured Profile of this week</h2>
        <p class="sub-title">
          Are you looking to join online institutions? Now it's very simple,
          Sign up with mentoring
        </p>
        <div class="sec-dots">
          <span />
          <span />
          <span />
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6 col-lg-3">
          <div class="profile-list">
            <div class="profile-detail">
              <div class="profile-img">
                <img
                  class="img-fluid"
                  alt=""
                  src="assets/img/mendor/mendor-01.jpg"
                />
              </div>
              <div class="profile-content">
                <h4>Donna Yancey</h4>
                <p>UNIX, Calculus, Trigonometry</p>
              </div>
            </div>
            <div class="profile-rating">
              <div class="rating">
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star" />
              </div>
              <div class="price-box">$500 <span>/ hr</span></div>
            </div>
          </div>
        </div>

        <div class="col-12 col-md-6 col-lg-3">
          <div class="profile-list">
            <div class="profile-detail">
              <div class="profile-img">
                <img
                  class="img-fluid"
                  alt=""
                  src="assets/img/mendor/mendor-01.jpg"
                />
              </div>
              <div class="profile-content">
                <h4>Donna Yancey</h4>
                <p>UNIX, Calculus, Trigonometry</p>
              </div>
            </div>
            <div class="profile-rating">
              <div class="rating">
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star" />
              </div>
              <div class="price-box">$500 <span>/ hr</span></div>
            </div>
          </div>
        </div>

        <div class="col-12 col-md-6 col-lg-3">
          <div class="profile-list">
            <div class="profile-detail">
              <div class="profile-img">
                <img
                  class="img-fluid"
                  alt=""
                  src="assets/img/mendor/mendor-01.jpg"
                />
              </div>
              <div class="profile-content">
                <h4>Donna Yancey</h4>
                <p>UNIX, Calculus, Trigonometry</p>
              </div>
            </div>
            <div class="profile-rating">
              <div class="rating">
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star" />
              </div>
              <div class="price-box">$500 <span>/ hr</span></div>
            </div>
          </div>
        </div>

        <div class="col-12 col-md-6 col-lg-3">
          <div class="profile-list">
            <div class="profile-detail">
              <div class="profile-img">
                <img
                  class="img-fluid"
                  alt=""
                  src="assets/img/mendor/mendor-01.jpg"
                />
              </div>
              <div class="profile-content">
                <h4>Donna Yancey</h4>
                <p>UNIX, Calculus, Trigonometry</p>
              </div>
            </div>
            <div class="profile-rating">
              <div class="rating">
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star filled" />
                <i class="fas fa-star" />
              </div>
              <div class="price-box">$500 <span>/ hr</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section statistics-section">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-4">
          <div class="statistics-list">
            <div class="statistics-icon">
              <i class="fas fa-street-view" />
            </div>
            <div class="statistics-content">
              <span>500+</span>
              <h3>Happy Clients</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="statistics-list">
            <div class="statistics-icon">
              <i class="fas fa-history" />
            </div>
            <div class="statistics-content">
              <span>120+</span>
              <h3>Online Appointments</h3>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="statistics-list">
            <div class="statistics-icon">
              <i class="fas fa-user-check" />
            </div>
            <div class="statistics-content">
              <span>100%</span>
              <h3>Job Satisfaction</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section section-blogs">
    <div class="container">
      <div class="section-header text-center">
        <span>LATEST</span>
        <h2>Blogs & News</h2>
        <p class="sub-title">
          Are you looking to join online institutions? Now it's very simple,
          Sign up with mentoring
        </p>
        <div class="sec-dots">
          <span />
          <span />
          <span />
        </div>
      </div>

      <div class="row blog-grid-row">
        <div class="col-md-6 col-lg-4 col-sm-12">
          <div class="blog grid-blog">
            <div class="blog-image">
              <a href="blog-details.html"
                ><img
                  class="img-fluid"
                  src="assets/img/blog/blog-01.jpg"
                  alt="Post Image"
                /></a
              >
            </div>
            <div class="blog-content">
              <div class="blog-month">04 <span>Dec</span></div>
              <ul class="entry-meta meta-item">
                <li>
                  <div class="post-author">
                    <a href="blog-details.html"><span>Tyrone Roberts</span></a>
                  </div>
                </li>
              </ul>
              <h3 class="blog-title">
                <a href="blog-details.html"
                  >What is Lorem Ipsum? Lorem Ipsum is simply</a
                >
              </h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur em adipiscing elit, sed
                do eiusmod tempor.
              </p>
              <a href="blog-details.html" class="read">Read more</a>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-sm-12">
          <div class="blog grid-blog">
            <div class="blog-image">
              <a href="blog-details.html"
                ><img
                  class="img-fluid"
                  src="assets/img/blog/blog-01.jpg"
                  alt="Post Image"
                /></a
              >
            </div>
            <div class="blog-content">
              <div class="blog-month">04 <span>Dec</span></div>
              <ul class="entry-meta meta-item">
                <li>
                  <div class="post-author">
                    <a href="blog-details.html"><span>Tyrone Roberts</span></a>
                  </div>
                </li>
              </ul>
              <h3 class="blog-title">
                <a href="blog-details.html"
                  >What is Lorem Ipsum? Lorem Ipsum is simply</a
                >
              </h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur em adipiscing elit, sed
                do eiusmod tempor.
              </p>
              <a href="blog-details.html" class="read">Read more</a>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-sm-12">
          <div class="blog grid-blog">
            <div class="blog-image">
              <a href="blog-details.html"
                ><img
                  class="img-fluid"
                  src="assets/img/blog/blog-01.jpg"
                  alt="Post Image"
                /></a
              >
            </div>
            <div class="blog-content">
              <div class="blog-month">04 <span>Dec</span></div>
              <ul class="entry-meta meta-item">
                <li>
                  <div class="post-author">
                    <a href="blog-details.html"><span>Tyrone Roberts</span></a>
                  </div>
                </li>
              </ul>
              <h3 class="blog-title">
                <a href="blog-details.html"
                  >What is Lorem Ipsum? Lorem Ipsum is simply</a
                >
              </h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur em adipiscing elit, sed
                do eiusmod tempor.
              </p>
              <a href="blog-details.html" class="read">Read more</a>
            </div>
          </div>
        </div>
      </div>
      <div class="view-all text-center">
        <a href="blog-list.html" class="btn btn-primary btn-view">View All</a>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="footer-top">
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-3 col-md-6">
            <div class="footer-widget footer-about">
              <div class="footer-logo">
                <img src="assets/img/logo-white.png" alt="logo" />
              </div>
              <div class="footer-about-content">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="footer-widget footer-menu">
              <h2 class="footer-title">For Mentee</h2>
              <ul>
                <li><a href="search.html">Search Mentors</a></li>
                <li><a href="login.html">Login</a></li>
                <li><a href="register.html">Register</a></li>
                <li><a href="booking.html">Booking</a></li>
                <li><a href="dashboard-mentee.html">Mentee Dashboard</a></li>
              </ul>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="footer-widget footer-menu">
              <h2 class="footer-title">For Mentors</h2>
              <ul>
                <li><a href="appointments.html">Appointments</a></li>
                <li><a href="chat.html">Chat</a></li>
                <li><a href="login.html">Login</a></li>
                <li><a href="register.html">Register</a></li>
                <li><a href="dashboard.html">Mentor Dashboard</a></li>
              </ul>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="footer-widget footer-contact">
              <h2 class="footer-title">Contact Us</h2>
              <div class="footer-contact-info">
                <div class="footer-address">
                  <p>
                    3556 Beech Street, San Francisco,<br /> California, CA 94108
                  </p>
                </div>
                <p>+1 315 369 5943</p>
                <p class="mb-0">
                  <a
                    href="/cdn-cgi/l/email-protection"
                    class="__cf_email__"
                    data-cfemail="5f323a312b302d3631381f3a273e322f333a713c3032"
                    >[email&#160;protected]</a
                  >
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="container-fluid">
        <div class="copyright">
          <div class="row">
            <div class="col-md-6">
              <div class="copyright-text">
                <p class="mb-0">&copy; 2020 Mentoring. All rights reserved.</p>
              </div>
            </div>
            <div class="col-md-6">
              <div class="social-icon text-md-right">
                <ul>
                  <li>
                    <a href="#" target="_blank"
                      ><i class="fab fa-instagram" /></a
                    >
                  </li>
                  <li>
                    <a href="#" target="_blank"
                      ><i class="fab fa-linkedin-in" /></a
                    >
                  </li>
                  <li>
                    <a href="#" target="_blank"
                      ><i class="fab fa-twitter" />
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</div>
