
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title><LGU ISULAN Website></title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="index.js">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
<link rel="stylesheet" href="index.css">


<style>

:root{
    --green:#083961;
    --yellow:#2fda19;
    --darkgreen:#10ce4c;
}

body{
    font-family: Arial, sans-serif;
}

/* TOP BAR */
.top-bar{
    background:var(--green);
    color:#ffffff;
    font-size:12px;
    padding:2px 0;
}

.top-bar a{
    color:#fff;
    text-decoration:none;
    margin-right:20px;
}

.top-bar i{
    color:#ffc107;
}

/* HEADER */
.main-header{
    background:#fbfffd;
    padding:2 px 4;
}

.logo{
    width:75px;
}

.lgu-name{
    color:#008d3b;
    font-weight:700;
    font-size:22px;
}

.subtitle{
    color:#666;
    font-size:12px;
    letter-spacing:1px;
}

/* SEARCH */
.search-box{
    max-width:400px;
}

.search-box .form-control{
    border-radius:30px 0 0 30px;
}

.search-box .btn{
    border-radius:0 30px 30px 0;
    background:var(--green);
    color:#fff;
}

/* NAVIGATION */
.navbar-custom{
    background:var(--green);
     min-height:50px;
}

.navbar-custom .nav-link{
    color:rgb(255, 255, 255) !important;
    font-weight:60;
    padding:2px 15px !important;
}

.navbar-custom .nav-link:hover{
    background:#007d2a;
}

.active-link{
    background:#ff7300;
    color:#000 !important;
}

/* HERO */
.hero{
    position:relative;
    min-height:70px;
    background:
    linear-gradient(rgba(255,255,255,.85),
    rgba(83, 81, 226, 0.85)),
    url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1');
    background-size:cover;
    background-position:center;
    overflow:hidden;
}

.hero-content{
    padding-top:3px;
}

.hero-logo{
    width:1000px;
}

.iso-logo{
    width:260px;
}

.main-title{
    font-size:85px;
    font-weight:800;
    color:#003a8c;
    text-transform:uppercase;
    line-height:1;
}

.sub-title{
    font-size:50px;
    color:#003a8c;
    letter-spacing:10px;
    font-weight:700;
}

.iso-box{
    display:inline-block;
    background:#003a8c;
    color:white;
    padding:15px 40px;
    font-size:60px;
    font-weight:800;
    border-radius:6px;
}




/* BOTTOM FEATURE */
.features{
    background:#012f7c;
    color:white;
    padding:5px 0;
}

.feature-box{
    display:flex;
    align-items:center;
    gap:15px;
}

.feature-box i{
    font-size:25px;
    color:#fff;
}

.feature-title{
    color:#ffd500;
    font-weight:700;
    font-size:24px;
}

.feature-text{
    font-size:18px;
}

@media(max-width:991px){

.main-title{
    font-size:50px;
}

.sub-title{
    font-size:8px;
}


.hero-logo,
.iso-logo{
    width:180px;
}
}

</style>
</head>
<body>

<!-- TOP BAR -->
<div class="top-bar">
<div class="container">
<div class="row">
<div class="col-md-8">
<a href="tel:+63645620679">
    <i class="fas fa-phone"></i> (064) 562 0679
</a>
<a href="mailto:mpdco.isk@gmail.com">
    <i class="fas fa-envelope"></i> mayorsofficeisulan@gmail.com
</a>
<a href="https://www.facebook.com/mpdoisulan.sultankudarat"
   target="_blank"
   rel="noopener noreferrer">
    <i class="fab fa-facebook-f"></i> Municipality of Bagong Isulan 
</a>
</div>

<div class="col-md-4 text-end">
<a href="https://www.facebook.com/mpdoisulan.sultankudarat"
   target="_blank"
   rel="noopener noreferrer">
    <i class="fab fa-facebook-f"></i>
</a>
<a href="#"><i class="fab fa-twitter"></i></a>
<a href="#"><i class="fab fa-youtube"></i></a>
</div>
</div>
</div>
</div>

<!-- HEADER -->
<div class="lgu-header">

    <div class="container">

        <div class="row align-items-center header-row">

            <!-- LOGO & TITLE -->
            <div class="col-lg-7">

                <div class="d-flex align-items-center">

                    <img src="OFFICES LOGO/Coat_of_arms_of_the_Philippines.svg.webp"
                         class="logo logo-slide-in me-4">

                    <img src="OFFICES LOGO/SK LOGO1.png"
                         class="logo logo-slide-in me-4">

                    <img src="isulan_logo-removebg-preview.png"
                         class="logo logo-slide-in me-4">

                    <div>

                        <div class="province-name">
                            REPUBLIC OF THE PHILIPPINES
                        </div>

                        <div class="lgu-title">
                            PROVINCE OF SULTAN KUDARAT
                        </div>

                        <h1 class="office-name mb-1"
                            style="
                                font-family:'Times New Roman', Times, serif;
                                color: white;
                                font-size: 25px;
                            ">
                            LOCAL GOVERNMENT UNIT OF ISULAN
                        </h1>

                        <div class="subtitle">
                            National Highway Municipal Compound,
                            Isulan, Sultan Kudarat, Philippines
                        </div>

                    </div>

                </div>

            </div>


            <!-- SEARCH + TIME -->
            <div class="col-lg-5">

                <div class="d-flex align-items-center justify-content-end gap-3">

                    <form class="search-box d-flex">

                        <input type="text"
                               class="form-control"
                               placeholder="Search...">

                        <button class="btn px-4" type="submit">
                            <i class="fas fa-search"></i>
                        </button>

                    </form>

                    <!-- PST -->
<div class="pst-box">
    <small>Philippine Standard Time</small>
    <div id="pst-clock">Loading...</div>
</div>

                </div>

            </div>

        </div>

    </div>

    <script>
function updatePST() {

    const clock = document.getElementById("pst-clock");

    if (!clock) return;

    const now = new Date();

    const time = now.toLocaleTimeString("en-PH", {
        timeZone: "Asia/Manila",
        hour: "2-digit",
        minute: "2-digit",
        second: "2-digit",
        hour12: true
    });

    clock.textContent = time;
}

updatePST();

setInterval(updatePST, 1000);
</script>
</div>

<!-- =========================================
     LGU NAVIGATION BAR
