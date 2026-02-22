this is all my code ok? so you can just change it on your own so i wont have to do it manually when i need to modify the website

index html:

<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Immaculate Heart of Mary College Inc.</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>

<body>

code
Code
download
content_copy
expand_less
<header>
    <div class="header-left">
        <div class="logo">
            <a href="index.html"><img src="images.png" alt="School Logo"></a>
        </div>
        <div class="school-info">
            <div class="school-name">IMMACULATE HEART OF MARY COLLEGE INC.</div>

            <nav class="nav-menu">


                <div class="dropdown">
                    <button class="dropbtn">FACILITIES <i class="fa-solid fa-chevron-down"></i></button>
                    <div class="dropdown-content">
                        <div class="sub-dropdown">
                            <a href="#" class="sub-dropbtn">COMP LAB <i class="fa-solid fa-caret-right"></i></a>
                            <div class="sub-dropdown-content">
                                <a href="complab.html">CAI Lab</a>
                                <a href="complab.html">Lower Computer Lab</a>
                                <a href="complab.html">Upper Computer Lab</a>
                            </div>
                        </div>
                        <div class="sub-dropdown">
                            <a href="#" class="sub-dropbtn">TLE LAB <i class="fa-solid fa-caret-right"></i></a>
                            <div class="sub-dropdown-content">
                                <a href="tle.html">TLE Laboratory</a>
                                <a href="#">HELE Laboratory</a>
                                <a href="#">IA Laboratory</a>
                            </div>
                        </div>
                        <div class="sub-dropdown">
                            <a href="#" class="sub-dropbtn">SCI LAB <i class="fa-solid fa-caret-right"></i></a>
                            <div class="sub-dropdown-content">
                                <a href="scilab.html">Science Laboratory</a>
                                <a href="#">Chemistry Laboratory</a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="dropdown">
                    <button class="dropbtn">ABOUT US <i class="fa-solid fa-chevron-down"></i></button>
                    <div class="dropdown-content wide">
                        <a href="about.html">Vision & Mission</a>
                        <a href="about.html">Purpose of Website</a>
                        <a href="about.html">Gratitude</a>
                    </div>
                </div>
            </nav>
        </div>
    </div>


</header>

<div class="main-content">
    <div class="glass-box carousel-container">
        <input type="radio" name="slider" id="r1" checked>
        <input type="radio" name="slider" id="r2">
        <input type="radio" name="slider" id="r3">
        <input type="radio" name="slider" id="r4">
        <input type="radio" name="slider" id="r5">
        <input type="radio" name="slider" id="r6">
        <input type="radio" name="slider" id="r7">
        <input type="radio" name="slider" id="r8">
        <input type="radio" name="slider" id="r9">
        <input type="radio" name="slider" id="r10">

        <div class="carousel-track">
            <div class="carousel-slide slide-1"></div>
            <div class="carousel-slide slide-2"></div>
            <div class="carousel-slide slide-3"></div>
            <div class="carousel-slide slide-4"></div>
            <div class="carousel-slide slide-5"></div>
            <div class="carousel-slide slide-6"></div>
            <div class="carousel-slide slide-7"></div>
            <div class="carousel-slide slide-8"></div>
            <div class="carousel-slide slide-9"></div>
            <div class="carousel-slide slide-10"></div>
        </div>

        <div class="arrows">
            <label for="r10" class="arrow-label arrow-left slide1-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r2" class="arrow-label arrow-right slide1-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r1" class="arrow-label arrow-left slide2-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r3" class="arrow-label arrow-right slide2-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r2" class="arrow-label arrow-left slide3-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r4" class="arrow-label arrow-right slide3-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r3" class="arrow-label arrow-left slide4-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r5" class="arrow-label arrow-right slide4-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r4" class="arrow-label arrow-left slide5-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r6" class="arrow-label arrow-right slide5-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r5" class="arrow-label arrow-left slide6-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r7" class="arrow-label arrow-right slide6-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r6" class="arrow-label arrow-left slide7-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r8" class="arrow-label arrow-right slide7-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r7" class="arrow-label arrow-left slide8-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r9" class="arrow-label arrow-right slide8-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r8" class="arrow-label arrow-left slide9-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r10" class="arrow-label arrow-right slide9-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>

            <label for="r9" class="arrow-label arrow-left slide10-arrow"><i
                    class="fa-solid fa-chevron-left"></i></label>
            <label for="r1" class="arrow-label arrow-right slide10-arrow"><i
                    class="fa-solid fa-chevron-right"></i></label>
        </div>

        <div class="dots">
            <label for="r1" class="dot-label d1"></label>
            <label for="r2" class="dot-label d2"></label>
            <label for="r3" class="dot-label d3"></label>
            <label for="r4" class="dot-label d4"></label>
            <label for="r5" class="dot-label d5"></label>
            <label for="r6" class="dot-label d6"></label>
            <label for="r7" class="dot-label d7"></label>
            <label for="r8" class="dot-label d8"></label>
            <label for="r9" class="dot-label d9"></label>
            <label for="r10" class="dot-label d10"></label>
        </div>
    </div>

    <div class="glass-box announcement-container">
        <div class="announcement-header">
            <span>Announcement</span>
            <i class="fa-solid fa-bullhorn announcement-icon"></i>
        </div>
    </div>
</div>

<footer>
    <div class="contact-item">
        <div class="icon-circle"><i class="fa-solid fa-phone-volume"></i></div><span class="contact-text">(02)
            8-715-0850</span>
    </div>
    <div class="contact-item">
        <div class="icon-circle"><i class="fa-solid fa-globe"></i></div><span
            class="contact-text">www.immaculateheartqc.org</span>
    </div>
    <div class="contact-item">
        <div class="icon-circle"><i class="fa-solid fa-envelope"></i></div><span
            class="contact-text">ihmcregistrar1949@gmail.com</span>
    </div>
</footer>
</body>

</html>


science lab.html:

<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Science Laboratory</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="tle_styles.css">
</head>

<body class="sci-theme">

code
Code
download
content_copy
expand_less
<header>
    <div class="header-left">
        <div class="logo">
            <a href="index.html"><img src="images.png" alt="Logo"></a>
        </div>
        <div class="header-text">
            <div class="school-name">IMMACULATE HEART OF MARY COLLEGE INC.</div>
            <div class="page-name">FACILITIES</div>
        </div>

</header>

<input type="radio" name="nav" id="tab_intro" checked>
<input type="radio" name="nav" id="tab_rules">
<input type="radio" name="nav" id="tab_safety">
<input type="radio" name="nav" id="tab_equip">
<input type="radio" name="nav" id="tab_emer">

