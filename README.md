<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation Beast</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #444;
            color: white;
            padding: 10px 20px;
            text-align: center;
            position: relative;
        }
        header button {
            position: absolute;
            top: 10px;
            right: 20px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        header button:hover {
            background-color: #0056b3;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #444;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .content {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .link-section {
            text-align: center;
            margin: 20px 0;
        }
        .link-section a {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
        }
        .link-section a:hover {
            background-color: #0056b3;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        .why-section, .dream-section, .ideas-section {
            margin-top: 40px;
            padding: 20px;
            background-color: #E3F2FD;
            border-radius: 8px;
            text-align: center;
        }
        .contact-section {
            text-align: center;
            margin-top: 40px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #444;
            color: white;
            margin-top: 20px;
        }
        /* Styling for the form */
        form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #0056b3;
        }
        .idea-card {
            border: 1px solid #ddd;
            padding: 10px;
            margin-top: 20px;
            text-align: center;
            background-color: #fff;
            border-radius: 8px;
        }
        .idea-card img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Animation Beast</h1>
        <p>Your hub for epic stop-motion animation and action figures!</p>
        <!-- Sign Up Button -->
        <a href="https://accounts.google.com/o/oauth2/auth/oauthchooseaccount?redirect_uri=storagerelay%3A%2F%2Fhttps%2Fsignup.com%3Fid%3Dauth125173&response_type=permission%20id_token&scope=email%20profile%20openid&openid.realm&include_granted_scopes=true&client_id=169255260842-ojsa3235vuqlbljrugns4k6q5mkvf0dc.apps.googleusercontent.com&ss_domain=https%3A%2F%2Fsignup.com&fetch_basic_profile=true&gsiwebsdk=2&service=lso&o2v=1&ddm=1&flowName=GeneralOAuthFlow" target="_blank">
            <button>Sign Up</button>
        </a>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#link">My Channel</a>
        <a href="#why">Why I Made This</a>
        <a href="#dream">My Dream</a>
        <a href="#ideas">Send Ideas</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="content" id="home">
        <h2>Welcome to Animation Beast!</h2>
        <p>Discover stunning stop-motion animations and action figure collections. Dive into a world of creativity and epic battles brought to life through animation.</p>
    </div>

    <div class="content link-section" id="link">
        <h2>Check Out My YouTube Channel</h2>
        <a href="https://www.youtube.com/@The_stop-motion_MAN" target="_blank">Visit Animation Beast on YouTube</a>
    </div>

    <div class="content" id="gallery">
        <h2>Action Figure Gallery</h2>
        <div class="gallery">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_hUOv2fR3Pj29sjYhWeMeZVxNLoUdpI63euhrjntYTy55Nboa6HTd6XKtgPVjiwHM254&usqp=CAU" alt="Action Figure 1">
            <img src="https://m.media-amazon.com/images/I/71Hc7uqVhIL._AC_UF894,1000_QL80_.jpg" alt="Action Figure 2">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbnBYyof6CVtyINQ2F_XhfWjMnJQdF0_m_BQ&s" alt="Action Figure 3">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRzeDQjBjpT9cCRgXndWuFwn74hY92fPSvS0g&s" alt="Action Figure 4">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRngWqQzMUZGcvtIqdZDe_qTw2Reb4pCIdIPQ&s" alt="Action Figure 5">
        </div>
    </div>

    <div class="content why-section" id="why">
        <h2>Why I Made This Account</h2>
        <p>I created this stop-motion account to share my passion for storytelling and animation. Stop-motion allows me to bring action figures to life, creating epic battles and unique narratives. It's a blend of creativity, patience, and imagination that I love to share with others. Join me on this journey!</p>
        <p>Created by: The_Stop-Motion_Man</p>
    </div>

    <div class="content dream-section" id="dream">
        <h2>My Dream</h2>
        <p>It has always been my dream to bring my own creations to life through stop-motion animation. Every click of the camera and every frame is a step closer to making that dream a reality. But I can't do it without your support!</p>
        <p>If you love the animations, the stories, and the action, please consider subscribing to my YouTube channel. Your support helps me make more incredible animations and continue chasing my dream.</p>
        <p>Thank you for being a part of this journey!</p>
        <p><strong>Dream Big, Animate Bigger!</strong></p>
    </div>

    <div class="content ideas-section" id="ideas">
        <h2>Share Your Animation Ideas!</h2>
        <p>Upload an image and describe your idea for a new animation! Let's create something amazing together.</p>
        
        <!-- Idea Submission Form -->
        <form id="ideaForm">
            <input type="text" id="name" placeholder="Your Name" required>
            <textarea id="idea" placeholder="Describe Your Idea" rows="4" required></textarea>
            <input type="file" id="image" accept="image/*" required>
            <button type="submit">Submit Your Idea</button>
        </form>

        <div id="ideaContainer"></div>
    </div>

    <div class="content contact-section" id="contact">
        <h2>Contact Me</h2>
        <p>If you need anything, feel free to reach out!</p>
        <p><strong>Phone: 974 66338896</strong></p>
    </div>

    <footer>
        <p>&copy; 2024 Animation Beast. All Rights Reserved.</p>
    </footer>

    <script>
        // Handle form submission and display idea with image
        document.getElementById('ideaForm').addEventListener('submit', function(e) {
            e.preventDefault();

            const name = document.getElementById('name').value;
            const idea = document.getElementById('idea').value;
            const image = document.getElementById('image').files[0];

            if (name && idea && image) {
                const reader = new FileReader();

                reader.onload = function(event) {
                    const imgSrc = event.target.result;

                    const ideaCard = document.createElement('div');
                    ideaCard.classList.add('idea-card');

                    const img = document.createElement('img');
                    img.src = imgSrc;

                    const ideaText = document.createElement('p');
                    ideaText.textContent = idea;

                    const author = document.createElement('p');
                    author.textContent = `By: ${name}`;

                    ideaCard.appendChild(img);
                    ideaCard.appendChild(ideaText);
                    ideaCard.appendChild(author);

                    document.getElementById('ideaContainer').appendChild(ideaCard);

                    // Clear the form after submission
                    document.getElementById('ideaForm').reset();
                };

                reader.readAsDataURL(image);
            } else {
                alert('Please fill in all fields and select an image.');
            }
        });
    </script>
</body>
</html>
