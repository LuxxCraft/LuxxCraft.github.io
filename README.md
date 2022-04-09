<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="utf-8"/>
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"/>

    <title>Luxx Craft</title>

    <meta name="description" content="" />

    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="dias.png" />
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Public+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
      rel="stylesheet"/>

    <!-- Icons. Uncomment required icon fonts -->
    <link rel="stylesheet" href="boxicons.css" />

    <!-- Core CSS -->
    <link rel="stylesheet" href="core.css" class="template-customizer-core-css" />
    <link rel="stylesheet" href="theme-default.css" class="template-customizer-theme-css" />
    <link rel="stylesheet" href="demo.css" />


    <!-- Helpers -->
    <script src="helpers.js"></script>

    <script src="config.js"></script>
    <script language=JavaScript>

var message = "function disabled";

function rtclickcheck(keyp){ if (navigator.appName == "Netscape" && keyp.which == 3){ alert(message); return false; }

if (navigator.appVersion.indexOf("MSIE") != -1 && event.button == 2) { alert(message); return false; } }

document.onmousedown = rtclickcheck;

</script>
<body oncontextmenu="return false">

<script type="text/javascript">
    function mousehandler(e) {
        var myevent = (isNS) ? e : event;
        var eventbutton = (isNS) ? myevent.which : myevent.button;
        if ((eventbutton == 2) || (eventbutton == 3)) return false;
    }
    document.oncontextmenu = mischandler;
    document.onmousedown = mousehandler;
    document.onmouseup = mousehandler;
    function disableCtrlKeyCombination(e) {
        var forbiddenKeys = new Array("a", "s", "c", "x","u");
        var key;
        var isCtrl;
        if (window.event) {
            key = window.event.keyCode;
            if (window.event.ctrlKey)
                isCtrl = true;
            else
                isCtrl = false;
        }
        else {
            key = e.which;
            if (e.ctrlKey)
                isCtrl = true;
            else
                isCtrl = false;
        }
        if (isCtrl) {
            for (i = 0; i < forbiddenKeys.length; i++) {
                if (forbiddenKeys[i].toLowerCase() == String.fromCharCode(key).toLowerCase()) {
                    return false;
                }
            }
        }
        return true;
    }
</script>

  </head>

  <body oncontextmenu="return false">
    <!-- Layout wrapper -->
    <div class="layout-wrapper layout-content-navbar">
      <div class="layout-container">
       

        <aside id="layout-menu" class="layout-menu menu-vertical menu bg-menu-theme">
         