<div class="main-body">

    <div class="sidebar">
        <label for="tab_intro" class="sidebar-btn btn-intro">INTRODUCTION</label>
        <label for="tab_rules" class="sidebar-btn btn-rules">GENERAL<br>LABORATORY RULES</label>
        <label for="tab_safety" class="sidebar-btn btn-safe">SAFETY & PROPER<br>HANDLING PROCEDURE</label>
        <label for="tab_equip" class="sidebar-btn btn-equip">SAFETY & PROPER<br>HANDLING EQUIPMENT</label>
        <label for="tab_emer" class="sidebar-btn btn-emer red-btn">PROPER PRECAUTION /<br>EMERGENCY
            PROCEDURE</label>
    </div>

    <div class="content-area">

        <div class="content-section" id="sec_intro">
            <div class="content-box">
                <h1 class="slide-header-text">INTRODUCTION</h1>
                <p>The Science Laboratory provides students with the necessary equipment and environment to conduct
                    experiments in Biology, Chemistry, and Physics. It is a space designed to foster scientific
                    inquiry, critical thinking, and safety awareness.</p>

                <div class="box-navigation">
                    <div></div> 
                    <label for="tab_rules" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_rules">
            <div class="content-box">
                <h1 class="slide-header-text">GENERAL LABORATORY RULES</h1>
                <ul class="custom-list">
                    <li><strong>No Food or Drink:</strong> Strictly prohibited to prevent contamination.</li>
                    <li><strong>PPE Required:</strong> Wear lab coats and goggles during experiments.</li>
                    <li><strong>Horseplay:</strong> Running or playing is forbidden.</li>
                    <li><strong>Chemicals:</strong> Never taste or smell chemicals directly.</li>
                    <li><strong>Cleanliness:</strong> Clean your station before leaving.</li>
                </ul>

                <div class="box-navigation">
                    <label for="tab_intro" class="arrow-btn">◀ </label>
                    <label for="tab_safety" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_safety">
            <div class="content-box">
                <h1 class="slide-header-text">SAFETY & PROPER HANDLING</h1>
                <p><strong>Handling Chemicals:</strong> Always read labels twice. Pour acid into water, never water
                    into acid.</p>
                <p><strong>Glassware:</strong> Check for cracks before use. Use tongs for hot glass.</p>
                <p><strong>Microscopes:</strong> Carry with two hands (one on the arm, one on the base). Use lens
                    paper for cleaning.</p>

                <div class="box-navigation">
                    <label for="tab_rules" class="arrow-btn">◀</label>
                    <label for="tab_equip" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_equip">
            <div class="content-box">
                <h1 class="slide-header-text">HANDLING EQUIPMENT</h1>
                <ol class="custom-ol">
                    <li><strong>Bunsen Burners:</strong> Tie back long hair. Never leave a lit burner unattended.
                    </li>
                    <li><strong>Electronic Balances:</strong> Keep clean and dry. Do not overload.</li>
                    <li><strong>Test Tubes:</strong> Point away from yourself and others when heating.</li>
                </ol>

                <div class="box-navigation">
                    <label for="tab_safety" class="arrow-btn">◀</label>
                    <label for="tab_emer" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_emer">
            <div class="content-box">
                <h1 class="slide-header-text">EMERGENCY PROCEDURE</h1>
                <p><strong>Chemical Spill:</strong> Inform teacher immediately. Wash with water if on skin.</p>
                <p><strong>Broken Glass:</strong> Do not pick up with hands. Use broom and dustpan.</p>
                <p><strong>Fire:</strong> Use fire extinguisher or fire blanket. Evacuate calmly.</p>

                <div class="box-navigation">
                    <label for="tab_equip" class="arrow-btn">◀</label>
                    <div></div> 
                </div>
            </div>
        </div>

    </div>
</div>
</body>

</html>


computerlab.html:

<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Laboratory</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="tle_styles.css">
</head>

<body class="comp-theme">

code
Code
download
content_copy
expand_less
<header>
    <div class="header-left">
        <div class="logo">
            <a href="index.html"><img src="images.png" alt="Logo"></a>
        </div>
        <div class="header-text">
            <div class="school-name">IMMACULATE HEART OF MARY COLLEGE INC.</div>
            <div class="page-name">FACILITIES</div>
        </div>

        <nav class="main-nav">

</header>

<input type="radio" name="nav" id="tab_intro" checked>
<input type="radio" name="nav" id="tab_obj">
<input type="radio" name="nav" id="tab_dos">
<input type="radio" name="nav" id="tab_game">
<input type="radio" name="nav" id="tab_equip">
<input type="radio" name="nav" id="tab_shutdown">
<input type="radio" name="nav" id="tab_maint">
<input type="radio" name="nav" id="tab_prohib">
<input type="radio" name="nav" id="tab_cons">
<input type="radio" name="nav" id="tab_commit">
<input type="radio" name="nav" id="tab_emer1">
<input type="radio" name="nav" id="tab_emer2">
<input type="radio" name="nav" id="tab_emer3">

<div class="main-body">
    <div class="sidebar">
        <label for="tab_intro" class="sidebar-btn btn-intro">INTRODUCTION</label>
        <label for="tab_obj" class="sidebar-btn btn-obj">GENERAL<br>OBJECTIVES</label>
        <label for="tab_dos" class="sidebar-btn btn-dos">DO'S AND DONT'S<br>INSIDE COM LAB</label>
        <label for="tab_game" class="sidebar-btn btn-game">GAME PLAYING POLICY<br>(THREE-STRIKE RULE)</label>
        <label for="tab_equip" class="sidebar-btn btn-equip">USE OF COMPUTER<br>LABORATORY EQUIPMENT</label>
        <label for="tab_prohib" class="sidebar-btn btn-prohib">PROHIBITED ITEMS AND<br>PRACTICES</label>
        <label for="tab_cons" class="sidebar-btn btn-cons">CONSEQUENCES FOR<br>MANUAL VIOLATIONS</label>
        <label for="tab_emer1" class="sidebar-btn btn-emer red-btn">PROPER PRECAUTION /<br>EMERGENCY
            PROCEDURE</label>
    </div>

    <div class="content-area">

        <div class="content-section" id="sec_intro">
            <div class="content-box">
                <h1 class="slide-header-text">INTRODUCTION</h1>
                <p>The Computer Laboratory of Immaculate Heart of Mary College is a dedicated space for students to
                    develop digital skills, explore creativity, and engage in meaningful learning activities.</p>
                <p>This manual outlines the standards of behavior, safety protocols, and proper equipment usage to
                    ensure that the lab is used efficiently and responsibly.</p>
                <div class="box-navigation">
                    <div></div>
                    <label for="tab_obj" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_obj">
            <div class="content-box">
                <h1 class="slide-header-text">GENERAL OBJECTIVES</h1>
                <ol class="custom-ol">
                    <li>To guide proper and ethical use of ICT resources.</li>
                    <li>To maintain cleanliness, safety, and functionality of the lab.</li>
                    <li>To develop digital citizenship and responsible technology usage.</li>
                    <li>To avoid misuse, damage, or loss of computer and network equipment.</li>
                </ol>
                <div class="box-navigation">
                    <label for="tab_intro" class="arrow-btn">◀ </label>
                    <label for="tab_dos" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_dos">
            <div class="content-box">
                <h1 class="slide-header-text">Do's and Don'ts</h1>
                <ol class="custom-ol spaced-list">
                    <li>Always follow the teacher's instructions.</li>
                    <li>Log in only using your assigned account credentials.</li>
                    <li>Sit at your assigned workstation.</li>
                    <li>Handle all equipment with care.</li>
                </ol>
                <div class="box-navigation">
                    <label for="tab_obj" class="arrow-btn">◀ </label>
                    <label for="tab_game" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_game">
            <div class="content-box">
                <h1 class="slide-header-text">Game Playing Policy</h1>
                <p>Playing games during class hours without permission is strictly prohibited.</p>
                <p><strong>1st Offense:</strong> Verbal warning.</p>
                <p><strong>2nd Offense:</strong> Parent notification.</p>
                <p><strong>3rd Offense:</strong> Referral to Student Formation Office.</p>
                <div class="box-navigation">
                    <label for="tab_dos" class="arrow-btn">◀ </label>
                    <label for="tab_equip" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_equip">
            <div class="content-box">
                <h1 class="slide-header-text">Use of Equipment</h1>
                <p>Treat all ICT devices with respect and care. Students are not allowed to connect personal devices
                    unless authorized.</p>
                <div class="box-navigation">
                    <label for="tab_game" class="arrow-btn">◀ </label>
                    <label for="tab_shutdown" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_shutdown">
            <div class="content-box">
                <h1 class="slide-header-text">Proper Shutdown</h1>
                <p>Students must follow the correct shutdown procedure. Close all applications and save your work
                    before clicking Shut Down.</p>
                <div class="box-navigation">
                    <label for="tab_equip" class="arrow-btn">◀ </label>
                    <label for="tab_maint" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_maint">
            <div class="content-box">
                <h1 class="slide-header-text">Maintenance</h1>
                <p>Report any issues such as unresponsive keyboards or monitor display problems immediately. Do not
                    try to fix hardware problems on your own.</p>
                <div class="box-navigation">
                    <label for="tab_shutdown" class="arrow-btn">◀ </label>
                    <label for="tab_prohib" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_prohib">
            <div class="content-box">
                <h1 class="slide-header-text">Prohibited Practices</h1>
                <p>No Eating or Drinking inside the laboratory. Bags are to be placed in the designated area near
                    the entrance.</p>
                <div class="box-navigation">
                    <label for="tab_maint" class="arrow-btn">◀ </label>
                    <label for="tab_cons" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_cons">
          <div class="content-box">
                <h1 class="slide-header-text">OFFENSE & CONSEQUENCE</h1>
                <table class="exact-schedule-table">
                    <tr>
                        <td>Minor (1st Offense)</td>
                        <td>Verbal Warning</td>
                    </tr>
                    <tr>
                        <td>Repeated Violation</td>
                        <td>Written Warning</td>
                    </tr>
                </table>
                <div class="box-navigation">
                    <label for="tab_prohib" class="arrow-btn">◀</label>
                    <label for="tab_commit" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_commit">
            <div class="content-box">
                <h1 class="slide-header-text">Student Commitment</h1>
                <p>By using the Computer Laboratory, each student agrees to follow all guidelines. Violations will
                    be handled with firm adherence to the school's Code of Conduct.</p>
                <div class="box-navigation">
                    <label for="tab_cons" class="arrow-btn">◀ </label>
                    <label for="tab_emer1" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_emer1">
            <div class="content-box">
                <h1 class="slide-header-text">Fire Safety</h1>
                <p>Stay Calm and Alert. Cease all computer use immediately. The teacher shall turn off the main
                    breaker and lead evacuation.</p>
                <div class="box-navigation">
                    <label for="tab_commit" class="arrow-btn">◀ </label>
                    <label for="tab_emer2" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_emer2">
            <div class="content-box">
                <h1 class="slide-header-text">Earthquake Safety</h1>
                <p>Drop, Cover, and Hold. Stay away from windows and heavy equipment. Do not rush outside while the
                    ground is shaking.</p>
                <div class="box-navigation">
                    <label for="tab_emer1" class="arrow-btn">◀ </label>
                    <label for="tab_emer3" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_emer3">
            <div class="content-box">
                <h1 class="slide-header-text">Evacuation</h1>
                <p>Leave calmly. Do not bring bags or go back for belongings. Once outside, a headcount will be
                    conducted.</p>
                <div class="box-navigation">
                    <label for="tab_emer2" class="arrow-btn"> ◀</label>
                    <div></div>
                </div>
            </div>
        </div>

    </div>