========================================= -->

<nav class="navbar navbar-expand-lg lgu-navbar">

    <div class="container">

        <!-- MOBILE TOGGLE -->
        <button class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#lguMenu"
                aria-controls="lguMenu"
                aria-expanded="false"
                aria-label="Toggle navigation">

            <span class="navbar-toggler-icon"></span>

        </button>


        <!-- NAVIGATION -->
        <div class="collapse navbar-collapse" id="lguMenu">

            <ul class="navbar-nav mx-auto">


                <!-- HOME -->
                <li class="nav-item">

                    <a class="nav-link active" href="#">
                        <i class="fas fa-home"></i>
                        Home
                    </a>

                </li>


                <!-- ABOUT US -->
                <li class="nav-item dropdown">

                    <a class="nav-link dropdown-toggle"
                       href="#"
                       data-bs-toggle="dropdown">

                        <i class="fas fa-landmark"></i>
                        About Us

                    </a>

                    <ul class="dropdown-menu">

                        <li>
                            <a class="dropdown-item" href="#">
                                Municipal Profile
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                History
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Vision, Mission & Goals
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Organizational Structure
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Officials & Personnel
                            </a>
                        </li>

                    </ul>

                </li>


                <!-- GOVERNMENT -->
<li class="nav-item dropdown">

    <a class="nav-link dropdown-toggle"
       href="#"
       data-bs-toggle="dropdown">

        <i class="fas fa-building-columns"></i>
        Government

    </a>

    <ul class="dropdown-menu">

        <li>
            <a class="dropdown-item" href="#">
                Office of the Mayor
            </a>
        </li>

        <li>
            <a class="dropdown-item" href="#">
                Office of the Vice Mayor
            </a>
        </li>

        <li>
            <a class="dropdown-item" href="#">
                Sangguniang Bayan
            </a>
        </li>


        <!-- MUNICIPAL DEPARTMENTS SUBMENU -->
        <li class="dropdown-submenu">

            <a class="dropdown-item dropdown-toggle"
               href="#">
                <i class="fas fa-building"></i>
                Municipal Departments
            </a>

            <ul class="dropdown-menu">

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Planning & Development Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Engineering Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Assessor's Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Treasurer's Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Budget Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Health Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Agriculture Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Public Employment Services Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Municipal Information Office
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Office of the Legal Officer
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        Office of the Administrator
                    </a>
                </li>

                <li>
                    <a class="dropdown-item" href="#">
                        MDRRM Office
                    </a>
                </li>

            </ul>

        </li>


        <li>
            <a class="dropdown-item" href="#">
                Barangays
            </a>
        </li>

    </ul>

</li>


                <!-- SERVICES -->
                <li class="nav-item dropdown">

                    <a class="nav-link dropdown-toggle"
                       href="#"
                       data-bs-toggle="dropdown">

                        <i class="fas fa-hand-holding-heart"></i>
                        Services

                    </a>

                    <ul class="dropdown-menu">

                        <li>
                            <a class="dropdown-item" href="#">
                                Business Permits
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Civil Registry
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Health Services
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Social Welfare Services
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Planning & Development Services
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Engineering Services
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Agricultural Services
                            </a>
                        </li>

                    </ul>

                </li>


                <!-- PROGRAMS & PROJECTS -->
                <li class="nav-item dropdown">

                    <a class="nav-link dropdown-toggle"
                       href="#"
                       data-bs-toggle="dropdown">

                        <i class="fas fa-diagram-project"></i>
                        Programs & Projects

                    </a>

                    <ul class="dropdown-menu">

                        <li>
                            <a class="dropdown-item" href="#">
                                Development Programs
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Infrastructure Projects
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Social Development
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Economic Development
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Environmental Programs
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Completed Projects
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Ongoing Projects
                            </a>
                        </li>

                    </ul>

                </li>


                <!-- TRANSPARENCY -->
                <li class="nav-item dropdown">

                    <a class="nav-link dropdown-toggle"
                       href="#"
                       data-bs-toggle="dropdown">

                        <i class="fas fa-file-shield"></i>
                        Transparency

                    </a>

                    <ul class="dropdown-menu">

                        <li>
                            <a class="dropdown-item" href="#">
                                Full Disclosure Policy
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Budget & Financial Reports
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Procurement
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Annual Investment Program
                            </a>
                        </li>

                        <li>
                            <a class="dropdown-item" href="#">
                                Annual Accomplishment Reports
                            </a>
                        </li>

                    </ul>

                </li>


                <!-- DOWNLOADS -->
                <li class="nav-item">

                    <a class="nav-link" href="#">

                        <i class="fas fa-download"></i>
                        Downloads

                    </a>

                </li>


                <!-- CONTACT -->
                <li class="nav-item">

                    <a class="nav-link" href="#">

                        <i class="fas fa-phone"></i>
                        Contact Us

                    </a>

                </li>

            </ul>

        </div>

    </div>

</nav> 

<!---- slideshow carousel-->
<!-- =========================================
     HERO SLIDESHOW
========================================= -->