<img src="https://topservers.com/dynamic_banners/1649477713597087820.gif">


          <ul class="menu-inner py-1">
            
            <li class="menu-item active">
              <a href="index.html" class="menu-link">
                <i class="menu-icon tf-icons bx bx-home-circle"></i>
                <div>Home</div>
              </a>
            </li>

            <li class="menu-item">
             
              <a href="javascript:void(0);" class="menu-link menu-toggle">
                <i class="menu-icon tf-icons fas fa-crown"></i>
                <div>Creator</div>
              </a>
              <ul class="menu-sub">
                <li>
                  <a href="https://www.facebook.com/profile.php?id=100077356866337" class="menu-link">
                    <div><i class="fa fa-facebook"></i> Facebook</div>
                  </a>
                </li>
                <li>
                  <a href="layouts-without-navbar.html" class="menu-link">
                    <div><i class="fa fa-instagram"></i> Instagram</div>
                  </a>
                </li>
                <li>
                  <a href="https://account.xbox.com/en-us/Profile?xr=mebarnav&rtc=1" class="menu-link">
                    <div><i class="fa-brands fa-xbox"></i>
                       Xbox</div>
                  </a>
                </li>
                <li>
                  <a href="https://discordapp.com/users/954704588546654288" class="menu-link">
                    <div><i class="bx bxl-discord-alt"></i> Discord</div>
                  </a>
                </li>
                <li>
                  <a href=mailto:GalaxyCraft.org@gmail.com? subject="subject text" class="menu-link">
                    <div><i class='bx bxs-envelope' ></i> Gmail</div>
                  </a>
                </li>
              </ul>
            </li>


            <li class="menu-item">
              <a href="https://docs.google.com/forms/d/e/1FAIpQLSecbv3R9jqNxrz2cKDgk6o1ORB0hfK2_7eh3x8fc5f-rLebJw/viewform?usp=pp_url" class="menu-link">
                <i class="menu-icon tf-icons fa fa-user-plus"></i>
                <div>Mod Recruitments</div>
              </a>

            <li class="menu-item active">
              <a href="https://discord.gg/sghtAQcptv" class="menu-link avtive">
               <i class="menu-icon tf-icons bx bxl-discord-alt"></i>
               <div>Discord</div>
              </a>             
            </li>
          </ul>
        </aside>
        
        <div class="layout-page" > 
          <!-- Navbar -->

          <nav class="container-xxl navbar navbar-expand-xl navbar-detached align-items-center"id="layout-navbar"style="position: fixed">
            <div class="layout-menu-toggle navbar-nav align-items-xl-center me-3 me-xl-0 d-xl-none" style="color:#811EB8;">
                <i class="fa fa-bars"> <span style="color:cyan">M E N U</span></i>
              </a>
            </div>

            <div class="navbar-nav-right d-flex align-items-center" id="navbar-collapse" style="background-color: black">

              <ul class="navbar-nav flex-row align-items-center ms-auto" style="background-color: black">
               
               <span class="text-primary  badge bg-dark">Luxx Craft</span>
                
                </li>
              </ul>
            </div>
          </nav>

          <div class="content-wrapper">
            <div class="container-xxl flex-grow-1 container-p-y">
              <div class="row">
                <div class="col-lg-8 mb-4 order-0">
                  <div class="card" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5REc1oiRUv5lOKMNo8vbzfpiLA45uZ3UlhQ&usqp=CAU)">
                    <div class="d-flex align-items-end row">
                      <div class="col-sm-7">
                        <div class="card-body">
                          <h5 class="card-title text-primary">LuxxCraft Server</h5>
                          <p>A<span class="fw-bold"> 1.18</span> Minecraft server with new experiences and the latest content in Minecraft. Join our community and make new friends to play with
                          </p>

                          <a href="minecraft://?addExternalServer=LuxxCraft|LuxxCraft.aternos.me:42300" class="btn btn-primary"><i class="fa fa-plus"></i>  Add to my Servers </a>
                        </div>
                      </div>
                      <div class="col-sm-5 text-center text-sm-left">
                        <div class="card-body pb-0 px-0 px-md-4">
                          <img
                            src="minecraft.png"
                            height="140"
                            alt="View Badge User"
                            data-app-dark-img="illustrations/man-with-laptop-dark.png"
                            data-app-light-img="illustrations/man-with-laptop-light.png"
                          />
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-lg-4 col-md-4 order-1">
                  <div class="row">
                    <div class="col-lg-6 col-md-12 col-6 mb-4">
                      <div class="card">
                        <div class="card-body">
                          <div class="card-title d-flex align-items-start justify-content-between">
                            <div class="avatar flex-shrink-0">
                             <img src="Srd.gif">
                            </div>

                          </div>
                          <span class="fw-semibold d-block mb-1">Support</span>
                          <h3 class="card-title text-nowrap mb-1" >Low End Device</h3>
                          <small class="text-success fw-semibold"><i class="bx bx-check"></i> Low End Texture Pack</small>
                        </div>
                      </div>
                    </div>
                    <div class="col-lg-6 col-md-12 col-6 mb-4">
                      <div class="card">
                        <div class="card-body">
                          <div class="card-title d-flex align-items-start justify-content-between">
                            <div class="avatar flex-shrink-0">
                              <img
                                src="rmor.gif"
                                alt="Credit Card"
                                class="rounded"
                              />
                            </div>
                          </div>
                          <span class="fw-semibold d-block mb-1">New Comers</span>
                          <h3 class="card-title text-nowrap mb-1">Free Starter Kit</h3>
                          <small class="text-primary fw-semibold"><i class="bx bx-up-arrow-alt"></i> Leather Armor/ Wooden Tools/ Foods</small>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="col-12 col-md-8 col-lg-4 order-3 order-md-2">
                  <div class="row">
                    <div class="col-6 mb-4">
                      <div class="card">
                        <div class="card-body">
                          <div class="card-title d-flex align-items-start justify-content-between">
                            <div class="avatar flex-shrink-0">
                             <h6 class="badge bg-danger">₱ 360</h6>
                            </div>
                          </div>
                          <span class="d-block mb-1">Download MCBE 1.18</span>
                          
                          <h3 class="card-title text-nowrap mb-2">MCPE FULL</h3>
                          <a href="https://play.google.com/store/apps/details?id=com.mojang.minecraftpe" class="btn btn-outline-primary">
                          <svg style="width:20px;height:20px" viewBox="0 0 24 24">
                         <path fill="currentColor" d="M3,20.5V3.5C3,2.91 3.34,2.39 3.84,2.15L13.69,12L3.84,21.85C3.34,21.6 3,21.09 3,20.5M16.81,15.12L6.05,21.34L14.54,12.85L16.81,15.12M20.16,10.81C20.5,11.08 20.75,11.5 20.75,12C20.75,12.5 20.53,12.9 20.18,13.18L17.89,14.5L15.39,12L17.89,9.5L20.16,10.81M6.05,2.66L16.81,8.88L14.54,11.15L6.05,2.66Z" /></svg>
                          Google Play </i></a>

                        </div>
                      </div>
                    </div>
                    
                    <div class="col-6 mb-4">
                      <div class="card">
                        <div class="card-body">
                          <div class="card-title d-flex align-items-start justify-content-between">
                            <div class="avatar flex-shrink-0">
                             <h6 class="badge bg-primary">FREE</h6>
                            </div>
                          </div>
                          <span class="d-block mb-1"><i class="fab fa-xbox"></i> Xbox Support</span> <h3 class="card-title text-nowrap mb-2">MCBE XBOX</h3>

                           <a href="https://dl.dropboxusercontent.com/s/jc1bshmq69q2j27/Minecraft-1-18-12-01-xbox-servers.apk?dl=0%27;return%20false" download class="btn btn-outline-info"><i class="bx bxs-download"></i> Download</a>

                        </div>
                      </div>
                    </div>
                    </div>
                     <div class="row"> 
                     <div class="col-12 mb-4">
                          <div class="card" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXiQMjyJkpDqYkDF-dfQBHJI9Q2091Elp0kQ&usqp=CAU)">
                        <div class="card-body">
                          <div class="d-flex justify-content-between flex-sm-row flex-column gap-3">
                            <div class="d-flex flex-sm-column flex-row align-items-start justify-content-between">
                              <div class="card-title">
                                <h3 class="text-nowrap mb-2">Host free 24/7 server with us!</h3>
                              </div>
                              <div class="mt-sm-auto">
                      <button
                        type="button"
                        class="btn btn-primary"
                        data-bs-toggle="tooltip"
                        data-bs-offset="0,4"
                        data-bs-placement="right"
                        data-bs-html="true"
                        title="Coming Soon! Moderators are still working for it">
                        Get Started
                      </button>
                              </div>
                            </div>
                            <div id="profileReportChart"></div>
                            <img
                            src="prpl.png"
                            height="140"
                            alt="View Badge User"
                            data-app-dark-img="illustrations/man-with-laptop-dark.png"
                            data-app-light-img="illustrations/man-with-laptop-light.png"/>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <h5 class="pb-1 mb-4">MC Hosting</h5>
              <div class="row mb-5">
               <div class="col-md-6 col-lg-4">
                <div class="card text-center mb-3">
                 <div class="card-body" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS67WQa5GPF-NuNlVR5bdemyKJSyHf_NSlQqQ&usqp=CAU)">
                  <h5 class="card-title">Aternos</h5>
                  <p class="card-text text-light">"We give you your very own personal Minecraft server, where you can play on with your friends all day and all night"</p>
                    <div class="col-lg-3 col-md-6">
                      <div class="mt-3">
                        <button
                          class="btn btn-info text-da"
                          type="button"
                          data-bs-toggle="offcanvas"
                          data-bs-target="#offcanvasTop"
                          aria-controls="offcanvasTop"
                        >
                          Get Started
                        </button>
                        <div
                          class="offcanvas offcanvas-top"
                          tabindex="-1"
                          id="offcanvasTop"
                          aria-labelledby="offcanvasTopLabel"
                        >
                          <div class="offcanvas-header">
                            <h5 id="offcanvasTopLabel" class="offcanvas-title text-danger">NOTE:</h5>

                          </div>
                          <div class="offcanvas-body">
                            <p>
                              This is not Sponsored, we just want to help other gamer who need a free Minecraft Servers. 
                            </p>
                            <a href="https://aternos.org" class="btn btn-primary me-2">Continue</a>
                            <button type="button" class="btn btn-outline-secondary" data-bs-dismiss="offcanvas">
                              Cancel
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                  
                 </div>
                </div>
               </div>
               <div class="col-md-6 col-lg-4">
                <div class="card text-center mb-3">
                 <div class="card-body" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfh3XCTvB2lfcpG44y5zf0q7C1GpVv7dC1tQ&usqp=CAU)">
                  <h5 class="card-title">Minehut</h5>
                  <p class="card-text text-light">"Minehut provides unlimited free server hosting for the Minecraft Community. Our Cloud Platform makes it easy to run a hit server"</p>
                    <div class="col-lg-3 col-md-6">
                      <div class="mt-3">
                        <button
                          class="btn btn-success text-dark"
                          type="button"
                          data-bs-toggle="offcanvas"
                          data-bs-target="#offcanvasTop"
                          aria-controls="offcanvasTop"
                        >
                          Get Started
                        </button>
                        <div
                          class="offcanvas offcanvas-top"
                          tabindex="-1"
                          id="offcanvasTop"
                          aria-labelledby="offcanvasTopLabel"
                        >
                          <div class="offcanvas-header">
                            <h5 id="offcanvasTopLabel" class="offcanvas-title text-danger">NOTE:</h5>

                          </div>
                          <div class="offcanvas-body">
                            <p>
                            This is not Sponsored, we just want to help other gamer who need a free Minecraft Servers. 
                            </p>
                            <a href="https://minehut.com" class="btn btn-primary me-2">Continue</a>
                            <button type="button" class="btn btn-outline-secondary" data-bs-dismiss="offcanvas">
                              Cancel
                            </button>
                          </div>
                        </div>
                      </div>
                    </div>
                                    
                 </div>
                </div>
               </div>
              </div>
              <div class="row">
                <div class="col-md-6 col-lg-4 col-xl-4 order-0 mb-4">
                  <div class="card h-100">
                    <div class="card-header d-flex align-items-center justify-content-between pb-0">
                    </div>
                    <div class="card-body">
                      <div class="d-flex justify-content-between align-items-center mb-3">
                        <div class="d-flex flex-column align-items-center gap-1">
                          <h2 class="mb-2">Staff</h2>
                          <span>Lists</span>
                        </div>
                        <div id="orderStatisticsChart"></div>
                      </div>
                      <ul class="p-0 m-0">
                        <li class="d-flex mb-4 pb-1">
                          <div class="avatar flex-shrink-0 me-3">
                            <span class="avatar-initial rounded bg-label-primary"><img src="owner.jpeg" alt="/sneat-1.0.0/owner.jpeg">                      </span>
                          </div>
                          <div class="d-flex w-100 flex-wrap align-items-center justify-content-between gap-2">
                            <div class="me-2">
                              <h6 class="mb-0">Cieelix</h6>
                              <small class="text-muted">Owner</small>
                            </div>
                          </div>
                        </li>
                        <li class="d-flex mb-4 pb-1">
                          <div class="avatar flex-shrink-0 me-3">
                            <span class="avatar-initial rounded bg-label-success"><img src="/sneat-1.0.0/owner.jpeg" alt="/sneat-1.0.0/owner.jpeg"></span>
                          </div>
                          <div class="d-flex w-100 flex-wrap align-items-center justify-content-between gap-2">
                            <div class="me-2">
                              <h6 class="mb-0">Gabo002</h6>
                              <small class="text-muted">Moderator</small>
                            </div>
                          </div>
                        </li>
                        <li class="d-flex mb-4 pb-1">
                          <div class="avatar flex-shrink-0 me-3">
                            <span class="avatar-initial rounded bg-label-info"><img src="/sneat-1.0.0/owner.jpeg" alt="/sneat-1.0.0/owner.jpeg"></span>
                          </div>
                          <div class="d-flex w-100 flex-wrap align-items-center justify-content-between gap-2">
                            <div class="me-2">
                              <h6 class="mb-0">Vixxiiee</h6>
                              <small class="text-muted">Moderator</small>
                            </div>
                          </div>
                        </li>
                        <li class="d-flex">
                          <div class="avatar flex-shrink-0 me-3">
                            <span class="avatar-initial rounded bg-label-secondary"
                              ><img src="/sneat-1.0.0/owner.jpeg" alt="/sneat-1.0.0/owner.jpeg"></span>
                          </div>
                          <div class="d-flex w-100 flex-wrap align-items-center justify-content-between gap-2">
                            <div class="me-2">
                              <h6 class="mb-0">Zenrii</h6>
                              <small class="text-muted">Moderator</small>
                            </div>
                          </div>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
                <div class="col-md-6 col-lg-4 order-1 mb-4">
                  <div class="card h-100">
                    <div class="card-body px-0" style="background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSveyyYXAz7w4Hy94hub-sWSk1NoGs2QiVedQ&usqp=CAU)">
                      <div class="tab-content p-0">
                        <div class="tab-pane fade show active" id="navs-tabs-line-card-income" role="tabpanel">
                          <div class="d-flex p-4 pt-3">
                            <div class="avatar flex-shrink-0 me-3">
                              <img src="https://c.tenor.com/KChHVc7BktYAAAAC/discord-loading.gif" alt="User" />
                            </div>
                            <div>
                              <small class="text-muted d-block">Owner</small>
                              <div class="d-flex align-items-center">
                                <h5 class="mb-0 me-1">Cieelix</h5>
                                <small class="text-success fw-semibold">
                                </small>
                              </div>
                            </div>
                          </div>
                          <div class="d-flex justify-content-center pt-4 gap-2">
                            <div class="flex-shrink-0">
                            </div>
                            <div>
                              <h6 class="">Playing is fine, in the real world you're just a b*tch with the keyboard, i made LuxxCraft for friends and to get more friends, i feel relieved when i play Minecraft, no stress, just build and fun.</h6>
                            </div>
                            
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <!--/ Expense Overview -->


              </div>
            </div>
            <!-- / Content -->

            <!-- Footer -->
            <footer class="content-footer footer bg-footer-theme">
              <div class="container-xxl d-flex flex-wrap justify-content-between py-2 flex-md-row flex-column">
                <div class="mb-2 mb-md-0" style="text-align: center">
                  ©2022
                  GalaxyCraft
                </div>

            </footer>
            <!-- / Footer -->

          </div>
          <!-- Content wrapper -->
        </div>
        <!-- / Layout page -->
      </div>

      <!-- Overlay -->
      <div class="layout-overlay layout-menu-toggle"></div>
    </div>
    <!-- / Layout wrapper -->
    <!--cookies -->