</div>
</body>

</html>


aboutpage.html

<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="tle_styles.css">
</head>

<body class="about-theme">

code
Code
download
content_copy
expand_less
<header>
    <div class="header-left">
        <div class="logo"><a href="index.html"><img src="images.png" alt="Logo"></a></div>
        <div class="header-text">
            <div class="school-name">IMMACULATE HEART OF MARY COLLEGE INC.</div>
            <div class="page-name">ABOUT US</div>
        </div>
    </div>
    <div class="header-right">
        <div class="dropdown">
            <button class="pill-btn pink">FACILITIES <i class="fa-solid fa-chevron-down"></i></button>
            <div class="dropdown-content">
                <div class="sub-dropdown">
                    <a href="#" class="sub-dropbtn">COMP LAB <i class="fa-solid fa-caret-right"></i></a>
                    <div class="sub-dropdown-content">
                        <a href="complab.html">CAI Lab</a>
                        <a href="complab.html">Lower Computer Lab</a>
                        <a href="complab.html">Upper Computer Lab</a>
                    </div>
                </div>
                <div class="sub-dropdown">
                    <a href="#" class="sub-dropbtn">TLE LAB <i class="fa-solid fa-caret-right"></i></a>
                    <div class="sub-dropdown-content">
                        <a href="tle.html">TLE Laboratory</a>
                        <a href="#">HELE Laboratory</a>
                        <a href="#">IA Laboratory</a>
                    </div>
                </div>
                <div class="sub-dropdown">
                    <a href="#" class="sub-dropbtn">SCI LAB <i class="fa-solid fa-caret-right"></i></a>
                    <div class="sub-dropdown-content">
                        <a href="scilab.html">Science Laboratory</a>
                        <a href="#">Chemistry Laboratory</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="nav-dropdown">
            <a href="#" class="nav-label">ABOUT US <span>^</span></a>
            <div class="dropdown-list">
                <label for="tab_vm" class="dropdown-item">Vision & Mission</label>
                <label for="tab_purpose" class="dropdown-item">Purpose of Website</label>
                <label for="tab_gratitude" class="dropdown-item">Gratitude</label>
            </div>
        </div>
        </nav>
    </div>
</header>

<input type="radio" name="nav" id="tab_vm" checked>
<input type="radio" name="nav" id="tab_purpose">
<input type="radio" name="nav" id="tab_gratitude">

<div class="main-body">

    <div class="sidebar">
        <label for="tab_vm" class="sidebar-btn btn-vm">VISION & MISSION</label>
        <label for="tab_purpose" class="sidebar-btn btn-purpose">PURPOSE OF<br>WEBSITE</label>
        <label for="tab_gratitude" class="sidebar-btn btn-gratitude">GRATITUDE</label>
    </div>

    <div class="content-area">

        <div class="content-section" id="sec_vm">
            <div class="content-box" style="display: flex; flex-direction: column; gap: 20px; text-align: center;">
                <h1 class="slide-header-text">SCHOOL VISION & MISSION</h1>

                <div
                    style="background: rgba(0,0,139,0.3); padding: 20px; border-radius: 15px; border: 2px solid white;">
                    <h2
                        style="color: #ffcc00; text-transform: uppercase; font-size: 2rem; margin-bottom: 10px; font-weight: 900;">
                        Vision</h2>
                    <p style="font-size: 1.4rem; font-weight: bold;">IMMACULATE HEART OF MARY COLLEGE, INC. is an
                        empowering Christ-centered Vincentian learning institution.</p>
                </div>

                <div
                    style="background: rgba(0,0,139,0.3); padding: 20px; border-radius: 15px; border: 2px solid white;">
                    <h2
                        style="color: #ffcc00; text-transform: uppercase; font-size: 2rem; margin-bottom: 10px; font-weight: 900;">
                        Mission</h2>
                    <p style="font-size: 1.4rem; font-weight: bold;">We commit to engaging the community of learners
                        into inner-directed Vincentian leaders who journey with persons living in poverty situations
                        and care for God's creation.</p>
                </div>

                <div style="display: flex; gap: 20px; justify-content: center;">
                    <div
                        style="flex: 1; background: rgba(255,105,180,0.4); padding: 15px; border-radius: 10px; border: 2px solid white;">
                        <h3
                            style="color: white; font-size: 1.5rem; text-transform: uppercase; margin-bottom: 10px; font-weight: 900;">
                            Core Values</h3>
                        <ul style="list-style: none; padding: 0; font-size: 1.3rem; font-weight: bold;">
                            <li>Respect</li>
                            <li>Simplicity</li>
                            <li>Service</li>
                            <li>Vincentian Excellence</li>
                        </ul>
                    </div>
                    <div
                        style="flex: 1; background: rgba(65,105,225,0.4); padding: 15px; border-radius: 10px; border: 2px solid white;">
                        <h3
                            style="color: white; font-size: 1.5rem; text-transform: uppercase; margin-bottom: 10px; font-weight: 900;">
                            Graduate Attributes</h3>
                        <ul style="list-style: none; padding: 0; font-size: 1.3rem; font-weight: bold;">
                            <li>Christ-centered</li>
                            <li>Charitable</li>
                            <li>Competent</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="footer-nav"><a href="index.html" class="nav-link">BACK</a><label for="tab_purpose"
                    class="nav-link">NEXT</label></div>
        </div>

        <div class="content-section" id="sec_purpose">
            <div class="content-box">
                <h1 class="slide-header-text">PURPOSE OF THIS WEBSITE</h1>
                <p style="text-align: justify; line-height: 1.8; font-size: 1.6rem; font-weight: bold;">
                    We created a website for the school facilities—including the TLE, Computer, and Science
                    laboratories—to help students and visitors easily explore and understand their importance. By
                    reading and navigating our website, you can learn more about how the facilities of Immaculate
                    Heart of Mary College support our growth as learners and strengthen our unity as a school
                    community.
                </p>
                <p style="text-align: justify; line-height: 1.8; font-size: 1.6rem; font-weight: bold;">
                    These labs help us gain new experiences, discover more skills, and learn in a hands-on and
                    meaningful way. The website also makes information accessible so everyone can use the facilities
                    properly and responsibly.
                </p>
            </div>
            <div class="footer-nav"><label for="tab_vm" class="nav-link">BACK</label><label for="tab_gratitude"
                    class="nav-link">NEXT</label></div>
        </div>

        <div class="content-section" id="sec_gratitude">
            <div class="content-box">
                <h1 class="slide-header-text">GRATITUDE TOWARDS MEMBERS</h1>
                <p style="text-align: center; font-size: 2rem;">We would like to express our sincere gratitude to
                    every member of our group - Sophia Sumajit,Enrico Magbanua,Louise Padlan,Aildin Alavata and Kori
                    Pineda for giving their best throughout the creation of this website. Each member contributed
                    their hard work, time, and effort, showing true dedication from start to finish. Thank you for
                    supporting one another and combining your strengths to achieve our goals. Your teamwork reflects
                    our desire to help our school community grow and improve. This project shows how committed we
                    are to sharing knowledge and making a positive impact. Through this website, we are proud to
                    help uphold and spread the mission and vision of Immaculate Heart of Mary College.</p>
            </div>
            <div class="footer-nav"><label for="tab_purpose" class="nav-link">BACK</label><a href="index.html"
                    class="nav-link">HOME</a></div>
        </div>

    </div>