<div id="heroCarousel"
     class="carousel slide"
     data-bs-ride="carousel"
     data-bs-interval="5000">

    <!-- SLIDES -->
    <div class="carousel-inner">

        <!-- Slide 1 -->
        <div class="carousel-item active">
            <img src="Features/ISULAN, THE GLIMPSE.png"
                 class="hero-image d-block w-100"
                 alt="Slide 1">
        </div>

        <!-- Slide 2 -->
        <div class="carousel-item">
            <img src="slideshow2.jpg.png"
                 class="hero-image d-block w-100"
                 alt="Slide 2">
        </div>

        <!-- Slide 3 -->
        <div class="carousel-item">
            <img src="slideshow3.jpg.png"
                 class="hero-image d-block w-100"
                 alt="Slide 3">
        </div>

        <!-- Slide 4 -->
        <div class="carousel-item">
            <img src="slideshow4.png"
                 class="hero-image d-block w-100"
                 alt="Slide 4">
        </div>

        <!-- Slide 5 -->
        <div class="carousel-item">
            <img src="SLIDESHOW5.png"
                 class="hero-image d-block w-100"
                 alt="Slide 5">
        </div>

        <!-- Slide 6 -->
        <div class="carousel-item">
            <img src="SLIDESHOW6.png"
                 class="hero-image d-block w-100"
                 alt="Slide 6">
        </div>

        <!-- Slide 7 -->
        <div class="carousel-item">
            <img src="SLIDESHOW7.png"
                 class="hero-image d-block w-100"
                 alt="Slide 7">
        </div>

        <!-- Slide 8 -->
        <div class="carousel-item">
            <img src="SLIDESHOW8.png"
                 class="hero-image d-block w-100"
                 alt="Slide 8">
        </div>

        <!-- Slide 9 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/slideshow maam den.png"
                 class="hero-image d-block w-100"
                 alt="Ma'am Den">
        </div>

        <!-- Slide 10 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/MBNM.jpg"
                 class="hero-image d-block w-100"
                 alt="Barangayan CLUP">
        </div>

        <!-- Slide 11 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/LLPDCPI.png"
                 class="hero-image d-block w-100"
                 alt="Barangayan CLUP 2">
        </div>

        <!-- Slide 12 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/mayor bai.png"
                 class="hero-image d-block w-100"
                 alt="Mayor">
        </div>

        <!-- Slide 13 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/cap dev 2024.png"
                 class="hero-image d-block w-100"
                 alt="CapDev">
        </div>

        <!-- Slide 14 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/slideshow clup barangayan.png"
                 class="hero-image d-block w-100"
                 alt="CLUP">
        </div>

        <!-- Slide 15 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/isulan glowing logo.png"
                 class="hero-image d-block w-100"
                 alt="Isulan Logo">
        </div>

        <!-- Slide 16 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/MPDO ORG CHART.png"
                 class="hero-image d-block w-100"
                 alt="Organizational Chart">
        </div>

        <!-- Slide 17 -->
        <div class="carousel-item">
            <img src="SLIDESHOW/LLPDCPI.png"
                 class="hero-image d-block w-100"
                 alt="LLPDCPI">
        </div>

    </div>


    <!-- =================================
         LEFT ARROW
    ================================== -->

    <button class="carousel-control-prev"
            type="button"
            data-bs-target="#heroCarousel"
            data-bs-slide="prev">

        <span class="hero-nav">
            <i class="fas fa-chevron-left"></i>
        </span>

        <span class="visually-hidden">
            Previous
        </span>

    </button>


    <!-- =================================
         RIGHT ARROW
    ================================== -->

    <button class="carousel-control-next"
            type="button"
            data-bs-target="#heroCarousel"
            data-bs-slide="next">

        <span class="hero-nav">
            <i class="fas fa-chevron-right"></i>
        </span>

        <span class="visually-hidden">
            Next
        </span>

    </button>


    <!-- =================================
         INDICATORS
    ================================== -->

    <div class="carousel-indicators">

        <button type="button"
                data-bs-target="#heroCarousel"
                data-bs-slide-to="0"
                class="active"
                aria-current="true"></button>

        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="1"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="2"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="3"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="4"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="5"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="6"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="7"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="8"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="9"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="10"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="11"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="12"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="13"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="14"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="15"></button>
        <button type="button" data-bs-target="#heroCarousel" data-bs-slide-to="16"></button>

    </div>

</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>


<!----- end slideshow carousel -->

<!-- FLASHING BLUE ANNOUNCEMENT BAR -->
<section class="announcement-bar">
    <div class="container">
        <div class="announcement-content">
            <i class=""></i>
            ///////////////////////////////////////////
        </div>
    </div>
</section>


</section> <!-- HERO -->

<!-- Gray line -->
<div class="gray-divider"></div>

<section class="quick-links py-5">

<!-- Floating Feedback Button -->
<a href="feedback.html" class="feedback-btn" title="Feedback Form">
    <i class="fas fa-comment-dots"></i>
    <span>Feedback Form</span>
</a>
<div class="row g-4">

<!-- =========================================
     MAIN CONTENT
========================================= -->

