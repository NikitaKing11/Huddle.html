# Huddle.html
<div class="main-container">
    <header class="header">
     <img src="https://res.cloudinary.com/pandaa/image/upload/v1562494430/Frontend%20Mentor/Huddle%20Landing%20Page/logo.svg" alt="Huddle Logo">
    </header>
    <main class="main">
     <section class="image-section">
      <img src="https://res.cloudinary.com/pandaa/image/upload/v1562494430/Frontend%20Mentor/Huddle%20Landing%20Page/illustration-mockups.svg" alt="Illustration-mockups">
     </section>
     <section class="text-content">
      <h1 class="title">Build The Community Your Fans Will Love</h1>
      <p class="description">Huddle re-imagines the way we build communities. You have a voice, but so does your audience.
       Create connections with your users as you engage in genuine discussion.</p>
      <button class="register-button">
       Register
      </button>
     </section>
    </main>
    <footer class="footer">
     <a href="https://github.com/pandaa880" target="_blank" class="social-icon facebook"><i class="fab fa-facebook-f" aria-label="Follow us on Facebook"></i></a>
     <a href="https://github.com/pandaa880" target="_blank" class="social-icon twitter"><i class="fab fa-twitter" aria-label="Follow us on Twitter"></i></a>
     <a href="https://github.com/pandaa880" target="_blank" class="social-icon instagram"><i class="fab fa-instagram" aria-label="Follow us on Instagram"></i></a>
    </footer>
   </div>
   <style>@import url('https://fonts.googleapis.com/css?family=Open+Sans|Poppins:400,700&display=swap');

    *, *::before, *::after {
      box-sizing: border-box;
    }
    
    :root {
      --primary-color: hsl(257, 40%, 49%);
      --primary-white: #fff;
      --font-family-one: 'Open Sans', sans-serif;
      --font-family-two: 'Poppins', sans-serif;
    }
    
    body {
      padding: 0;
      margin: 0;
      height: 100%;
      overflow: scroll;
      background-color: var(--primary-color);
    }
    
    .header {
      padding: 5% 10%;
      position: absolute;
      top: 0;
      left: 0;
    }
    
    .header img {
      width: 50%;
      height: auto;
    }
    
    .main {
      /* margin-top: 70px; */
      /* min-height: 100vh; */
      padding-top: 25%;
      background-image: url("https://res.cloudinary.com/pandaa/image/upload/v1562494430/Frontend%20Mentor/Huddle%20Landing%20Page/bg-mobile.svg");
      background-size: 100% 55%;
      background-position: top;
      background-repeat: no-repeat;
      background-attachment: scroll;
      background-origin: border-box;
    }
    
    .image-section {
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    
    .image-section img {
      width: 80%;
      height: auto;
    }
    
    .text-content {
      margin-top: 15%;
      padding: 5% 10%;
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    
    .title {
      margin: 0.5rem 0;
      font-size: 1.5rem;
      color: var(--primary-white);
      line-height: 1.5;
      letter-spacing: 1px;
      font-family: var(--font-family-two);
    }
    
    .description {
      margin: 0.5rem 0 1rem 0;
      font-size: 1rem;
      color: var(--primary-white);
      line-height: 1.5;
      font-family: var(--font-family-one); 
    }
    
    .register-button {
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      border: 1px solid var(--primary-white);
      border-radius: 20px;
      width: 70%;
      max-width: 200px;
      font-size: 1.1rem;
      background-color: var(--primary-white);
      color: var(--primary-color);
    }
    
    .footer {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    
    .social-icon {
      display: block;
      margin: 2rem 0.5rem;
      width: 30px;
      height: 30px;
      border:1px solid var(--primary-white);
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      color: var(--primary-white);
      cursor: pointer;
    }
    
    /* Media Queries */
    
    @media(min-width: 1024px) {
    
      .main-container {
        height: 100vh;
        background: url('https://res.cloudinary.com/pandaa/image/upload/v1562494430/Frontend%20Mentor/Huddle%20Landing%20Page/bg-desktop.svg'), var(--primary-color);
        background-size: cover;
        background-position: left;
        background-repeat: no-repeat;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
      }
    
      .header {
        padding: 2% 5%;
      }
    
      .main {
        margin-top: 15%;
        padding: 0 5%;
        background: none;
        display: flex;
        justify-content: center;
        align-items: center;
      }
    
      .image-section {
        flex: 2 1 auto;
        display: flex;
        justify-content: flex-start;
      }
    
      .image-section img {
        width: 100%;
        max-width: 700px;
      }
    
      .text-content {
        margin: 0;
        padding: 2% 0 2% 10%;
        text-align: left;
        align-items: flex-start;
      }
    
      .title {
        font-size: 2.5rem;
      }
    
      .description {
        font-size: 1.2rem;
        line-height: 1.8;
      }
    
      .register-button {
        padding: 1rem 2rem;
        border-radius: 30px;
        width: 40%;
        max-width: 350px;
      }
    
      .register-button:hover {
        background-color: var(--primary-color);
        border: 1px solid var(--primary-white);
        color: var(--primary-white);
        transition: background-color 0.2s ease-in-out, border 0.2s ease-in-out;
      }
    
      .footer {
        padding: 0 5%;
        justify-content: flex-end;
      }
    
      .social-icon {
        width: 50px;
        height: 50px;
        font-size: 1.5rem;
      }
    }</style>