</div>
</body>

</html>


style.css

{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Arial', sans-serif;
}

body {
height: 100vh;
display: flex;
flex-direction: column;
background: url(school-bg.jpg) no-repeat center center/cover;
overflow: hidden;
}

header {
background: linear-gradient(90deg, #443bc4 0%, #ff99cc 60%, #ff99cc 100%);
height: 130px;
display: flex;
align-items: center;
justify-content: space-between;
padding: 0 30px;
box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
position: relative;
z-index: 1000;
}

.header-left {
display: flex;
align-items: center;
gap: 20px;
}

.logo {
width: 95px;
height: 95px;
background: white;
border-radius: 50%;
border: 4px solid white;
display: flex;
justify-content: center;
align-items: center;
flex-shrink: 0;
overflow: hidden;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.logo img {
width: 100%;
height: 100%;
object-fit: contain;
}

.school-info {
display: flex;
flex-direction: column;
justify-content: center;
}

.school-name {
color: white;
font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif;
font-weight: 800;
font-size: 2.2rem;
text-transform: uppercase;
letter-spacing: 1px;
text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
border-bottom: 3px solid white;
padding-bottom: 5px;
margin-bottom: 10px;
display: inline-block;
white-space: nowrap;
}

.nav-menu {
display: flex;
gap: 40px;
align-items: center;
}

.dropdown {
position: relative;
display: inline-block;
}

.dropbtn {
color: #001a4d;
font-weight: 900;
text-decoration: none;
font-size: 1.3rem;
text-transform: uppercase;
display: flex;
align-items: center;
gap: 8px;
cursor: pointer;
background: none;
border: none;
padding: 10px 0;
}

.dropdown-content {
display: none;
position: absolute;
background: linear-gradient(180deg, rgba(65, 105, 225, 0.98), rgba(138, 43, 226, 0.98));
min-width: 250px;
box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.4);
z-index: 2000;
border-radius: 0 0 10px 10px;
top: 100%;
left: 0;
}

.dropdown-content.wide {
min-width: 260px;
}

.dropdown-content a,
.sub-dropbtn {
color: white;
padding: 15px 20px;
text-decoration: none;
display: block;
font-family: 'Arial', sans-serif;
font-size: 1.1rem;
font-weight: bold;
border-bottom: 1px solid rgba(255, 255, 255, 0.2);
transition: 0.2s;
}

.dropdown-content a:hover,
.sub-dropbtn:hover {
background-color: rgba(255, 255, 255, 0.2);
padding-left: 25px;
}

.dropdown:hover .dropdown-content {
display: block;
}

.dropdown:hover .dropbtn i {
transform: rotate(180deg);
transition: 0.3s;
}

.sub-dropdown {
position: relative;
width: 100%;
}

.sub-dropbtn {
display: flex;
justify-content: space-between;
align-items: center;
cursor: pointer;
}

.sub-dropdown-content {
display: none;
position: absolute;
left: 100%;
top: 0;
min-width: 250px;
background: linear-gradient(180deg, rgba(65, 105, 225, 0.98), rgba(138, 43, 226, 0.98));
box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.4);
z-index: 3000;
border-radius: 0 10px 10px 10px;
}

.sub-dropdown:hover .sub-dropdown-content {
display: block;
}

.header-right {
display: flex;
align-items: center;
gap: 20px;
}

.main-content {
flex: 1;
display: flex;
justify-content: center;
align-items: center;
gap: 40px;
padding: 0 50px;
backdrop-filter: blur(3px);
background-color: rgba(0, 0, 0, 0.1);
z-index: 1;
}

.glass-box {
border-radius: 15px;
overflow: hidden;
box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
border: 2px solid rgba(255, 255, 255, 0.5);
height: 500px;
position: relative;
}

.carousel-container {
width: 60%;
background-color: #aaddff;
position: relative;
overflow: hidden;
}

.carousel-container input[type="radio"] {
display: none;
}

.carousel-track {
display: flex;
height: 100%;
width: 1000%;
transition: margin-left 0.6s ease-in-out;
}

.carousel-slide {
width: 100%;
height: 100%;
background-position: center center;
background-size: cover;
background-repeat: no-repeat;
}

.slide-1 {
background-image: url(1.jpg);
}

.slide-2 {
background-image: url(2.jpg);
}

.slide-3 {
background-image: url(3.jpg);
}

.slide-4 {
background-image: url(4.jpg);
}

.slide-5 {
background-image: url(5.jpg);
}

.slide-6 {
background-image: url(6.jpg);
background-size: contain;
background-color: white;
}

.slide-7 {
background-image: url(7.jpg);
}

.slide-8 {
background-image: url(8.jpg);
}

.slide-9 {
background-image: url(9.jpg);
}

.slide-10 {
background-image: url(10jpg);
}

#r1:checked~.carousel-track {
margin-left: 0;
}

#r2:checked~.carousel-track {
margin-left: -100%;
}

#r3:checked~.carousel-track {
margin-left: -200%;
}

#r4:checked~.carousel-track {
margin-left: -300%;
}

#r5:checked~.carousel-track {
margin-left: -400%;
}

#r6:checked~.carousel-track {
margin-left: -500%;
}

#r7:checked~.carousel-track {
margin-left: -600%;
}

#r8:checked~.carousel-track {
margin-left: -700%;
}

#r9:checked~.carousel-track {
margin-left: -800%;
}