<div class="row g-4 align-items-start">

    <!-- =====================================
         LEFT 8 COLUMNS
         DEPARTMENTS + MAYOR SECTIONS
    ====================================== -->

    <div class="col-lg-8">

        <div class="department-layout">

            <!-- =================================
                 MUNICIPAL DEPARTMENTS
            ================================== -->

            <div class="departments-area">

                <div class="department-header">

                    <button class="department-btn"
                            type="button"
                            data-bs-toggle="collapse"
                            data-bs-target="#departmentList"
                            aria-expanded="false"
                            aria-controls="departmentList">

                        <i class="fas fa-building"></i>

                        MUNICIPAL DEPARTMENTS

                        <i class="fas fa-chevron-down department-arrow"></i>

                    </button>

                    <a href="#" class="view-all">
                        View All
                        <i class="fas fa-arrow-right"></i>
                    </a>

                </div>


                


                <!-- =================================
                     OFFICE WHEEL
                ================================== -->

                <div class="office-wheel">

                    <!-- CENTER MAYOR -->

                    <a href="#" class="mayor-center">

                        <div class="mayor-logo">
                            <img src="OFFICES LOGO/isulan_logo-removebg-preview.png"
                                 alt="Office of the Mayor">
                        </div>

                        <div class="mayor-name">
                            Office of the Mayor
                        </div>

                        <div class="mayor-description">
                            Municipal Mayor
                        </div>

                    </a>


                    <!-- 1 -->

                    <a href="#" class="wheel-office office-1">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/SB OFFICE.png">
                        </div>
                        <div class="wheel-name">
                            Office of the Vice Mayor
                        </div>
                    </a>


                    <!-- 2 -->

                    <a href="#" class="wheel-office office-2">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/isulan_logo-removebg-preview.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Administrator Office
                        </div>
                    </a>


                    <!-- 3 -->

                    <a href="#" class="wheel-office office-3">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/MEO.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Engineering Office
                        </div>
                    </a>


                    <!-- 4 -->

                    <a href="#" class="wheel-office office-4">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/assessor.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Assessor's Office
                        </div>
                    </a>


                    <!-- 5 -->

                    <a href="#" class="wheel-office office-5">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/treasurers office.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Treasurer's Office
                        </div>
                    </a>


                    <!-- 6 -->

                    <a href="#" class="wheel-office office-6">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/isulan_logo-removebg-preview.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Budget Office
                        </div>
                    </a>


                    <!-- 7 -->

                    <a href="#" class="wheel-office office-7">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/MHO ISULAN.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Health Office
                        </div>
                    </a>


                    <!-- 8 -->

                    <a href="#" class="wheel-office office-8">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/omag isulan.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Agriculture Office
                        </div>
                    </a>


                    <!-- 9 -->

                    <a href="#" class="wheel-office office-9">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/PESO ISULAN.png">
                        </div>
                        <div class="wheel-name">
                            Public Employment Services Office
                        </div>
                    </a>


                    <!-- 10 -->

                    <a href="#" class="wheel-office office-10">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/MIO.png">
                        </div>
                        <div class="wheel-name">
                            Municipal Information Office
                        </div>
                    </a>


                    <!-- 11 -->

                    <a href="#" class="wheel-office office-11">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/MDRRMO.jpg">
                        </div>
                        <div class="wheel-name">
                            MDRRMO
                        </div>
                    </a>


                    <!-- 12 -->

                    <a href="#" class="wheel-office office-12">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/Mpdo Logo.jpg">
                        </div>
                        <div class="wheel-name">
                            Municipal Planning & Development Office
                        </div>
                    </a>


                    <!-- 13 -->

                    <a href="#" class="wheel-office office-13">
                        <div class="wheel-logo">
                            <img src="OFFICES LOGO/isulan_logo-removebg-preview.png">
                        </div>
                        <div class="wheel-name">
                            Legal Office
                        </div>
                    </a>

                </div>

            </div>


            <!-- =================================
                 SECTIONS UNDER MAYOR
            ================================== -->

            <div class="mayor-sections-area">

                <div class="section-header">

                    <h2>
                        <i class="fas fa-layer-group"></i>
                        SECTIONS UNDER MAYOR'S OFFICE
                    </h2>

                </div>


                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-umbrella-beach"></i>
                    </div>

                    <div class="section-info">
                        <h4>MTO</h4>
                        <span>Municipal Tourism Office</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>


                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-leaf"></i>
                    </div>

                    <div class="section-info">
                        <h4>MENRO</h4>
                        <span>Municipal Environment and Natural Resources</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>


                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-users"></i>
                    </div>

                    <div class="section-info">
                        <h4>LYDO</h4>
                        <span>Local Youth Development Office</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>


                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-store"></i>
                    </div>

                    <div class="section-info">
                        <h4>MARKET</h4>
                        <span>Municipal Public Market</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>


                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-tractor"></i>
                    </div>

                    <div class="section-info">
                        <h4>OMABE</h4>
                        <span>Office of the Municipal Agricultural and Biosystems Engineer</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>


                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-boxes"></i>
                    </div>

                    <div class="section-info">
                        <h4>GSO</h4>
                        <span>General Services Office</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>
                <a href="#" class="mayor-section-card">

                    <div class="section-icon">
                        <i class="fas fa-users-cog"></i>
                    </div>

                    <div class="section-info">
                        <h4>HRMO</h4>
                        <span>Human Resource Management Office</span>
                    </div>

                    <i class="fas fa-chevron-right"></i>

                </a>

            </div>

        </div>

    </div>


    <!-- =====================================
         RIGHTMOST : NEWS & FEATURES
    ====================================== -->

    <div class="col-lg-4 news-column">

        <div class="section-header">

            <h2>
                <i class="fas fa-newspaper"></i>
                NEWS & FEATURES
            </h2>

            <a href="#" class="view-all">
                View All
                <i class="fas fa-arrow-right"></i>
            </a>

        </div>


        <!-- FEATURED NEWS1 -->

        <div class="news-feature-card">

            <div class="news-feature-image">

                <a href="Features/new public market.jpg"
                   class="news-image-link"
                   target="_blank">

                    <img src="Features/new public market.jpg"
                         alt="Isulan Public Market Phase 1">

                    <span class="image-zoom-icon">
                        <i class="fas fa-expand"></i>
                    </span>

                </a>

                <span class="news-label">
                    FEATURED
                </span>

            </div>


            <div class="news-feature-content">

                <div class="news-date">
                    <i class="far fa-calendar-alt"></i>
                    August 09, 2026
                </div>

                <h3>
                    Isulan Public Market Phase 1 Construction
                </h3>

                <p>
                    Yes!!! We are now on the final stage of design
                    and preparation for the construction of Phase 1
                    of the new Isulan Public Market, which is set to
                    begin this August.
                </p>

                <a href="#" class="read-more">
                    Read More
                    <i class="fas fa-arrow-right"></i>
                </a>

            </div>

        </div>
<!-- FEATURED NEWS2 -->
        <div class="news-feature-card">

            <div class="news-feature-image">

                <a href="Features/esplanade.jpg"
                   class="news-image-link"
                   target="_blank">

                    <img src="Features/esplanade.jpg"
                         alt="Isulan Public Market Phase 1">

                    <span class="image-zoom-icon">
                        <i class="fas fa-expand"></i>
                    </span>

                </a>
<!-- Feature 2 -->
                <span class="news-label">
                    FEATURED
                </span>

            </div>


            <div class="news-feature-content">

            <div class="news-date">
         <i class="far fa-calendar-alt"></i>
            August 09, 2026
        </div>

         <h3>
        Bagong Isulan: Isulan Esplanade and Boardwalk
        </h3>

    <!-- SHORT VERSION -->
        <div class="news-summary">
        <p>
            Isa sa aming mga plano at plataporma ang pag-develop ng
            Isulan bilang isang tourist destination, kabilang ang
            pag-develop ng Allah River sa Barangay Kalawag III.
        </p>
        </div>

        <!-- FULL VERSION -->
        <div class="news-full" id="newsFull">

        <p>
            Isa sa aming mga plano at plataporma ang patuloy na
            pag-develop ng ating bayan bilang isang
            <strong>tourist destination</strong>—hindi lamang dahil
            sa ating Provincial Capitol, Sports Complex and Gymnasium,
            at Sultan Kudarat Provincial Hospital, kundi pati na rin
            sa pag-develop ng ating mga lokal na lugar.
        </p>

        <p>
            Isa sa mga nakikita nating may malaking potential ay ang
            <strong>Allah River sa Barangay Kalawag III</strong>.
        </p>

        <p>
            Plano ng <strong>Team Kapamilya</strong> na gawing isang
            magandang pasyalan ang lugar sa pamamagitan ng
            <strong>Isulan Esplanade / Isulan Boardwalk</strong>,
            na magkakaroon ng <strong>Senior Citizen Exercise Park</strong>
            at <strong>Food Park</strong>.
        </p>

        <p>
            Wala pong imposible sa pangarap na ito dahil kaya po natin
            itong matupad basta sama-sama po tayo tungo sa mas maganda,
            mas maunlad at mas progresibong Isulan.
        </p>

        </div>

     <!-- SEE MORE BUTTON -->
     <button type="button"
            class="read-more"
            id="seeMoreBtn"
            onclick="toggleNews()">

        See More
        <i class="fas fa-arrow-right"></i>

     </button>

    </div>

        </div>

        </a>
        

    </div>

