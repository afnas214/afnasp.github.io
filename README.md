/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #2c3e50;
    color: #ecf0f1;
    line-height: 1.6;
}

/* Header Styling */
header {
    background-color: #34495e;
    padding: 40px 0;
    text-align: center;
}

header h1 {
    font-size: 3em;
    color: #ecf0f1;
    text-transform: uppercase;
}

header p {
    font-size: 1.2em;
    color: #ecf0f1;
    margin-top: 10px;
}

/* About Section */
.about {
    padding: 30px;
    text-align: center;
}

.about h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.about p {
    font-size: 1.2em;
    color: #ecf0f1;
    max-width: 800px;
    margin: 0 auto;
}

/* Social Media Buttons */
.social {
    padding: 30px;
    text-align: center;
}

.social-buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.social-btn {
    font-size: 1.2em;
    padding: 15px 30px;
    border-radius: 5px;
    text-decoration: none;
    color: #ecf0f1;
    transition: background-color 0.3s, transform 0.3s;
}

.instagram {
    background: linear-gradient(135deg, #f8a5c2, #f9b7c3);
}

.linkedin {
    background: linear-gradient(135deg, #3498db, #9b59b6);
}

.social-btn:hover {
    transform: scale(1.1);
    background-color: #e74c3c;
}

/* Footer */
footer {
    background-color: #34495e;
    text-align: center;
    padding: 20px 0;
}

footer p {
    color: #ecf0f1;
    font-size: 1em;
}