#r10:checked~.carousel-track {
margin-left: -900%;
}

.arrow-label {
position: absolute;
top: 50%;
transform: translateY(-50%);
width: 60px;
height: 60px;
background: rgba(255, 255, 255, 0.7);
border-radius: 50%;
display: none;
justify-content: center;
align-items: center;
cursor: pointer;
font-size: 2rem;
color: #555;
transition: 0.3s;
z-index: 5;
}

.arrow-label:hover {
background: white;
color: black;
transform: translateY(-50%) scale(1.1);
}

.arrow-left {
left: 20px;
}

.arrow-right {
right: 20px;
}

#r1:checked~.arrows .slide1-arrow,
#r2:checked~.arrows .slide2-arrow,
#r3:checked~.arrows .slide3-arrow,
#r4:checked~.arrows .slide4-arrow,
#r5:checked~.arrows .slide5-arrow,
#r6:checked~.arrows .slide6-arrow,
#r7:checked~.arrows .slide7-arrow,
#r8:checked~.arrows .slide8-arrow,
#r9:checked~.arrows .slide9-arrow,
#r10:checked~.arrows .slide10-arrow {
display: flex;
}

.dots {
position: absolute;
bottom: 25px;
width: 100%;
display: flex;
justify-content: center;
gap: 12px;
z-index: 20;
}

.dot-label {
width: 15px;
height: 15px;
border-radius: 50%;
border: 3px solid white;
background: transparent;
cursor: pointer;
transition: 0.3s;
}

#r1:checked~.dots .d1,
#r2:checked~.dots .d2,
#r3:checked~.dots .d3,
#r4:checked~.dots .d4,
#r5:checked~.dots .d5,
#r6:checked~.dots .d6,
#r7:checked~.dots .d7,
#r8:checked~.dots .d8,
#r9:checked~.dots .d9,
#r10:checked~.dots .d10 {
background: rgba(255, 255, 255, 0.8);
transform: scale(1.3);
}

.announcement-container {
width: 35%;
background: linear-gradient(135deg, rgba(80, 70, 150, 0.6), rgba(60, 50, 180, 0.8));
display: flex;
flex-direction: column;
color: white;
}