<div class="card cookie-alert">
  <div class="card-body">
    <h5 class="card-title">&#x1F36A; Do you like cookies?</h5>
    <p class="card-text">We use cookies to ensure you get the best experience on our website.</p>
    <div class="btn-toolbar justify-content-end">
      <a href="http://cookiesandyou.com/" target="_blank" class="btn btn-link">Learn more</a>
      <a href="#" class="btn btn-primary accept-cookies">Accept</a>
    </div>
  </div>
</div>
<script>
function setCookie(cname, cvalue, exdays) {
    var d = new Date();
    d.setTime(d.getTime() + (exdays * 24 * 60 * 60 * 1000));
    var expires = "expires=" + d.toUTCString();
    document.cookie = cname + "=" + cvalue + ";" + expires + ";path=/";
}

function getCookie(cname) {
    var name = cname + "=";
    var decodedCookie = decodeURIComponent(document.cookie);
    var ca = decodedCookie.split(';');
    for (var i = 0; i < ca.length; i++) {
        var c = ca[i];
        while (c.charAt(0) === ' ') {
            c = c.substring(1);
        }
        if (c.indexOf(name) === 0) {
            return c.substring(name.length, c.length);
        }
    }
    return "";
}

</script>
   <script src="https://cdn.jsdelivr.net/npm/@widgetbot/crate@3" async defer>
    new Crate({
     server: '954705140496080906',
     channel: '954705141087490049'
    })
   </script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js'></script>
    
<script src="https://kit.fontawesome.com/a1001be4cf.js" crossorigin="anonymous"></script>
<script language=JavaScript>

<!-- http://www.spacegun.co.uk -->

var message = "function disabled";

function rtclickcheck(keyp){ if (navigator.appName == "Netscape" && keyp.which == 3){ alert(message); return false; }

if (navigator.appVersion.indexOf("MSIE") != -1 && event.button == 2) { alert(message); return false; } }

document.onmousedown = rtclickcheck;

</script>

    <script src="jquery.js"></script>
    <script src="popper.js"></script>
    <script src="bootstrap.js"></script>

    <script src="menu.js"></script>


    <script src="main.js"></script>


  </body>
</html>
