# Tokyo
Tokyo CRCP final project 
<!DOCTYPE html> 
<html>
<head>
    <title>Tutorial</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" href="style1.css">
    <link rel="stylesheet" hred=" lightbox.css">
</head>
<body>
    <div class= "container">
        <div class="heading">
            <h3>Tokyo:Visualizing Authenicity</h3>
        </div>
            <nav>
                <ul>
                    <li><a href="#All">All</a></li> 
                    <li><a data-group="group1">Experiences</a></li>
                    <li><a data-group="group2">Culture</a></li>
                    <li><a data-group="group1">Family</a></li>

                </ul>
              </nav>
      
      
        <div class="box"> 
            
        <div class="dream">
            <div class="full-img" id="fullImgBox">
                <img src="img3.jpg" id="fullImg">
                <span onclick="closefullImg()">X</span>
                <div class="lightbox-caption" id="lightbox-caption"></div> 
            </div>
           
                    <img src="img3.jpg" alt="Edo Museum" onclick="openfullImg(this)">
                    <img src="img7.jpg" alt="Tokyo National Museum" onclick="openfullImg(this)">
                    <img src="img11.jpg" alt="Hasedera Temple: The most beautiful Hydrangias I have ever seen" onclick="openfullImg(this)">
                    <img src="img12.jpg" alt="Club Moussy: My first experience shopping in Japan. They have you put a bag over your head to try things on." onclick="openfullImg(this)">
                    <img src="img26.JPG" alt="#1 Best Fourtune: I got the best fortune twice, I think I'm lucky" onclick="openfullImg(this)">
                    <img src="img31.JPG" alt="Family Temple Sen Bei: We ate sen bei in the temple with my family next to priceless Buddist objects " onclick="openfullImg(this)">
                    <img src="img21.jpg" alt="Ron's Pick: Go to a small concert, make friends, and become one of the 4 listeners on spotify" onclick="openfullImg(this)">
                                        
        </div> 
        <div class="dream">
            <img src="img2.jpg" alt="Boarding Pass: Beginning" onclick="openfullImg(this)">
                 <img src="img1.jpg" alt="Kannon Coffee: My first of many observations of enduring Japanese hospitality" onclick="openfullImg(this)">
                     <img src="img10.jpg" alt="Geta from my grandmother: Walking was as much of the experiece as the museums and temples" onclick="openfullImg(this)">
                         <img src="img9.jpg" alt="Kotoku-in: A demonstration of devoute faith turned tourist attraction" onclick="openfullImg(this)">
                             <img src="img18.jpg" alt="Kinkaku-Ji; The Golden Temple" onclick="openfullImg(this)">
                                 <img src="img17.jpg" alt="Sanjūsangen: Walk amoung 1,001 Goddesses. I have never seen such a devotion to woman." onclick="openfullImg(this)">
                                    <img src="img16.jpg" alt="Todai-Ji Temple: PSA The deer will bite your ass" onclick="openfullImg(this)">
                                        <img src="img15.jpg" alt="Eating Manga: Juxtaposing the conservitive nature of Japanese values and dress lies Akihabara's Maid Cafes." onclick="openfullImg(this)">
                                            <img src="img32.JPG" alt="Engaku-Ji: The most authentic temple I visited" onclick="openfullImg(this)">
                                         
        </div>



        <div class="dream">
            <img src="img5.jpg" alt="J-Rail Pass: Nothing will make you feel like a tourist like batteling through Tokyo Station." onclick="openfullImg(this)">
                 <img src="img13.jpg" alt="Kiyomizu: Traditional souviners and a great view" onclick="openfullImg(this)">
                     <img src="img20.jpg" alt="Hello Kitty: For many the first introduction into japanese culture, for me the first aspect my friedns actually liked." onclick="openfullImg(this)">
                         <img src="img29.JPG" alt="Suica Card: Some of my favorite memories happened on the Hanzoman and Oedo Line" onclick="openfullImg(this)">
                             <img src="img28.JPG" alt="Hospital Appointment Card: The do not use anesthetic in Japan." onclick="openfullImg(this)">
                                 <img src="img27.JPG" alt="Money Envelope: I recived this from my family in Tokyo, made me feel like a born and raised Japanese girl." onclick="openfullImg(this)">
                                     <img src="img23.JPG" alt="Hair Pins: Left: A family heirloom from my grandmother Right: A gift from Tsubasa" onclick="openfullImg(this)">
                                         
        </div>

        <div class="dream">
            <img src="img4.jpg" alt="Tokyo Sky Tree: Tokyo Space Needle" onclick="openfullImg(this)">
                 <img src="img6.jpg" alt="Hamarikyu Gardens: Women in Kimonos come to take pictures in their traditional dress, unbotherred and beautiful." onclick="openfullImg(this)">
                     <img src="img8.jpg" alt="Hamarikyu Gardens" onclick="openfullImg(this)">
                        <img src="img33.JPG" alt=":/" onclick="openfullImg(this)">
                            <img src="img14.jpg" alt="DJ Bar Bridge: The Bar tenders shirt read: I understand JAP asshole" onclick="openfullImg(this)">
                                <img src="img19.jpg" alt="Adult Virus: A japanese fashion designer who knows Daniel Johnston, a reminder of our small world" onclick="openfullImg(this)">
                                    <img src="img22.jpg" alt="Mori Art Museum: the best museum I went to in Japan and one of the best contemporary art museums ive been to in my life" onclick="openfullImg(this)">
                                        <img src="img30.JPG" alt="Alley Nuts Rock Bar: Tsubasa's Bar, birth place of the drink Adios Tonight "onclick="openfullImg(this)">
                                     
        </div>

    </div>
    <div class= "btn">
        <a hred ="#"> <a>By Mari Sato</a>
    </div>
    </div>
   
    <div class="lightbox" id="lightbox">
        <span class="close-button" id="close-button">&times;</span>
        <img src="" alt="" id="lightbox-image">
        <div class="lightbox-caption" id="lightbox-caption"></div>
    </div>

    <script>

        var fullImgBox = document.getElementById("fullImgBox");
        var fullImg = document.getElementById("fullImg");
        var lightboxCaption = document.getElementById("lightbox-caption");


        function openfullImg(pic){
            fullImgBox.style.display = "flex"; 
            fullImg.src = pic.src;
            lightboxCaption.textContent = pic.alt; 
        }

        function closefullImg(){
         fullImgBox.style.display = "none";   
        }
        
    </script>

    <script src="scripts.js"></script>
    <script src="lightbox-plus-jquery.js"></script>
</div> 
</body>
</html> 