.announcement-header {
padding: 25px;
display: flex;
align-items: center;
justify-content: space-between;
font-size: 2.2rem;
font-weight: bold;
font-family: sans-serif;
text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.announcement-icon {
font-size: 2.5rem;
transform: rotate(-20deg);
}

footer {
background: white;
padding: 20px 50px;
display: flex;
justify-content: center;
gap: 80px;
align-items: center;
border-top-left-radius: 10px;
border-top-right-radius: 10px;
box-shadow: 0 -5px 15px rgba(0, 0, 0, 0.1);
z-index: 10;
}

.contact-item {
display: flex;
align-items: center;
gap: 15px;
color: #002366;
font-weight: bold;
font-size: 1.3rem;
}

.icon-circle {
width: 50px;
height: 50px;
border-radius: 50%;
border: 3px solid #002366;
display: flex;
justify-content: center;
align-items: center;
color: #002366;
font-size: 1.5rem;
}

.contact-text {
font-family: Arial, sans-serif;
font-weight: 700;
}

@media (max-width: 1200px) {
.school-name {
font-size: 1.5rem;
}

code
Code
download
content_copy
expand_less
.main-content {
    flex-direction: column;
    padding-top: 20px;
    overflow-y: auto;
}

.carousel-container,
.announcement-container {
    width: 90%;
    height: 300px;
}

footer {
    flex-direction: column;
    gap: 10px;
}

.header-right {
    display: none;
}

}

tle.html

<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TLE Laboratory</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="tle_styles.css">
</head>

<body class="tle-theme">

code
Code
download
content_copy
expand_less
<header>
    <div class="header-left">
        <div class="logo">
            <a href="index.html"><img src="images.png" alt="Logo"></a>
        </div>
        <div class="header-text">
            <div class="school-name">IMMACULATE HEART OF MARY COLLEGE INC.</div>
            <div class="page-name">FACILITIES</div>
        </div>

        <nav class="main-nav">

</header>

<input type="radio" name="nav" id="tab_op" checked>
<input type="radio" name="nav" id="tab_intro">
<input type="radio" name="nav" id="tab_org">
<input type="radio" name="nav" id="tab_proc1">
<input type="radio" name="nav" id="tab_proc2">
<input type="radio" name="nav" id="tab_proc3">
<input type="radio" name="nav" id="tab_rules1">
<input type="radio" name="nav" id="tab_rules2">
<input type="radio" name="nav" id="tab_kitchen">
<input type="radio" name="nav" id="tab_arts">
<input type="radio" name="nav" id="tab_equip">
<input type="radio" name="nav" id="tab_emer">

<div class="main-body">
    <div class="sidebar">
        <label for="tab_op" class="sidebar-btn btn-op">OPERATION</label>
        <label for="tab_intro" class="sidebar-btn btn-intro">INTRODUCTION</label>
        <label for="tab_org" class="sidebar-btn btn-org">ORG. CHART</label>
        <label for="tab_proc1" class="sidebar-btn btn-proc">OPERATING<br>PROCEDURES</label>
        <label for="tab_rules1" class="sidebar-btn btn-rules">GEN. LABORATORY<br>RULES</label>

        <div class="safety-container">
            <div class="sidebar-title-box">SAFETY & PROPER<br>HANDLING PROCEDURE</div>
            <div class="sub-btn-row">
                <label for="tab_kitchen" class="sub-btn-box kitchen-btn">KITCHEN<br>LAB</label>
                <div class="vertical-line"></div>
                <label for="tab_arts" class="sub-btn-box arts-btn">INDUSTRIAL<br>ARTS</label>
            </div>
        </div>

        <label for="tab_equip" class="sidebar-btn btn-equip">SAFETY & PROPER<br>HANDLING EQUIPMENT</label>
        <label for="tab_emer" class="sidebar-btn btn-emer red-btn">PROPER PRECAUTION /<br>EMERGENCY
            PROCEDURE</label>
    </div>

    <div class="content-area">

        <div class="content-section" id="sec_op">
            <div class="content-box schedule-box-style">
                <h1 class="slide-header-text">OPERATION SCHEDULE</h1>
                <table class="exact-schedule-table">
                    <thead>
                        <tr>
                            <th>DAY</th>
                            <th>TIME</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>MONDAY - FRIDAY</td>
                            <td>7AM - 4PM</td>
                        </tr>
                        <tr>
                            <td>SATURDAY - SUNDAY</td>
                            <td>CLOSED</td>
                        </tr>
                    </tbody>
                </table>
                <div class="box-navigation">
                    <div></div>
                    <label for="tab_intro" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_intro">
            <div class="content-box">
                <h1 class="slide-header-text">INTRODUCTION</h1>
                <p class="intro-text">This manual outlines the essential rules, operational procedures, safety
                    guidelines, and emergency protocols for students and teachers utilizing the Kitchen Laboratory
                    and Industrial Arts Laboratory.</p>
                <div class="box-navigation">
                    <label for="tab_op" class="arrow-btn">◀ </label>
                    <label for="tab_org" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_org">
            <div class="content-box" style="display:flex; align-items:center; gap:20px;">
                <h1 class="slide-header-text">ORG. CHART</h1>
                <img src="images.png" class="org-chart-img" alt="Chart">
                <div style="text-align:left; color: #000;">
                    <p><strong>Principal:</strong> Ms. Ma. Elizabeth P. Bulaon</p>
                    <p><strong>Lab-in-charge:</strong> Mrs. Anna Vanessa R. Llarena</p>
                </div>

                <div class="box-navigation">
                    <label for="tab_intro" class="arrow-btn">◀ </label>
                    <label for="tab_proc1" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_proc1">
            <div class="content-box">
                <h1 class="slide-header-text">OPERATING PROCEDURES</h1>
                <div
                    style="display: flex; flex-direction: column; align-items: center; width: 100%; margin-top: 20px;">
                    <div
                        style="background: #f8bbd0; border: 3px solid black; padding: 15px; width: 350px; text-align: center; color: black; font-weight: bold;">
                        STUDENTS / EMPLOYEES / OTHER STAKEHOLDERS
                    </div>
                    <div style="font-size: 30px; color: #443bc4; margin: 10px 0;">▼</div>
                    <div style="display: flex; gap: 40px;">
                        <div
                            style="border: 3px solid black; background: white; width: 220px; border-radius: 10px; overflow: hidden;">
                            <div
                                style="height: 120px; background: #e1f5fe; display: flex; justify-content: center; align-items: center; font-size: 60px;">
                                👤</div>
                            <div
                                style="background: #f8bbd0; border-top: 3px solid black; padding: 15px; text-align: center; color: black; font-weight: bold;">
                                TLE TEACHER</div>
                        </div>
                        <div
                            style="border: 3px solid black; background: white; width: 220px; border-radius: 10px; overflow: hidden;">
                            <div
                                style="height: 120px; background: #e1f5fe; display: flex; justify-content: center; align-items: center; font-size: 60px;">
                                👤</div>
                            <div
                                style="background: #ce93d8; border-top: 3px solid black; padding: 15px; text-align: center; color: black; font-weight: bold;">
                                LABORATORY STAFF</div>
                        </div>
                    </div>
                </div>
                <div class="box-navigation">
                    <label for="tab_org" class="arrow-btn">◀ </label>
                    <label for="tab_proc2" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_proc2">
            <div class="content-box">
                <h1 class="slide-header-text">OPERATING PROCEDURES</h1>
                <ol class="custom-ol" start="1">
                    <li>All stakeholders can avail of the services of the laboratories with the approval of the
                        laboratory-in-charge (Laboratory staff and/or TLE Teacher in the absence of the laboratory
                        staff.)</li>
                    <li>Students must always be accompanied by their subject teachers every time they use the
                        laboratories.</li>
                    <li>All lab requisitions are channeled to the lab-in-charge through the laboratory staff in the
                        TLE laboratory.</li>
                    <li>Requisition forms 1 are located at a designated place in the HELE laboratory. It is to be
                        filled duplicate copies (student and office) and be submitted several or a day before the
                        intended use of theequipment/tools.</li>
                    <li>Failure to make requests for equipment/tools needed will deprive the individual/group to
                        perform or work an activity for the day. (BERESPONSIBLE INDIVIDUAL/GROUP)</li>
                    <li>Requested equipment/tools are released together with the studentcopy of the request form at
                        the start of their subject by the laboratory staff. Students are advice to check the items
                        written vis-à-vis with the release’s equipment/tools.</li>
                </ol>
                <div class="box-navigation">
                    <label for="tab_proc1" class="arrow-btn">◀ </label>
                    <label for="tab_proc3" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_proc3">
            <div class="content-box">
                <h1 class="slide-header-text">OPERATING PROCEDURES</h1>
                <ol class="custom-ol" start="7">
                    <li>Requested equipment other than those to be use for TLE/HELE/IA classes may be taken out by
                        the person concern after filling up the requisition in the TLE lab through the lab-in-charge
                        and may be returned right after their use.</li>
                    <li>In case of breakage, damage or lost items, student/s concern must inform the subject
                        teacher. The latter in turn should inform the laboratory staff for record purposes and
                        proper action.</li>
                    <li>Replacement of broken items is done by maintaining the same brand and quality.</li>
                    <li>An inventory is conducted at the middle and end of the school year.</li>
                </ol>
                <div class="box-navigation">
                    <label for="tab_proc2" class="arrow-btn">◀ </label>
                    <label for="tab_rules1" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_rules1">
            <div class="content-box">
                <h1 class="slide-header-text">LABORATORY RULES</h1>
                <ul class="custom-list">
                    <li><strong>Attire:</strong> Wear proper lab gear (aprons, hairnets). No loose clothes.</li>
                    <li><strong>Food/Drink:</strong> No eating or drinking in the lab area.</li>
                </ul>
                <div class="box-navigation">
                    <label for="tab_proc3" class="arrow-btn">◀ </label>
                    <label for="tab_rules2" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_rules2">
            <div class="content-box">
                <h1 class="slide-header-text">LABORATORY RULES</h1>
                <ul class="custom-list">
                    <li><strong>No Horseplay:</strong> Running and messing around is strictly forbidden.</li>
                    <li><strong>Reporting:</strong> Report any injuries or accidents immediately.</li>
                </ul>
                <div class="box-navigation">
                    <label for="tab_rules1" class="arrow-btn">◀</label>
                    <label for="tab_kitchen" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_kitchen">
            <div class="content-box">
                <h1 class="slide-header-text">KITCHEN SAFETY</h1>
                <p>Gather all tools before starting. Wash hands for 20 seconds. Clean and sanitize all counters
                    after use.</p>
                <div class="box-navigation">
                    <label for="tab_rules2" class="arrow-btn">◀ </label>
                    <label for="tab_arts" class="arrow-btn">▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_arts">
            <div class="content-box">
                <h1 class="slide-header-text">INDUSTRIAL ARTS</h1>
                <p>Use the correct tool for the job. Carry sharp tools pointing downward. Always wear safety glasses
                    with power tools.</p>
                <div class="box-navigation">
                    <label for="tab_kitchen" class="arrow-btn">◀ </label>
                    <label for="tab_equip" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_equip">
            <div class="content-box">
                <h1 class="slide-header-text">HANDLING EQUIPMENT</h1>
                <p>Keep electrical cords away from water. Unplug appliances before cleaning. Never lift a tool by
                    its cord.</p>
                <div class="box-navigation">
                    <label for="tab_arts" class="arrow-btn">◀ </label>
                    <label for="tab_emer" class="arrow-btn"> ▶</label>
                </div>
            </div>
        </div>

        <div class="content-section" id="sec_emer">
            <div class="content-box">
                <h1 class="slide-header-text">EMERGENCY PROCEDURE</h1>
                <p>Smother pan fires with a lid. Never use water on grease fires. Evacuate calmly if the fire is not
                    controlled.</p>
                <div class="box-navigation">
                    <label for="tab_equip" class="arrow-btn">◀</label>
                    <div></div>
                </div>
            </div>
        </div>

    </div>
</div>
</body>

</html>


tlestyles.css

{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Arial', sans-serif;
}

body {
height: 100vh;
display: flex;
flex-direction: column;
overflow: hidden;
background: #333;
}

input[type="radio"] {
display: none;
}

#tab_op:checked~.main-body .content-area #sec_op,
#tab_intro:checked~.main-body .content-area #sec_intro,
#tab_org:checked~.main-body .content-area #sec_org,
#tab_proc1:checked~.main-body .content-area #sec_proc1,
#tab_proc2:checked~.main-body .content-area #sec_proc2,
#tab_proc3:checked~.main-body .content-area #sec_proc3,
#tab_rules1:checked~.main-body .content-area #sec_rules1,
#tab_rules2:checked~.main-body .content-area #sec_rules2,
#tab_kitchen:checked~.main-body .content-area #sec_kitchen,
#tab_arts:checked~.main-body .content-area #sec_arts,
#tab_safety1:checked~.main-body .content-area #sec_safety1,
#tab_safety2:checked~.main-body .content-area #sec_safety2,
#tab_equip:checked~.main-body .content-area #sec_equip,
#tab_emer:checked~.main-body .content-area #sec_emer {
display: flex;
}