</div>
 

<!-- Gray line -->
<!-- =========================================
     BLUE-VIOLET SEPARATOR NAV BAR
========================================= -->

<div class="office-nav-bar">

    <div class="office-nav-inner">

        <!-- PRIORITY PROGRAMS -->
        <div class="office-nav-item">
            <a href="#">
                Priority Programs
                <i class="fas fa-caret-down"></i>
            </a>

            <div class="office-dropdown">
                <a href="#">Priority Projects</a>
                <a href="#">Development Programs</a>
                <a href="#">Social Programs</a>
            </div>
        </div>


        <!-- NEWS & EVENTS -->
        <div class="office-nav-item">
            <a href="#">
                News &amp; Events
                <i class="fas fa-caret-down"></i>
            </a>

            <div class="office-dropdown">
                <a href="#">Latest News</a>
                <a href="#">Events</a>
                <a href="#">Announcements</a>
            </div>
        </div>


        <!-- E-LIBRARY -->
        <div class="office-nav-item">
            <a href="#">
                E-Library
                <i class="fas fa-caret-down"></i>
            </a>

            <div class="office-dropdown">
                <a href="#">Ordinances</a>
                <a href="#">Resolutions</a>
                <a href="#">Official Documents</a>
            </div>
        </div>


        <!-- CAREER OPPORTUNITIES -->
        <div class="office-nav-item">
            <a href="#">
                Career Opportunities
                <i class="fas fa-caret-down"></i>
            </a>

            <div class="office-dropdown">
                <a href="#">Job Vacancies</a>
                <a href="#">Government Jobs</a>
                <a href="#">Career Information</a>
            </div>
        </div>


        <!-- BID OPPORTUNITIES -->
        <div class="office-nav-item">
            <a href="#">
                Bid Opportunities
                <i class="fas fa-caret-down"></i>
            </a>

            <div class="office-dropdown">
                <a href="#">Bid Notices</a>
                <a href="#">Procurement</a>
                <a href="#">Bids &amp; Awards</a>
            </div>
        </div>

    </div>

</div>
<!-- Gray line -->

<!---- LCE Corner-->


    <!-- =================================================
         MAIN CONTENT
    ================================================== -->

    <div class="lgu-content-container">


        <!-- =================================================
             ONLINE SERVICES / STAT
        ================================================== -->

        <section class="online-services-section">

            <div class="section-title-line">

                <h3>
                    ONLINE SERVICES
                </h3>

            </div>


            <div class="online-services-grid">

                <!-- SERVICE 1 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-file-alt"></i>
                    </div>

                    <span>
                        Business<br>
                        Permit
                    </span>

                </a>


                <!-- SERVICE 2 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-building"></i>
                    </div>

                    <span>
                        Building<br>
                        Permit
                    </span>

                </a>


                <!-- SERVICE 3 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-coins"></i>
                    </div>

                    <span>
                        Real Property<br>
                        Tax
                    </span>

                </a>


                <!-- SERVICE 4 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-briefcase"></i>
                    </div>

                    <span>
                        PESO<br>
                        Services
                    </span>

                </a>

                <!-- SERVICE 5 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-file-signature"></i>
                    </div>

                    <span>
                        Document<br>
                        Requests
                    </span>

                </a>

                <!-- SERVICE 6 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-heartbeat"></i>
                    </div>

                    <span>
                        Health<br>
                        Services
                    </span>

                </a>

                <!-- SERVICE 7 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-seedling"></i>
                    </div>

                    <span>
                        Agriculture<br>
                        Services
                    </span>

                </a>

                <!-- SERVICE 8 -->
                <a href="#" class="online-service-card">

                    <div class="service-icon">
                        <i class="fas fa-landmark"></i>
                    </div>

                    <span>
                        Municipal<br>
                        Services
                    </span>

                </a>

            </div>

        </section>


        <!-- =================================================
             TWO COLUMN AREA
        ================================================== -->

        <div class="lgu-feature-grid">


            <!-- =================================================
                 LEFT : MAYOR'S CORNER
            ================================================== -->

            <!-- =================================
     MAYOR'S CORNER
================================== -->

<div class="mayor-corner">

    <!-- SECTION TITLE -->
    <div class="mayor-corner-title">
        <span>MAYOR'S CORNER</span>
    </div>


    <!-- MAYOR PHOTO -->
    <div class="mayor-profile">

        <div class="mayor-photo-box">

            <img src="Mayors corner/mayor bai 3.png"
                 alt="Municipal Mayor"
                 class="mayor-photo">

        </div>

        <!-- PROFILE / SPEECHES -->
        <div class="mayor-buttons">

            <a href="#" class="mayor-btn">
                PROFILE
            </a>

            <a href="#" class="mayor-btn">
                SPEECHES
            </a>

        </div>

    </div>


    <!-- =================================
         GOVERNMENT SEALS
    ================================== -->

    <!-- =================================
     MAYOR'S CORNER AWARDS
================================== -->

