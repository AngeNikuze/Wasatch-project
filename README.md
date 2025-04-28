# Wasatch-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wasatch Academy History Timeline</title>

    <!-- TimelineJS Library -->
    <script src="https://cdn.knightlab.com/libs/timeline3/latest/js/timeline.js"></script>
    <link rel="stylesheet" href="https://cdn.knightlab.com/libs/timeline3/latest/css/timeline.css">
    
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        :root {
            --primary-color: #000000;
            --secondary-color: #990000;
            --accent-color: #ff7700;
            --text-color: #333333;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            color: var(--text-color);
        }
        
        header {
            background-color: var(--primary-color);
            color: orange;
            padding: 20px 0;
            margin-bottom: 30px;
        }
        
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        
        header p {
            margin: 10px 0 0;
            font-style: italic;
        }
        
        #timeline {
            width: 95%;
            height: 650px;
            margin: auto;
            margin-bottom: 40px;
        }
        
        .section-title {
            position: relative;
            margin: 40px 0 20px;
            padding-bottom: 10px;
            font-size: 1.8rem;
            color: var(--primary-color);
        }
        
        .section-title::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 30px auto;
            max-width: 1200px;
            padding: 0 20px;
        }
        
        .image-gallery img {
            width: 300px;
            height: 220px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .image-gallery img:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }
        
        .about-section {
            background-color: var(--accent-color);
            padding: 40px 20px;
            margin: 40px 0;
        }
        
        .about-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            line-height: 1.6;
        }
        
        footer {
            background-color: var(--primary-color);
            color: orange;
            padding: 30px 20px;
            margin-top: 40px;
        }
        
        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .footer-section {
            flex: 1;
            min-width: 250px;
            margin: 10px;
            text-align: left;
        }
        
        .footer-section h3 {
            font-size: 1.2rem;
            margin-bottom: 15px;
            padding-bottom: 5px;
            border-bottom: 2px solid var(--secondary-color);
            display: inline-block;
        }
        
        .footer-section ul {
            list-style: none;
            padding: 0;
        }
        
        .footer-section ul li {
            margin-bottom: 8px;
        }
        
        .social-icons {
            margin-top: 15px;
        }
        
        .social-icons a {
            color: white;
            margin-right: 15px;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-icons a:hover {
            color: #ccc;
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            margin-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        @media (max-width: 768px) {
            .footer-content {
                flex-direction: column;
            }
            
            .footer-section {
                margin-bottom: 20px;
            }
            
            #timeline {
                height: 500px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>WASATCH ACADEMY</h1>
        <p>A Tradition of Excellence Since 1875</p>
    </header>

    <!-- Timeline Container -->
    <h2 class="section-title">Our Rich History Timeline</h2>
    <div id="timeline"></div>

    <!-- Historical Image Gallery -->
    <h2 class="section-title">Historic Campus Images</h2>
    <div class="image-gallery">
    
   <div> <h2>Liberal hall</h2>
    <img src="liberal hall original.jpg" alt="Liberal Hall - Historic Building">
    <img src="History of Liberal Hall.jpeg" alt="Liberal Hall - Historic Building">
    <img src="LH Logo.jpg" alt="Liberal Hall - Historic Building">
    <img src="Liberal Hall5 Mid Thirties.jpg" alt="Liberal Hall - Historic Building"> 
    <img src="Liberal Hall6 June 1982.jpg" alt="Liberal Hall - Historic Building">
    <img src="Liberal Hall2.jpg" alt="Liberal Hall - Historic Building">
    <img src="Liberal Hall + main street 034.jpg" alt="Liberal Hall - Historic Building">
    <img src="DSC_5773.jpg gun and photo.jpg" alt="Liberal Hall - Historic Building">
    <img src="LH Int 1.jpg" alt="Liberal Hall - Historic Building">
    <img src="LH Int 2.jpg" alt="Liberal Hall - Historic Building">
    <img src="liberal hall 2.jpg" alt="Liberal Hall - Historic Building">

   </div>
    

    <div> <h2>Craighead </h2>
        <img src="Craighead9 1935.png" alt="Craighead">
        <img src="Craighead 1.jpg" alt="Craighead">
        <img src="Craighead 2.jpg" alt="Craighead">
        <img src="Craighead 3.jpg" alt="Craighead">
        <img src="Craighead 4.jpg" alt="Craighead">
        <img src="Craighead 5.JPG" alt="Craighead">
        <img src="Craighead 6.JPG" alt="Craighead">

    </div>
    <div>
        <h2>
            Coffe house
        </h2>
        <img src="Coffee House  Meat Market (1).jpg" alt="Coffe house">
        <img src="Coffee House (1).jpg" alt="Coffe house">
        <img src="Coffee House2 (1).jpg" alt="Coffe house">
        <img src="Int Coffee house 2.jpg" alt="Coffe house">
        <img src="Present day coffee house.JPG" alt="Coffe house">

    </div>
    <div><h2>Darlington</h2>
        <img src="Darkington.jpg" alt="Darlington">
        <img src="Darlington 2 (1).jpg" alt="Darlington">
        <img src="Darlington11 Dorm known as the Doghouse during 40s 50s.jpg" alt="Darlington">
        <img src="Darlington3.jpg" alt="Darlington">
        <img src="Darlington5 1925.jpg" alt="Darlington">
    </div>
    <div><h1> Duncan McMillan</h1>
        <p> Duncan McMillan was the founder of Wasatch Acdemy in the year of 1875</p>
    
        <img src="Young Duncan J McMillan (1).jpg" alt="school founder">
        <img src="Emily Kent Johnson McMillan  and Duncan J McMillan (1).jpg" alt="school founder"> 
        </div>
        <div> <h2>
            Other pictures
    
        </h2>
        <img src="Wasatch fall 1948.jpg" alt="Other pictures">
        <img src="class of 1950.png" alt="Other pictures">
        <img src="Copy of Infirmary 2.jpg" alt="Other pictures">
        <img src="Jensen fam.jpeg" alt="Other pictures">
        <img src="Jensen History.jpg" alt="Other pictures">

        </div>

    <!-- About Section -->
    <div class="about-section">
        <h2 class="section-title">About Wasatch Academy</h2>
        <div class="about-content">
            <p>Wasatch Academy is Utah's premier independent college preparatory boarding school, nestled in the heart of Mount Pleasant. Since 1875, we have been providing exceptional education to students from across the nation and around the world.</p>
            <p>Our commitment to academic excellence, innovative teaching methods, and holistic student development has established us as one of the leading boarding schools in the western United States.</p>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Contact Us</h3>
                <ul>
                    <li><i class="fas fa-map-marker-alt"></i> 120 South 100 West</li>
                    <li>Mount Pleasant, UT 84647</li>
                    <li><i class="fas fa-phone"></i> (435) 462-1400</li>
                    <li><i class="fas fa-envelope"></i> info@wasatchacademy.org</li>
                </ul>
            </div>
            
            <div class="footer-section">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="https://www.wasatchacademy.org/admissions" style="color: white;">Admissions</a></li>
                    <li><a href="https://www.wasatchacademy.org/academics" style="color: white;">Academics</a></li>
                    <li><a href="https://www.wasatchacademy.org/student-life" style="color: white;">Student Life</a></li>
                    <li><a href="https://www.wasatchacademy.org/athletics" style="color: white;">Athletics</a></li>
                    <li><a href="https://www.wasatchacademy.org/alumni" style="color: white;">Alumni</a></li>
                </ul>
            </div>
            
            <div class="footer-section">
                <h3>Connect With Us</h3>
                <p>Stay updated with the latest news and events from Wasatch Academy.</p>
                <div class="social-icons">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-linkedin"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
        </div>
        
        <div class="copyright">
            <p>&copy; 2025 Wasatch Academy. All Rights Reserved. By Ange NIKUZE</p>
        </div>
    </footer>

    <script>
        window.onload = function () {
            var timelineData = {
                "title": {
                    "media": {"url": "https://i.imgur.com/lQK0rA0.jpg"},
                    
                    "text": {"headline": "150 Years of Wasatch Academy", "text": "Explore our journey since our founding in 1875."}
                },
                "events": [
                    {
                        "media": {"url": "https://i.imgur.com/RWUpboV.jpg"},
                        "start_date": {"year": "1875"},
                        "text": {"headline": "School Founded", "text": "Wasatch Academy was established in 1875 by Presbyterian minister Duncan McMillan as the first non-Mormon school in Utah."}
                    },
                    {
                        "media": {"url": "https://i.imgur.com/2PoPIM4.jpg"},
                        "start_date": {"year": "1891"},
                        "text": {"headline": "Liberal Hall Built", "text": "Liberal Hall was constructed as one of the earliest buildings on campus and still stands today as a historical landmark."}
                    },
                    
                    {
                        "media": {"url": "https://i.imgur.com/8OG2b6x.jpg"},
                        "start_date": {"year": "1935"},
                        "text": {"headline": "Transition Period", "text": "The school transitioned from Presbyterian Church oversight to independent governance while maintaining its educational mission."}
                    },
                  
                    {
                        "media": {"url": "https://i.imgur.com/V1VugAt.jpg"},
                        "start_date": {"year": "1988"},
                        "text": {"headline": "Campus Expansion", "text": "Major campus renovation and expansion projects were undertaken to modernize facilities while preserving historic buildings."}
                    },
                   
                    
                    {
                        "media": {"url": "https://i.imgur.com/OqFvU3V.jpg"},
                        "start_date": {"year": "2025"},
                        "text": {"headline": "150th Anniversary", "text": "Celebrating 150 years of educational excellence and looking forward to the future of Wasatch Academy."}
                    }
                ]
            };
            new TL.Timeline("timeline", timelineData);
        };
    </script>

</body>
</html>