#tab_obj:checked~.main-body .content-area #sec_obj,
#tab_dos:checked~.main-body .content-area #sec_dos,
#tab_game:checked~.main-body .content-area #sec_game,
#tab_equip:checked~.main-body .content-area #sec_equip,
#tab_shutdown:checked~.main-body .content-area #sec_shutdown,
#tab_maint:checked~.main-body .content-area #sec_maint,
#tab_prohib:checked~.main-body .content-area #sec_prohib,
#tab_cons:checked~.main-body .content-area #sec_cons,
#tab_commit:checked~.main-body .content-area #sec_commit,
#tab_emer1:checked~.main-body .content-area #sec_emer1,
#tab_emer2:checked~.main-body .content-area #sec_emer2,
#tab_emer3:checked~.main-body .content-area #sec_emer3 {
display: flex;
}

#tab_vm:checked~.main-body .content-area #sec_vm,
#tab_purpose:checked~.main-body .content-area #sec_purpose,
#tab_gratitude:checked~.main-body .content-area #sec_gratitude {
display: flex;
}

#tab_intro:checked~.main-body .content-area #sec_intro,
#tab_rules:checked~.main-body .content-area #sec_rules,
#tab_safety:checked~.main-body .content-area #sec_safety,
#tab_equip:checked~.main-body .content-area #sec_equip,
#tab_emer:checked~.main-body .content-area #sec_emer {
display: flex;
}

#tab_op:checked~.main-body .sidebar .btn-op,
#tab_intro:checked~.main-body .sidebar .btn-intro,
#tab_org:checked~.main-body .sidebar .btn-org,
#tab_proc1:checked~.main-body .sidebar .btn-proc,
#tab_proc2:checked~.main-body .sidebar .btn-proc,
#tab_proc3:checked~.main-body .sidebar .btn-proc,
#tab_rules1:checked~.main-body .sidebar .btn-rules,
#tab_rules2:checked~.main-body .sidebar .btn-rules,
#tab_rules:checked~.main-body .sidebar .btn-rules,
#tab_kitchen:checked~.main-body .sidebar .safety-container .kitchen-btn,
#tab_arts:checked~.main-body .sidebar .safety-container .arts-btn,
#tab_safety1:checked~.main-body .sidebar .btn-safe1,
#tab_safety2:checked~.main-body .sidebar .btn-safe2,
#tab_emer:checked~.main-body .sidebar .btn-emer,
#tab_obj:checked~.main-body .sidebar .btn-obj,
#tab_dos:checked~.main-body .sidebar .btn-dos,
#tab_game:checked~.main-body .sidebar .btn-game,
#tab_equip:checked~.main-body .sidebar .btn-equip,
#tab_maint:checked~.main-body .sidebar .btn-equip,
#tab_shutdown:checked~.main-body .sidebar .btn-equip,
#tab_prohib:checked~.main-body .sidebar .btn-prohib,
#tab_cons:checked~.main-body .sidebar .btn-cons,
#tab_commit:checked~.main-body .sidebar .btn-cons,
#tab_safety:checked~.main-body .sidebar .btn-safe,
#tab_emer1:checked~.main-body .sidebar .btn-emer,
#tab_emer2:checked~.main-body .sidebar .btn-emer,
#tab_emer3:checked~.main-body .sidebar .btn-emer,
#tab_vm:checked~.main-body .sidebar .btn-vm,
#tab_purpose:checked~.main-body .sidebar .btn-purpose,
#tab_gratitude:checked~.main-body .sidebar .btn-gratitude {
background: white;
color: #333;
}

#tab_kitchen:checked~.main-body .sidebar .safety-container .sidebar-title-box,
#tab_arts:checked~.main-body .sidebar .safety-container .sidebar-title-box {
background: white;
color: #d4a5ff;
}

#tab_kitchen:checked~.main-body .sidebar .safety-container .kitchen-btn {
color: #d4a5ff;
font-weight: 900;
}

#tab_arts:checked~.main-body .sidebar .safety-container .arts-btn {
color: #d4a5ff;
font-weight: 900;
}

