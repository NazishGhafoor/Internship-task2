<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute to Imran Khan - Leader & Visionary</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            background-attachment: fixed;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                        url('https://th.bing.com/th/id/R.614a955d5a7b916edaa96aa5baa87026?rik=c9%2fQ3CB4RRIKmw&riu=http%3a%2f%2fimg.xcitefun.net%2fusers%2f2011%2f11%2f272877%2cxcitefun-imran-khan-pti-wallpaper-6.jpg&ehk=E5Kn6FHeTHHHWgP9cwIN5q0G0X05q%2f5gjilqpRl9sQs%3d&risl=&pid=ImgRaw&r=0');
            background-size: cover;
            background-position: center;
            color: white;
            border-radius: 10px;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(30, 60, 114, 0.5);
            z-index: 1;
        }
        
        header > * {
            position: relative;
            z-index: 2;
        }
        
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .subtitle {
            font-size: 1.5rem;
            font-weight: 300;
            margin-bottom: 20px;
        }
        
        .dates {
            font-size: 1.2rem;
            font-style: italic;
            margin-bottom: 30px;
        }
        
        .quote {
            font-style: italic;
            font-size: 1.3rem;
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            border-left: 4px solid #e74c3c;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 0 10px 10px 0;
        }
        
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .main-content {
            flex: 2;
            min-width: 300px;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .sidebar {
            flex: 1;
            min-width: 250px;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        h2 {
            font-family: 'Playfair Display', serif;
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #eaecef;
        }
        
        h3 {
            font-family: 'Playfair Display', serif;
            color: #1e3c72;
            margin: 25px 0 15px;
        }
        
        p {
            margin-bottom: 20px;
            font-size: 1.1rem;
        }
        
        .image-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .gallery-item {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .gallery-item:hover {
            transform: translateY(-5px);
        }
        
        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            display: block;
        }
        
        .caption {
            padding: 15px;
            background: white;
            font-size: 0.9rem;
            color: #666;
        }
        
        .timeline {
            margin: 30px 0;
        }
        
        .timeline-item {
            margin-bottom: 25px;
            padding-left: 20px;
            border-left: 3px solid #1e3c72;
            position: relative;
        }
        
        .timeline-item::before {
            content: "";
            position: absolute;
            left: -8px;
            top: 0;
            width: 14px;
            height: 14px;
            border-radius: 50%;
            background: #1e3c72;
        }
        
        .timeline-year {
            font-weight: bold;
            color: #1e3c72;
            margin-bottom: 5px;
        }
        
        .achievements {
            list-style-type: none;
        }
        
        .achievements li {
            margin-bottom: 15px;
            padding-left: 20px;
            position: relative;
        }
        
        .achievements li:before {
            content: "★";
            color: #e74c3c;
            position: absolute;
            left: 0;
        }
        
        .political-journey {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin: 25px 0;
        }
        
        .political-journey h3 {
            color: #e74c3c;
        }
        
        footer {
            text-align: center;
            padding: 30px;
            background: #2c3e50;
            color: white;
            border-radius: 10px;
            margin-top: 40px;
        }
        
        .footer-quote {
            font-style: italic;
            margin-top: 15px;
            font-size: 1.1rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: #e74c3c;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .content {
                flex-direction: column;
            }
            
            .image-gallery {
                grid-template-columns: 1fr;
            }
        }
        
        .highlight {
            background: linear-gradient(120deg, #f6d365 0%, #fda085 100%);
            padding: 2px 5px;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Imran Khan</h1>
            <p class="subtitle">Cricket Legend, Philanthropist, and Prime Minister</p>
            <p class="dates">Born: October 5, 1952</p>
            <div class="quote">
                "The more you study, the more you know; how less you know."
            </div>
        </header>
        
        <div class="content">
            <div class="main-content">
                <h2>Life and Legacy</h2>
                
                <p>Imran Khan Niazi is a Pakistani politician, former cricketer, and philanthropist who served as the 22nd Prime Minister of Pakistan from August 2018 until April 2022. He is the founder and chairman of the political party Pakistan Tehreek-e-Insaf (PTI).</p>
                
                <h3>Early Life and Cricket Career</h3>
                <p>Born in Lahore to a Pashtun family, Imran Khan graduated from Keble College, Oxford in 1975. He began his international cricket career at age 18, in a 1971 Test series against England. Khan played until 1992, serving as the captain of the Pakistani national team from 1982. Under his leadership, Pakistan won the <span class="highlight">1992 Cricket World Cup</span>, the country's first and only victory in the competition.</p>
                
                <h3>Philanthropy and Social Work</h3>
                <p>After retiring from cricket, Khan focused on philanthropy and established the <span class="highlight">Shaukat Khanum Memorial Cancer Hospital & Research Centre</span> in Lahore in 1994, named after his mother who died of cancer. In 2005, he founded <span class="highlight">Namal College</span> in Mianwali, providing higher education opportunities in a remote area of Pakistan.</p>
                
                <div class="image-gallery">
                    <div class="gallery-item">
                        <img src="https://tse1.mm.bing.net/th/id/OIP.dLJwwINk6Pim96kUWT-m8gHaEO?cb=ucfimgc2&w=1200&h=686&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Young Imran Khan as a cricketer">
                        <div class="caption">Young Imran Khan as a cricketer in 1975</div>
                    </div>
                    <div class="gallery-item">
                        <img src="https://staticg.sportskeeda.com/editor/2019/01/1963d-15467567628494-800.jpg" alt="Imran Khan lifting the 1992 World Cup">
                        <div class="caption">Imran Khan lifting the 1992 Cricket World Cup</div>
                    </div>
                    <div class="gallery-item">
                        <img src="https://tse4.mm.bing.net/th/id/OIP.N2KTfADuANt3-nB56LNvQAHaGp?cb=ucfimgc2&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Shaukat Khanum Hospital">
                        <div class="caption">Shaukat Khanum Memorial Cancer Hospital</div>
                    </div>
                </div>
                
                <div class="political-journey">
                    <h3>Political Journey</h3>
                    <p>Imran Khan entered politics in 1996, founding Pakistan Tehreek-e-Insaf (PTI). For over a decade, the party remained on the political fringe. However, following the 2013 general election, PTI became the second-largest party in Pakistan by vote share. In the <span class="highlight">2018 general election</span>, PTI became the largest party in the National Assembly and Khan was elected as the 22nd Prime Minister of Pakistan.</p>
                    
                    <p>During his tenure, Khan focused on implementing an Islamic welfare state, fighting corruption, and improving relations with neighboring countries. His government also initiated the <span class="highlight">Ehsaas Program</span>, one of the largest social safety nets in Pakistan's history.</p>
                </div>
                
                <h3>Legacy and Impact</h3>
                <p>Imran Khan remains one of the most influential and popular figures in Pakistan. His journey from cricket superstar to political leader has inspired millions. Despite political challenges, he continues to be a prominent voice in Pakistani politics and an advocate for justice, anti-corruption, and Islamic welfare principles.</p>
                
                <div class="timeline">
                    <h3>Key Events in His Life</h3>
                    <div class="timeline-item">
                        <div class="timeline-year">1952</div>
                        <div class="timeline-desc">Born in Lahore, Pakistan</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">1971</div>
                        <div class="timeline-desc">Made international cricket debut for Pakistan</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">1982</div>
                        <div class="timeline-desc">Became captain of the Pakistan cricket team</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">1992</div>
                        <div class="timeline-desc">Led Pakistan to Cricket World Cup victory</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">1994</div>
                        <div class="timeline-desc">Established Shaukat Khanum Memorial Cancer Hospital</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">1996</div>
                        <div class="timeline-desc">Founded Pakistan Tehreek-e-Insaf (PTI)</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2018</div>
                        <div class="timeline-desc">Elected as 22nd Prime Minister of Pakistan</div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-year">2022</div>
                        <div class="timeline-desc">Voted out as Prime Minister through no-confidence motion</div>
                    </div>
                </div>
            </div>
            
            <div class="sidebar">
                <h2>Key Facts</h2>
                
                <h3>Cricket Achievements</h3>
                <ul class="achievements">
                    <li><strong>World Cup Victory</strong><br>Captained Pakistan to 1992 Cricket World Cup win</li>
                    <li><strong>Test Career</strong><br>Scored 3,807 runs and took 362 wickets in Test cricket</li>
                    <li><strong>ODI Career</strong><br>Scored 3,709 runs and took 182 wickets in ODIs</li>
                    <li><strong>Wisden Cricketer</strong><br>Named one of Wisden's Cricketers of the Year in 1983</li>
                </ul>
                
                <h3>Political Milestones</h3>
                <ul class="achievements">
                    <li>Founded Pakistan Tehreek-e-Insaf in 1996</li>
                    <li>Elected to Parliament in 2002</li>
                    <li>Led PTI to victory in 2018 general elections</li>
                    <li>Served as Prime Minister from 2018 to 2022</li>
                </ul>
                
                <h3>Philanthropic Work</h3>
                <ul class="achievements">
                    <li>Shaukat Khanum Memorial Cancer Hospital</li>
                    <li>Namal College in Mianwali</li>
                    <li>Ehsaas Program for social welfare</li>
                    <li>Cancer treatment for underprivileged</li>
                </ul>
                
                <h3>Awards and Honors</h3>
                <ul class="achievements">
                    <li>Hilal-e-Imtiaz (1992)</li>
                    <li>BBC Overseas Sports Personality of the Year (1992)</li>
                    <li>UN Environment Program Laureate (1992)</li>
                    <li>Man of the Match in 1992 World Cup Final</li>
                </ul>
                
                <h3>Personal Life</h3>
                <p>Imran Khan has been married three times and has two sons. He is known for his charismatic personality, strong principles, and dedication to his vision of a corruption-free Pakistan based on Islamic welfare principles.</p>
                
                <h3>Published Works</h3>
                <ul class="achievements">
                    <li>Pakistan: A Personal History (2011)</li>
                    <li>Indus Journey: A Personal View of Pakistan (1990)</li>
                    <li>Warrior Race: A Journey Through the Land of the Tribal Pathans (1993)</li>
                </ul>
            </div>
        </div>
        
        <footer>
            <p>"I have always believed that one should not be frightened of dying, if one has achieved what one wanted to achieve." - Imran Khan</p>
            <p class="footer-quote">A tribute to a man who transformed from a sports icon to a political force</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
        </footer>
    </div>
</body>
</html>
