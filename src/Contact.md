---
title: Contact
layout: base.njk
tags: navItem
---
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
   <title>Contact Form</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>   
    <link href="Style.css" rel="stylesheet" />
</head>

<body>
    <div>
            <div class="container">
                <div class="contact-parent">
                    <div class="contact-child child1">
                        <p>
                            <i class="fas fa-map-marker-alt"></i> Location <br />
                            <span> New York, New York
                                <br />
                            </span>
                        </p>
                        <p>
                            <i class="fas fa-phone-alt"></i> Let's Talk <br />
                            <span> Chantelvf@gmail.com</span>
                        </p>
                        <p>
                            <i class=" far fa-envelope"></i> Where to find me <br />
                            <span> Idle Screen Podcast 
                            <br> Youtube - LegendOfAnakin 
                            <br>Twitch - LegendofAnakin
                            </span>
                        </p>
                    </div>
                    <div class="contact-child child2">
                        <div class="inside-contact">
                            <h2>Contact Me</h2>
                            <h3>
                               <span id="confirm">
                            </h3>
                            <p>Name *</p>
                            <input id="txt_name" type="text" Required="required">
                            <p>Email *</p>
                            <input id="txt_email" type="text" Required="required">
                            <p>Phone *</p>
                            <input id="txt_phone" type="text" Required="required">
                            <p>Subject *</p>
                            <input id="txt_subject" type="text" Required="required">
                            <p>Message *</p>
                            <textarea id="txt_message" rows="4" cols="20" Required="required" ></textarea>
                            <input type="submit" id="btn_send" value="SEND">
                        </div>
                    </div>
                </div>
            </div>
        </div>
</body>
</html>