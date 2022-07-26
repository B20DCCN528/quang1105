Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@quang1105 
quang1105
/
quang1105
Public
Code
Pull requests
Actions
Projects
Security
Insights
Settings
quang1105/Band.html
@quang1105
quang1105 Add files via upload
Latest commit 01a37f3 21 minutes ago
 History
 1 contributor
255 lines (229 sloc)  11.7 KB

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Band</title>
    <link href="https://fullstack.edu.vn/favicon/favicon_32x32.png" rel="icon" type="image/x-icon" />
    <link rel="stylesheet" href="Band.css">
    <link rel="stylesheet" href="themify-icons/themify-icons.css">
</head>
<body>
    <div id="wrapper">
        <div id="header">
            <ul id="nav">
                <li><a href="#">Home</a></li>
                <li><a href="#band">Band</a></li>
                <li><a href="#tour">Tour</a></li>
                <li><a href="#contact">Contact</a></li>
                <li>
                    <a href="#">
                        More
                        <i class="nav-arrow-down ti-angle-down"></i>
                    </a>
                    <ul class="subnav">
                        <li><a href="#">Merchandise</a></li>
                        <li><a href="#">Extras</a></li>
                        <li><a href="#">Media</a></li>
                    </ul>
                </li>
            </ul>

            <div class="search-btn">
                <i class="search-icon ti-search"></i>
            </div>

            <div id="mobile-menu" class="mobile-menu-btn">
                <i class="menu-icon ti-menu"></i>
            </div>
        </div>

        <div id="slider">
            <div class="text-content">
                <h2 class="text-heading">
                    New York
                </h2>
                <div class="text-description">The apmosphere in New York is lorem ipsum.</div>
            </div>
        </div>

        <div id="content">
            <div id="band" class="content-section">
                <h2 class="section-heading">THE BAND</h2>
                <p class="section-subheading">We love Music</p>
                <p class="about-text">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                <div class="row members-list">
                    <div class="col col-third text-center">
                        <p class="member-name">Name</p>
                        <img src="/images/bandmember.jpg" alt="Name" class="member-img">
                    </div>

                    <div class="col col-third text-center">
                        <p class="member-name">Name</p>
                        <img src="/images/bandmember.jpg" alt="Name" class="member-img">
                    </div>

                    <div class="col col-third text-center">
                        <p class="member-name">Name</p>
                        <img src="/images/bandmember.jpg" alt="Name" class="member-img">
                    </div>
                </div>
            </div>
            
            <div id="tour" class="tour-section">
                <div class="content-section">
                    <h2 class="section-heading text-white">TOUR DATES</h2>
                    <p class="section-subheading text-white">Remember </p>
                    <ul class="tickets-list">
                        <li>Septemper <span class="sold-out">Sold out</span></li>
                        <li>October <span class="sold-out">Sold out</span></li>
                        <li>November <span class="quantity">3</span></li>
                    </ul>

                    <div class="row place-list">
                        <div class="col col col-third">
                             <img src="/images/newyork.jpg" alt="" class="place-img">
                            <div class="place-body">
                                <h3 class="place-heading">New York</h3>
                                <p class="play-time">Fri 27 Nov 2016</p>
                                <p class="place-description">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                                <button class=" btn place-buy-btn js-buy-ticket">Buy Tickets</button>
                            </div>
                        </div>

                        <div class="col col-third">
                            <img src="/images/paris.jpg" alt="" class="place-img">
                            <div class="place-body">
                                <h3 class="place-heading">Paris</h3>
                                <p class="play-time">Sat 28 Nov 2016</p>
                                <p class="place-description">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                                <button class=" btn place-buy-btn js-buy-ticket">Buy Tickets</button>
                            </div>
                        </div>

                        <div class="col col-third">
                            <img src="/images/sanfran.jpg" alt="" class="place-img">
                            <div class="place-body">
                                <h3 class="place-heading">San Fransico</h3>
                                <p class="play-time">Sun 29 Nov 2016</p>
                                <p class="place-description">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                                <button class=" btn place-buy-btn js-buy-ticket">Buy Tickets</button>
                            
                            </div>
                        
                        </div>

                        <div class="clear"></div>
                    </div>
                </div>
            </div>

            <div id="contact" class="content-section">
                <h2 class="section-heading">CONTACT</h2>
                <p class="section-subheading">Fan? Drop a note!</p>
                <div class="row contact-content">
                    <div class="col col-half contact-info">
                        <p><i class="ti-location-pin"></i>Chicago, US</p>
                        <p><i class="ti-mobile"></i>Phone: ++00 151515</p>
                        <p><i class="ti-email"></i>Email: lazymoon2k2@gmail.com</p>
                    </div>
                    <div class="col col-half contact-form">
                        <form action="">
                            <div class="row">
                                <div class="col col-half">
                                    <input type="text" name="" class = "form-coltrol" required id="" placeholder="Name">
                                </div>
                                <div class="col col-half">
                                    <input type="email" name="" class = "form-coltrol" required id="" placeholder="Email">
                                </div>
                            </div>
                            <div class="row mt-8">
                                <div class="col col-full">
                                    <input type="text" name="" class = "form-coltrol" required id="" placeholder="Messengers">
                                </div>
                            </div>
                            <input class = "place-buy-btn pull-right mt-16" type="submit" value="SEND">
                        </form>
                    </div>
                </div>
                
            </div>
            <div class="map-section">
                <img src="/images/map.jpg" alt="map">
            </div>

        </div>

        <div id="footer">
            <div class="social-list">
                <a href=""><i class = "ti-facebook"></i></a>
                <a href=""><i class = "ti-instagram"></i></a>
                <a href=""><i class = "ti-youtube"></i></a>
                <a href=""><i class = "ti-pinterest"></i></a>
                <a href=""><i class = "ti-twitter"></i></a>
                <a href=""><i class = "ti-linkedin"></i></a>
            </div>
            <p class = "copyright"> Powered by <a href="">w3.css</a></p>
        </div>
    </div>
    <div class="modal js-modal">
        <div class="modal-container js-modal-container">
            <div class="modal-close js-modal-close">
                <i class="ti-close"></i>
            </div>
            <header class="modal-header">
                <i class="modal-heading-icon ti-bag"></i>
                Tickets
            </header>

            <div class="modal-body">
                <label for="ticket-quantity" class="modal-label">
                    <i class="ti-shopping-cart"></i>
                    Tickets, $15 per person
                </label>
                <input id="ticket-quantity" type="text" class="modal-input" placeholder="How many?">
            
                <label for="ticket-email" class="modal-label">
                    <i class="ti-user"></i>
                    Send to
                </label>
                
                <input id="ticket-email" type="email" class="modal-input" placeholder="Enter email">
                
                <button id="buy-tickets">
                    Pay 
                    <i class="ti-check"></i>
                </button>
            </div>

            <footer class="modal-footer">
                <p class="modal-help">Need <a href="#">help?</a></p>
            </footer>
        </div>
    </div>

    <script>
        const buyBtns = document.querySelectorAll('.js-buy-ticket')
        const modal = document.querySelector('.js-modal')
        const modalClose = document.querySelector('.js-modal-close')
        const modalContainer = document.querySelector('.js-modal-container')
        // hàm hiển thị mua vé (thêm class open vào modal)
        function showBuyTickets() {
            modal.classList.add('open')

        }
        // hàm ẩn modal mua vé (gỡ bỏ class open của modal)
        function hideBuyTickets() {
            modal.classList.remove('open')

        }
        // lặp qua từng thẻ button và nghe hành vi click
        for(const buyBtn of buyBtns) {
            buyBtn.addEventListener('click', showBuyTickets)
        }
        // nghe hành vi click vào button close
        modalClose.addEventListener('click', hideBuyTickets)
        modal.addEventListener('click', hideBuyTickets)
        modalContainer.addEventListener('click', function (event) {
            event.stopPropagation()
        })

        var header = document.getElementById('header');
        var mobileMenu = document.getElementById('mobile-menu');
        var headerHeight = header.clientHeight;
        // đóng mở mobile menu
        mobileMenu.onclick = function() {
            var isClose = header.clientHeight === headerHeight;
            if(isClose) {
                header.style.height = 'auto';
            }
            else {
                header.style.height = null;
            }
        }
        //  tự động đóng khi chọn menu
        var menuItems = document.querySelectorAll('#nav li a[href*="#"]');
        for(var i = 0; i < menuItems.length; i++) {
            var menuItem = menuItems[i];
            menuItem.onclick = function() {
                header.style.height = null;
            }
        }
    </script>
</body>
</html>
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
You have no unread notifications
1