body.about-theme {
background: linear-gradient(135deg, #443bc4 0%, #0099ff 100%);
}

body.about-theme .sidebar {
background: linear-gradient(180deg, #000080, #4169e1);
}

body.about-theme .sidebar-btn {
border: 2px solid white;
color: white;
background: transparent;
}

body.about-theme .sidebar-btn:hover {
background: white;
color: #000080;
}

body.about-theme .pill-btn.active-page {
background: #4169e1;
border: 2px solid white;
}

body.tle-theme {
background: linear-gradient(135deg, #d4a5ff 0%, #ff99cc 100%);
}

body.tle-theme .sidebar {
background: linear-gradient(180deg, #cc66ff, #ff66b2);
}

body.tle-theme .sidebar-btn {
border: 2px solid white;
color: white;
background: transparent;
}

body.tle-theme .sidebar-btn:hover {
background: white;
color: #cc66ff;
}

body.tle-theme .pill-btn.active-page {
background: #ff3399;
border: 2px solid white;
color: white;
}

body.comp-theme {
background: linear-gradient(135deg, #a18cd1 0%, #fbc2eb 100%);
}

body.comp-theme .sidebar {
background: linear-gradient(180deg, #4b6cb7, #182848);
}

body.comp-theme .sidebar-btn {
border: 2px solid white;
color: white;
background: transparent;
}

body.comp-theme .sidebar-btn:hover {
background: white;
color: #4b6cb7;
}

body.comp-theme .pill-btn.active-page {
background: #4b6cb7;
border: 2px solid white;
color: white;
}

body.sci-theme {
background: linear-gradient(135deg, #89f7fe 0%, #66a6ff 100%);
}

body.sci-theme .sidebar {
background: linear-gradient(180deg, #00c6ff, #0072ff);
}

body.sci-theme .sidebar-btn {
border: 2px solid white;
color: white;
background: transparent;
}

body.sci-theme .sidebar-btn:hover {
background: white;
color: #0072ff;
}

body.sci-theme .pill-btn.active-page {
background: #0072ff;
border: 2px solid white;
color: white;
}

.main-nav {
display: flex;
gap: 40px;
margin-left: 50px;
}
.nav-dropdown { position: relative; }
.nav-label {
text-decoration: none;
color: #001a4d;
font-weight: 900; font-size: 1.5rem;
text-transform: uppercase; display: flex; align-items: center; gap: 8px;
}
.dropdown-list {
display: none;
position: absolute; top: 100%; left: 0; width: 240px;
background: linear-gradient(to bottom, #4d79ff, #9933ff);
border-bottom-left-radius: 15px; border-bottom-right-radius: 15px;
overflow: hidden; box-shadow: 0 8px 15px rgba(0,0,0,0.3); z-index: 2000;
}
.nav-dropdown:hover .dropdown-list { display: block; }
.dropdown-list a {
display: flex; justify-content: space-between; align-items: center;
padding: 15px 20px; color: white; text-decoration: none;
font-weight: bold; font-size: 1.1rem;
border-bottom: 1px solid rgba(255, 255, 255, 0.2);
}
.lab-item { position: relative; }
.content-popout {
display: none;
position: absolute; left: 100%; top: 0; width: 320px;
background: white; padding: 25px; border-radius: 12px;
box-shadow: 5px 5px 20px rgba(0,0,0,0.4); z-index: 2100;
}
.lab-item:hover .content-popout { display: block; }
.big-text {
color: #00008b; font-size: 24px; font-weight: 900;
margin-bottom: 12px; text-transform: uppercase;
}
.content-popout p {
color: #00008b; font-size: 14px; text-transform: none; line-height: 1.5; font-weight: bold;
}

.box-navigation {
display: flex;
justify-content: space-between;
width: 100%;
margin-top: auto;
padding-top: 40px;
}

.arrow-btn {
padding: 10px 30px;
background: rgba(255, 255, 255, 0.2);
border: 2px solid white;
border-radius: 30px;
color: white;
font-weight: 900;
font-size: 1.1rem;
cursor: pointer;
transition: 0.3s ease;
user-select: none;
}

.arrow-btn:hover {
background: white;
color: #002366;
box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

.content-box {
display: flex;
flex-direction: column;
min-height: 60vh;
}

header {
background: linear-gradient(90deg, #443bc4 0%, #ff99cc 60%, #ff99cc 100%);
height: 130px;
display: flex;
align-items: center;
justify-content: space-between;
padding: 0 30px;
box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
position: relative;
z-index: 1000;
}

.header-left {
display: flex;
align-items: center;
gap: 20px;
}

.logo {
width: 95px;
height: 95px;
background: white;
border-radius: 50%;
border: 4px solid white;
display: flex;
justify-content: center;
align-items: center;
overflow: hidden;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
flex-shrink: 0;
}

.logo a {
display: block;
width: 100%;
height: 100%;
}

.logo img {
width: 100%;
height: 100%;
object-fit: contain;
display: block;
}

.header-text {
display: flex;
flex-direction: column;
}

.school-name {
color: white;
font-weight: 800;
font-size: 2.2rem;
letter-spacing: 1px;
margin-bottom: 5px;
text-transform: uppercase;
text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
border-bottom: 3px solid white;
display: inline-block;
padding-bottom: 2px;
font-family: "Palatino Linotype", serif;
}

.page-name {
color: white;
font-family: 'Times New Roman', serif;
font-weight: bold;
font-size: 2rem;
letter-spacing: 3px;
text-transform: uppercase;
text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.header-right {
display: flex;
align-items: center;
gap: 20px;
}

.nav-pills {
display: flex;
gap: 15px;
}

.pill-btn {
border: none;
padding: 10px 25px;
border-radius: 25px;
color: #001a4d;
font-weight: 900;
text-transform: uppercase;
cursor: pointer;
font-size: 1.2rem;
display: flex;
align-items: center;
gap: 8px;
}

.pill-btn.purple {
background: transparent;
color: white;
}

.pill-btn.active-page {
background: white;
color: #001a4d;
border: 2px solid #001a4d;
}

.pill-btn.pink {
background: transparent;
color: white;
}

.dropdown {
position: relative;
}

.dropdown-content {
display: none;
position: absolute;
top: 110%;
background: white;
min-width: 200px;
box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
border-radius: 5px;
z-index: 100;
}

.dropdown-content a {
display: block;
padding: 10px;
text-decoration: none;
color: #333;
font-weight: bold;
border-bottom: 1px solid #eee;
}

.dropdown-content a:hover {
background: #f0f0f0;
}

.dropdown:hover .dropdown-content {
display: block;
}

.main-body {
flex: 1;
display: flex;
height: calc(100vh - 130px);
}

.sidebar {
width: 340px;
padding: 20px 15px;
display: flex;
flex-direction: column;
gap: 15px;
border-right: 3px solid white;
overflow: visible;
z-index: 100;
}

.sidebar-btn {
border-radius: 30px;
padding: 15px 10px;
font-weight: 800;
font-size: 1.2rem;
text-transform: uppercase;
cursor: pointer;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
text-align: center;
transition: 0.3s;
display: block;
}

.red-btn {
background: linear-gradient(90deg, #ff1493, #ff69b4);
border: 2px solid white !important;
color: white !important;
}

.safety-container {
background: white;
border-radius: 30px;
padding: 5px;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
text-align: center;
}

.sidebar-title-box {
color: #cc66ff;
font-weight: 900;
font-size: 1rem;
text-transform: uppercase;
padding: 10px 5px;
border-bottom: 2px solid #ddd;
}

.sub-btn-row {
display: flex;
justify-content: space-evenly;
align-items: center;
padding: 10px 0;
}

.sub-btn-box {
font-size: 0.9rem;
font-weight: bold;
color: #555;
cursor: pointer;
text-align: center;
width: 45%;
}

.sub-btn-box:hover {
color: #d4a5ff;
}

.vertical-line {
width: 2px;
height: 30px;
background: #cc66ff;
}

.content-area {
flex: 1;
padding: 20px 50px;
display: flex;
flex-direction: column;
align-items: center;
position: relative;
z-index: 1;
}

.content-section {
display: none;
width: 100%;
height: 100%;
animation: fadeIn 0.5s;
flex-direction: column;
justify-content: center;
}

.slide-header-text {
font-family: "Bodoni MT", serif;
font-size: 4rem;
font-weight: 900;
color: #002366;
text-transform: uppercase;
text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
letter-spacing: 4px;
margin-bottom: 10px;
text-align: center;
width: 100%;
background: none;
-webkit-text-fill-color: #002366;
}

.content-box {
display: flex;
flex-direction: column;
min-height: 60vh;
background: rgba(255, 255, 255, 0.4);
border: 4px solid white;
border-radius: 30px;
padding: 30px;

code
Code
download
content_copy
expand_less
height: auto;          
overflow-y: visible;   

color: white; 
font-size: 1.6rem; 
font-weight: bold; 
width: 95%;
text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
align-items: center;

}

.box-navigation {
display: flex;
justify-content: space-between;
width: 100%;
margin-top: auto;
padding-top: 40px;
}
.arrow-btn {
padding: 10px 30px;
background: rgba(255, 255, 255, 0.2);
border: 2px solid white;
border-radius: 30px;
color: white;
font-weight: 900;
font-size: 1.1rem;
cursor: pointer;
transition: 0.3s ease;
}
.arrow-btn:hover {
background: white;
color: #002366;
}

.schedule-box-style {
background: transparent !important;
border: none !important;
padding: 0 !important;
box-shadow: none !important;
overflow: hidden !important;
justify-content: center;
}

.exact-schedule-table {
width: 100%;
border-collapse: collapse;
border: 3px solid black;
background: rgba(255, 255, 255, 0.9);
margin: 0 auto;
}

.exact-schedule-table th,
.exact-schedule-table td {
border: 3px solid black;
padding: 20px;
text-align: center;
font-weight: 900;
font-size: 2.2rem;
text-transform: uppercase;
font-family: Arial, sans-serif;
line-height: 1.2;
}

.exact-schedule-table th {
background: linear-gradient(180deg, #1e245a, #1a1e50);
background-clip: text;
-webkit-background-clip: text;
color: transparent;
background-image: linear-gradient(to bottom, #1f4681, #1a2d57);
letter-spacing: 2px;
font-size: 3rem;
text-shadow: 2px 2px 0px rgba(255, 255, 255, 0.4);
}

.exact-schedule-table td {
color: #172c4b;
text-shadow: 1px 1px 0px rgba(255, 255, 255, 0.8);
}

.exact-schedule-table tr:nth-child(odd) {
background: rgba(255, 255, 255, 0.8);
}

.exact-schedule-table tr:nth-child(even) {
background: rgba(255, 255, 255, 0.8);
}

.footer-nav {
display: none !important;
}

.social-footer {
margin-top: 10px;
display: flex;
justify-content: center;
align-items: center;
gap: 20px;
}

.social-footer i {
font-size: 3rem;
color: #4169e1;
}

.social-footer .fa-instagram {
color: #c13584;
}

.social-text {
font-weight: bold;
font-size: 1rem;
text-align: center;
text-decoration: underline;
color: black;
}

.split-content {
display: flex;
gap: 20px;
text-align: left;
width: 100%;
justify-content: center;
}

.split-content>div {
flex: 1;
}

.sub-list {
list-style: disc;
padding-left: 20px;
font-size: 1.2rem;
}

@keyframes fadeIn {
from {
opacity: 0;
}

code
Code
download
content_copy
expand_less
to {
    opacity: 1;
}

}