<div class="mayor-recognition-list">


    <!-- GAWAD KALASAG -->
    <a href="#" class="mayor-seal-card">

        <div class="mayor-seal-image">

            <img src="Mayors corner/National_Disaster_Risk_Reduction_and_Management_Council_(NDRRMC).svg.webp"
                 alt="Gawad KALASAG">

        </div>

        <div class="mayor-seal-text">

            <strong>GAWAD KALASAG</strong>

            <span>
                Disaster Risk Reduction and Management
            </span>

        </div>

    </a>


    <!-- SEAL OF GOOD LOCAL GOVERNANCE -->
    <a href="#" class="mayor-seal-card">

        <div class="mayor-seal-image">

            <img src="Mayors corner/dilg.webp"
                 alt="Seal of Good Local Governance">

        </div>

        <div class="mayor-seal-text">

            <strong>SEAL OF GOOD LOCAL GOVERNANCE</strong>

            <span>
                Department of the Interior and Local Government
            </span>

        </div>

    </a>


    <!-- RED ORCHID AWARD -->
    <a href="#" class="mayor-seal-card">

        <div class="mayor-seal-image">

            <img src="Mayors corner/doh.svg"
                 alt="Red Orchid Award">

        </div>

        <div class="mayor-seal-text">

            <strong>RED ORCHID AWARD</strong>

            <span>
                Department of Health
            </span>

        </div>

    </a>


</div>


<!-- =================================
     FEATURED VIDEO
================================== -->

<!-- =================================
     FEATURED VIDEO
================================== -->

<div class="mayor-video-section">

    <div class="mayor-video-title">
        FEATURED VIDEO
    </div>

    <div class="mayor-video">

        <video
            class="mayor-video-player"
            controls
            playsinline
            preload="metadata"
            poster="Features/mayor-video.jpg">

            <source src="Mayors corner/aerial view.mp4"
                    type="video/mp4">

            Your browser does not support HTML5 video.
        </video>

    </div>

</div>

    </div>



            <!-- =================================================
                 RIGHT : PRESS RELEASES
            ================================================== -->

            <section class="press-release-section">

                <div class="section-title-line">

                    <h3>
                        NEWS & FEATURES
                    </h3>

                    <a href="#" class="view-all">
                        View All
                        <i class="fas fa-arrow-right"></i>
                    </a>

                </div>


                <!-- ARTICLE 1 -->

                <article class="press-article">

                    <div class="press-article-content">

                        <span class="press-category">
                            FEATURED
                        </span>

                        <h4>
                            Bagong Isulan Daycare Center
                        </h4>

                        <small>
                            <i class="far fa-calendar-alt"></i>
                            August 09, 2026
                        </small>

                        <p>
                            Blessing and Turn-over Ceremony of Bagong Isulan Daycare Center sa Barangay New Pangasinan 
                        </p>

                        <a href="#">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>

                    </div>


                    <div class="press-image">

                        <img src="Mayors corner/new pang daycare.jpg"
                             alt="Isulan Public Market">

                    </div>

                </article>



                <!-- ARTICLE 2 -->

                <article class="press-article">

                    <div class="press-article-content">

                        <span class="press-category">
                            DEVELOPMENT
                        </span>

                        <h4>
                            Bagong Isulan:
                            Developing Our Town
                        </h4>

                        <small>
                            <i class="far fa-calendar-alt"></i>
                            August 08, 2026
                        </small>

                        <p>
                            Hamungaya Festival preparation 2026
                        </p>

                        <a href="#">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>

                    </div>


                    <div class="press-image">

                        <img src="Mayors corner/hamunagay preparation.jpg"
                             alt="Bagong Isulan">

                    </div>

                </article>



                <!-- ARTICLE 3 -->

                <article class="press-article">

                    <div class="press-article-content">

                        <span class="press-category">
                            LGU ISULAN
                        </span>

                        <h4>
                            Blessing and Turn-over Ceremony ng Tatlong One-Storey, Two Classrooms para sa Bambad Elementary School,
                        </h4>

                        <small>
                            <i class="far fa-calendar-alt"></i>
                            August 07, 2026
                        </small>

                        <p>
                            Blessing and Turn-over Ceremony ng Tatlong One-Storey, Two Classrooms para sa Bambad Elementary School, Isulan Central SPED at Tayugo Elementary School 💜 Ngayon taon naman ay magpapatayo ng bagong school building para sa New Pangasinan Elementary School, Kalawag III Elementary School, D’lotilla Elementary School at Laguilayan Central Elementary School
                        </p>

                        <a href="#">
                            Read More
                            <i class="fas fa-arrow-right"></i>
                        </a>

                    </div>


                    <div class="press-image">

                        <img src="Mayors corner/bamabad schoo.jpg"
                             alt="LGU Isulan Programs">

                    </div>

                </article>

            </section>

        </div>

    </div>

</section>

<!---- LCE Corner-->


<section class="mio-corner-section">

   
   <!-- =========================================
     MIO CORNER HEADER
========================================= -->

<div class="mio-corner-header">

    <!-- LEFT : HUGE MIO LOGO -->
    <div class="mio-logo-box">

        <img src="OFFICES LOGO/MIO.png"
             alt="Municipal Information Office"
             class="mio-huge-logo">

    </div>


    <!-- RIGHT : MIO INFORMATION -->
    <div class="mio-heading">

        <span class="section-label">
            MUNICIPAL INFORMATION OFFICE
        </span>

        <h2>
            Municipal Information Office Corner
        </h2>

        <p>
            Stay informed with the latest official news, updates,
            announcements, programs, projects, activities, and
            articles from the Municipality of Isulan.
        </p>

    </div>

