HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="profile-card">
        <div class="profile-img">
            <img src="file:///C:/Users/Abdul%20Basit/Downloads/asmatullah/WhatsApp%20Image%202026-02-02%20at%201.39.42%20PM.jpeg" alt="Profile Image">
        </div>

        <h2>Rehan Ali</h2>
        <p class="designation">Web Developer</p>

        <p class="bio">
            Passionate about creating clean and user-friendly websites using HTML & CSS.
        </p>

        <div class="social-icons">
            <a href="#">F</a>
            <a href="#">T</a>
            <a href="#">I</a>
            <a href="#">L</a>
        </div>

        <button class="btn">View Profile</button>
    </div>

</body>
</html>


CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", sans-serif;
}

body {
    height: 100vh;
    background:#00509b;
    display: flex;
    justify-content: center;
    align-items: center;
}

.profile-card {
    background: #ffffff;
    width: 300px;
    padding: 25px;
    border-radius: 15px;
    text-align:center;
    box-shadow: 0 15px 30px rgba(0,0,0,0.25);
}

.profile-img img {
    object-fit: cover;
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 4px solid #66eabe;
    margin-bottom: 15px;
}

.profile-card h2 {
    color: #333;
    margin-bottom: 5px;
}

.designation {
    color: #a8b8ff;
    font-size: 14px;
    margin-bottom: 10px;
}

.bio {
    font-size: 14px;
    color: #555;
    margin-bottom: 15px;
}

.social-icons {
    margin-bottom: 15px;
}

.social-icons a {
    display: inline-block;
    width: 35px;
    height: 35px;
    line-height: 35px;
    margin: 0 5px;
    border-radius: 50%;
    background: #667eea;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.social-icons a:hover {
    background: #00509b;
}

.btn {
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 25px;
    background: linear-gradient(135deg, #05186e, #60accf);
    color: #fff;
    font-size: 15px;
    cursor: pointer;
}

.btn:hover {
    opacity: 0.9;
}




