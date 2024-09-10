/* General Styles */
body {
  font-family: 'Comic Sans MS', sans-serif;
  background-color: #ffe6f7;
  margin: 0;
  padding: 0;
  text-align: center;
}

/* Container */
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background: url('hello-kitty-background.jpg') no-repeat center center;
  background-size: cover;
  border-radius: 15px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Header */
header h1 {
  font-size: 3rem;
  color: #ff69b4;
  margin-top: 20px;
}

/* Social Links */
.links {
  display: flex;
  flex-direction: column;
  margin: 20px 0;
}

.social-button {
  text-decoration: none;
  padding: 15px;
  margin: 10px;
  border-radius: 10px;
  font-size: 1.5rem;
  color: white;
  transition: background 0.3s;
}

.snapchat {
  background-color: #fffc00;
}

.instagram {
  background: linear-gradient(45deg, #fdc830, #f37335);
}

.youtube {
  background-color: #ff0000;
}

.tiktok {
  background: linear-gradient(45deg, #69c9d0, #ee1d52);
}

.social-button:hover {
  opacity: 0.8;
}

/* Email Form */
.email-form {
  margin-top: 20px;
}

.email-form input, .email-form textarea {
  width: 80%;
  padding: 10px;
  margin: 10px 0;
  border-radius: 5px;
  border: 2px solid #ff69b4;
}

.email-form button {
  background-color: #ff69b4;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.email-form button:hover {
  background-color: #ff85c2;
}

/* Responsive Design */
@media (max-width: 600px) {
  .social-button {
    font-size: 1.2rem;
  }
}