</div>


    <!-- =================================
         MIO CONTENT
    ================================== -->

    <div class="mio-content">

        <!-- =================================
             LEFT : NEWS & ARTICLES
        ================================== -->

        <div class="mio-news-column">


            <!-- NEWS 1 -->

            <a href="#" class="mio-article">

                <div class="mio-article-image">

                    <img src="MIO corner/subaybayani.jpg"
                         alt="Isulan Public Market Phase 1">

                </div>

                <div class="mio-article-content">

                    <span class="mio-category">
                        NEWS
                    </span>

                    <h4>
                        DILG SUBAYBAYAN ASSESSMENT
                    </h4>

                    <small>
                        <i class="far fa-calendar-alt"></i>
                        July 28, 2026
                    </small>

                    <p>
                        Under the leadership of Mayor Princess Rihan M. Sakaluran, Vice Mayor Arnold H. Armada and 22nd Sangguniang Bayan of Isulan, the Local Government Unit of Isulan successfully conducted the SUBAYBAYAN Validation led by the DILG Region XII Project Development and Management Unit (PDMU) together with the Financial Analyst. The validation was held at the Office of the Municipal Mayor, Municipal Hall, Isulan.
                    </p>

                    <span class="mio-read-more">
                        Read More
                        <i class="fas fa-arrow-right"></i>
                    </span>

                </div>

            </a>


            <!-- NEWS 2 -->

            <a href="#" class="mio-article">

                <div class="mio-article-image">

                    <img src="MIO corner/revenue code.jpg"
                         alt="Bagong Isulan">

                </div>

                <div class="mio-article-content">

                    <span class="mio-category">
                        UPDATES
                    </span>

                    <h4>
                        REVENUE CODE REVIEW
                    </h4>

                    <small>
                        <i class="far fa-calendar-alt"></i>
                        July 29,2026
                    </small>

                    <p>
                       Nagsagawa ng committee meeting ang Pamahalaang Bayan ng Isulan kasama ang mga Department Heads at mga Elected Officials upang talakayin ang mga panukalang rebisyon sa Municipal Revenue Code. Layunin ng pagpupulong na matiyak na ang mga probisyon ng Revenue Code ay nananatiling angkop, makatarungan, at tumutugon sa kasalukuyang pangangailangan ng ating bayan. 
                    </p>

                    <span class="mio-read-more">
                        Read More
                        <i class="fas fa-arrow-right"></i>
                    </span>

                </div>

            </a>


            <!-- NEWS 3 -->

            <a href="#" class="mio-article">

                <div class="mio-article-image">

                    <img src="MIO corner/coordination meeting hamungaya.jpg"
                         alt="LGU Isulan Programs">

                </div>

                <div class="mio-article-content">

                    <span class="mio-category">
                        ARTICLES
                    </span>

                    <h4>
                        Latest Programs and Activities of LGU Isulan
                    </h4>

                    <small>
                        <i class="far fa-calendar-alt"></i>
                        August 07, 2026
                    </small>

                    <p>
                        Read the latest programs, projects,
                        activities, and accomplishments of the
                        Local Government Unit of Isulan.
                    </p>

                    <span class="mio-read-more">
                        Read More
                        <i class="fas fa-arrow-right"></i>
                    </span>

                </div>

            </a>


        </div>


        <!-- =================================
             RIGHT : LARGE MIO LOGO
        ================================== -->

        <div class="mio-logo-column">

            <div class="mio-logo-background">

                <img src="OFFICES LOGO/MIO.png"
                     alt="Municipal Information Office"
                     class="mio-huge-logo">

                <h3>
                    MUNICIPAL INFORMATION OFFICE
                </h3>

                <p>
                    Official news, information, updates,
                    and public communications of the
                    Municipality of Isulan.
                </p>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     END SECTION MIO
========================== -->




<!-- =================================
     PESO CONTENT
================================== -->

<section class="mio-corner-section">

   
   <!-- =========================================
     MIO CORNER HEADER
========================================= -->

<div class="mio-corner-header">

    <!-- =================================
     PESO HEADER
================================== -->

<!-- LEFT : HUGE PESO LOGO -->

<div class="mio-logo-box">

    <img src="OFFICES LOGO/PESO ISULAN.png"
         alt="Public Employment Services Office"
         class="mio-huge-logo">

</div>


<!-- RIGHT : PESO INFORMATION -->

<div class="mio-heading">

    <span class="section-label">
        PUBLIC EMPLOYMENT SERVICES OFFICE
    </span>

    <h2>
        PESO Corner
    </h2>
 
    <p>
        Stay informed about employment opportunities, job fairs,
        livelihood programs, skills training, career assistance,
        and other employment services provided by the Municipality
        of Isulan.
    </p>

</div>

</div>


    <!-- =================================
     PESO CONTENT
================================== -->

<div class="mio-content">

    <!-- =================================
         LEFT : PESO NEWS & ARTICLES
    ================================== -->

    <div class="mio-news-column">


        <!-- =================================
             PESO NEWS 1
        ================================== -->

        <a href="#" class="mio-article">

            <div class="mio-article-image">

                <img src="MIO corner/veloz.png"
                     alt="PESO Job Opportunities">

            </div>

            <div class="mio-article-content">

                <span class="mio-category">
                    JOB OPPORTUNITIES
                </span>

                <h4>
                    📢 JOB ALERT! 📢

                </h4>

                <small>
                    <i class="far fa-calendar-alt"></i>
                    August 09, 2026
                </small>

                <p>
                    Velox Energy Philippines is currently hiring for the following positions:

                </p>

                <span class="mio-read-more">
                    Read More
                    <i class="fas fa-arrow-right"></i>
                </span>

            </div>

        </a>


        <!-- =================================
             PESO NEWS 2
        ================================== -->

        <a href="#" class="mio-article">

            <div class="mio-article-image">

                <img src="MIO corner/spes.jpg"
                     alt="PESO Employment Services">

            </div>

            <div class="mio-article-content">

                <span class="mio-category">
                    PESO UPDATES
                </span>

                <h4>
                    Special Program for the Employment of Students (SPES) Orientation
                </h4>

                <small>
                    <i class="far fa-calendar-alt"></i>
                    August 08, 2026
                </small>

                <p>
                    he orientation aimed to provide the beneficiaries and their families with a deeper understanding of the program, including their roles, responsibilities, and the collaborative efforts of the Local Government Unit (LGU) and the Department of Labor and Employment (DOLE) in ensuring the successful implementation of SPES.
                </p>

                <span class="mio-read-more">
                    Read More
                    <i class="fas fa-arrow-right"></i>
                </span>

            </div>

        </a>


        


    </div>


    <!-- =================================
         RIGHT : LARGE PESO LOGO
    ================================== -->

    <div class="mio-logo-column">

        <div class="mio-logo-background">

            <img src="OFFICES LOGO/PESO ISULAN.png"
                 alt="Public Employment Services Office"
                 class="mio-huge-logo">

            <h3>
                PUBLIC EMPLOYMENT SERVICES OFFICE
            </h3>

            <p>
                Connecting job seekers with employment opportunities,
                career services, skills development, training programs,
                and livelihood assistance in the Municipality of Isulan.
            </p>

        </div>

    </div>

</div>

</section>




<!-- =========================
     END PESO Section
========================== -->





<!-- ORGANIZATIONAL STRUCTURE -->

<section id="organizational-structure" class="org-chart py-1">

<div class="container org-container">

<h2 class="text-center fw-bold mb-5">

ORGANIZATIONAL STRUCTURE
</h2>

<!-- TOP -->
<div class="row justify-content-center">
    <div class="col-lg-4 col-md-6">

        <div class="org-card">
            <img src="Mayors corner/mayor bai 2.png" class="org-photo">

            <h5 class="mt-3">
                HON. PRINCESS RIHAN M. SAKALURAN
            </h5>

            <p>Municipal Mayor</p>

        </div>

    </div>
</div>

<div class="v-line"></div>

<div class="h-line"></div>

<!-- SECOND LEVEL -->

<div class="row justify-content-center text-center">

    <div class="col-md-4">

        <div class="org-card">

            <img src="LGU officials and heads/atty YLa.png" class="org-photo">

            <h6>ATTY SHEILA B. FERNANDEZ</h6>

            <small>Municipal Administrator</small>

        </div>

    </div>

    <div class="col-md-4">

        <div class="org-card">

            <img src="LGU officials and heads/atty armada.png" class="org-photo">

            <h6>HON. ATTY. ARNOLD H. ARMADA</h6>

            <small>Vice Myaor</small>

        </div>

    </div>

    <div class="col-md-4">

        <div class="org-card">

            <img src="LGU officials and heads/atty gleyo.png" class="org-photo">

            <h6>ATTY. MARCO RAY S. GLEYO</h6>

            <small>Municipal Legal Officer</small>

        </div>

    </div>

</div>

<!-- End of Org Structure -->


<!-- FEATURES -->
<!-- FEATURES -->
<div class="container text-center">
    <div class="certification">
        SERVE WITH A SMILE SERVICE WITH A HEART
    </div>
</div>


<div class="col-lg-3 text-center">
<img src="" class="iso-logo">
</div>

</div>

</div>

</section>





<!-- =========================================
     FOOTER
========================================= -->

<!-- =========================================
     GOVERNMENT FOOTER
========================================= -->
<div class="gov-footer-container">

    <!-- =========================================
         LEFT : GOVERNMENT / MUNICIPALITY LOGOS
    ========================================== -->

    <div class="gov-footer-main-logos">

        <!-- PHILIPPINE GOVERNMENT LOGO -->
        <div class="gov-main-logo">
            <img src="OFFICES LOGO/Coat_of_arms_of_the_Philippines.svg.webp"
                 alt="Republic of the Philippines">
        </div>

        <!-- SK LOGO -->
        <div class="gov-main-logo">
            <img src="OFFICES LOGO/SK LOGO1.png"
                 alt="Sangguniang Kabataan">
        </div>

        <!-- ISULAN LOGO -->
        <div class="gov-main-logo">
            <img src="OFFICES LOGO/isulan_logo-removebg-preview.png"
                 alt="Municipality of Isulan">
        </div>

    </div>


    <!-- =========================================
         RIGHT : DEPARTMENT LOGOS
    ========================================== -->

    <div class="gov-footer-departments">

        <h4>LGU ISULAN DEPARTMENTS</h4>

        <div class="department-logo-grid">

            <!-- MAYOR -->
            <div class="department-logo">
                <img src="isulan_logo-removebg-preview.png"
                     alt="Office of the Mayor">
            </div>

            <!-- VICE MAYOR -->
            <div class="department-logo">
                <img src="OFFICES LOGO/SB OFFICE.png"
                     alt="Office of the Vice Mayor">
            </div>

            <!-- ADMINISTRATOR -->
            <div class="department-logo">
                <img src="OFFICES LOGO/isulan_logo-removebg-preview.png"
                     alt="Municipal Administrator">
            </div>

            <!-- ENGINEERING -->
            <div class="department-logo">
                <img src="OFFICES LOGO/MEO.png"
                     alt="Municipal Engineering Office">
            </div>

            <!-- ASSESSOR -->
            <div class="department-logo">
                <img src="OFFICES LOGO/assessor.png"
                     alt="Municipal Assessor's Office">
            </div>

            <!-- TREASURER -->
            <div class="department-logo">
                <img src="OFFICES LOGO/treasurers office.png"
                     alt="Municipal Treasurer's Office">
            </div>

            <!-- BUDGET -->
            <div class="department-logo">
                <img src="OFFICES LOGO/isulan_logo-removebg-preview.png"
                     alt="Municipal Budget Office">
            </div>

            <!-- HEALTH -->
            <div class="department-logo">
                <img src="OFFICES LOGO/MHO ISULAN.png"
                     alt="Municipal Health Office">
            </div>

            <!-- AGRICULTURE -->
            <div class="department-logo">
                <img src="OFFICES LOGO/omag isulan.png"
                     alt="Municipal Agriculture Office">
            </div>

            <!-- PESO -->
            <div class="department-logo">
                <img src="OFFICES LOGO/PESO ISULAN.png"
                     alt="Public Employment Services Office">
            </div>

            <!-- INFORMATION -->
            <div class="department-logo">
                <img src="OFFICES LOGO/MIO.png"
                     alt="Municipal Information Office">
            </div>

            <!-- MDRRMO -->
            <div class="department-logo">
                <img src="OFFICES LOGO/MDRRMO.jpg"
                     alt="MDRRMO">
            </div>

            <!-- MPDO -->
            <div class="department-logo">
                <img src="OFFICES LOGO/Mpdo Logo.jpg"
                     alt="Municipal Planning and Development Office">
            </div>

            <!-- LEGAL -->
            <div class="department-logo">
                <img src="OFFICES LOGO/isulan_logo-removebg-preview.png"
                     alt="Legal Office">
            </div>

        </div>

    </div>


    <!-- =========================================
         FOOTER INFORMATION
    ========================================== -->    

        <!-- BACK TO TOP -->
        <button class="footer-back-top"
                type="button"
                onclick="window.scrollTo({
                    top: 0,
                    behavior: 'smooth'
                })">

            <i class="fas fa-arrow-up"></i>

        </button>

    </div>

</footer>
<div class="footer-bottom">

    <p class="designer mb-0">
        Designed and Managed by
        <strong>
            ENGR. DINDO I. CAMANSA JR. ENP., MPA ENP
            &amp; LGU Isulan ICT Team
        </strong>
    </p>

    <p class="copyright mb-0">
        © 2026 Municipality of Isulan. All Rights Reserved.
    </p>

</div>
</p>

</div>
</body>
</html>
