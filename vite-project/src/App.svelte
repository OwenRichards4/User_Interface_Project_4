<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<header>
  <img src="src/assets/childrens-logo-new.png" alt="Cincinnati Children's Logo">
  <ul>
    <a href="">Schedule an appointment</a>
    <a href="">Directions</a>
    <a href="">International</a>
    <a href="">Billing</a>
    <a href="">Sign in to MyChart</a>
    <a href="">Ways to help</a>
    <a href="">Donate Now</a>
  </ul>
  <ul>
    <a href="">Patients and Family</a>
    <a href="">Healthcare Professionals</a>
    <a href="">Researchers</a>
    <a href="">Search</a>
    <a href="">I want to</a>
  </ul>
</header>
<div class="pre-main">
  <h2 style="color: rgb(196, 88, 136)">Giving Hope to Kids!</h2>
  <div class="login-details">
    <label for="username-input">Login:</label>
    <input id="username-input" type="text" placeholder="username">
    <input id="password-input" type="password" placeholder="password">
    <button>Sign In</button>
    <button id="remember-sign-in" type="checkbox" checked="checked"></button>
    <label for="remember-sign-in">Remember me?</label>
    <a class="link" href="">Trouble Signing In?</a>
  </div>
</div>
<main>
  <div class="title-and-info">
    <h1>Create an Online Fundraising Page for Cincinnati Children's</h1>
    <p>
      Host your own personal fundraising page – it’s a fun way to spread the word and raise money to help change the outcome for our patients and families.
    </p> 
  </div>
  <div class="event-creation-options">
    <div class="event-2024">
      <h2>2024 Event/Fundraiser</h2>
      <button>Create a 2024 Fundraising Page</button>
      <button>Create a 2024 Team Fundraising Page</button>
      <button>Join a Team for 2024 Fundraising</button>
      <button>Create a Fundraising Page for our College Hill Campaign</button>
    </div>
    <div class="future-event">
      <h2>Future Year Event/Fundraiser</h2>
      <button>Create an Ongoing Fundraising Page</button>
      <button>Create an Ongoing Team Fundraising Page</button>
      <button>Join a Team for Ongoing Fundraising</button>
    </div>
  </div>
  <p>To register a fundraiser without creating an online page, please <a class="link" href="https://www.shecodes.io/">click here</a>.</p>
  <div class="divider"></div>
  <div class="search">
    <h1>Search for a Event/Fundraiser</h1>
    <label for="name-search">To search for someone participating in this event or a team of participants, enter all or part of the name in this field:</label>
    <input id="name-search" type="text" placeholder="name">
    <button>Search</button>
  </div>

  <p>If you have questions or would like more information, please email Andrew Stallings at <a class="link" href="">andrew.stallings@cchmc.org</a> or call 513-636-2915.</p>
</main>
<footer>
  <h3>Connect with Us</h3>
  <ul>
    <a href="">
      <img src="src/assets/facebook.png">
    </a>
    <a href="">
      <img src="src/assets/instagram.png">
    </a>
    <a href="">
      <img src="src/assets/X.png">
    </a>
    <a href="">
      <img src="src/assets/pinterest.png">
    </a>
    <a href="">
      <img src="src/assets/youtube.png">
    </a>
    <a href="">Patients and Family Blog</a>
    <a href="">Research Blog</a>
  </ul>
  <div class="divider"></div>
  <div class="footer-nav">
    <div class="quick-links">
      <h3>Quick Links</h3>
      <a href="">Schedule an Appointment</a>
      <a href="">Make a Referral</a>
      <a href="">Find an Urgent Care</a>
      <a href="">Find a Doctor / Researcher</a>
      <a href="">Pay a Bill</a>
      <a href="">Sign In to MyChart</a>
      <a href="">Request Medical Records</a>
    </div>
    <div class="explore">
      <h3>Explore</h3>
      <a href="">Locations and Directions</a>
      <a href="">Clinical Services</a>
      <a href="">Conditions and Treatments</a>
      <a href="">Visitor and Patient Information</a>
      <a href="">Clinical Trials</a>
      <a href="">Events</a>
    </div>
    <div class="about-us">
      <h3>About Us</h3>
      <a href="">About Cincinnati Children's</a>
      <a href="">Careers</a>
      <a href="">Newsroom</a>
      <a href="">Contact Us</a>
      <a href="">Download Our Caren App</a>
      <a href="">Terms of Use / Privacy Policies</a>
      <a href="">Non-Discrimination Notice</a>
    </div>
  </div>
  <h2>Give Today</h2>
  <h2>Subscribe</h2>
  <div class="footer-end">
    <img src="src/assets/arc-pattern-lower-left.png">
    <p>
      3333 Burnet Avenue, Cincinnati, Ohio 45229-3026 | 1-513-636-4200 | 1-800-344-2462 <br><br>
      © Cincinnati Children's Hospital Medical Center. All rights reserved. <br><br>
      Cincinnati Children's is a tax-exempt 501(C)(3) nonprofit organization. Your gift is tax-deductible as allowed by law.
    </p>
    <a href="">
      <img src="src/assets/Badge-ChildrensHospitals-Honor-Roll_Generic-year86.png">
    </a>
    <a href="">
      <img src="src/assets/bptw.png">
    </a>
    <img src="src/assets/arc-pattern-upper-right.png" style="position: relative; bottom: 200px;">
  </div>
</footer>

<style>
  :global(body) {
    margin: 0;
    padding: 0;

    font-family: "Gill Sans", sans-serif;

    text-align: center;
  }

  header {
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;

    margin-top: 30px;
    padding: 0px 30px;
  }

  ul a {
    position: relative;
    background-color: rgb(211, 211, 211);
    padding: 5px 10px;

    color: black;
    text-decoration: none;
  }

  ul {
    position: relative;
    display: flex;
    flex-direction: row;
    gap: 0;

    height: fit-content;
  }

  ul a:hover {
    background-color: rgb(230, 230, 230);
  }

  .pre-main, main {
    position: relative;
    width: 80%;
    left: 10%;
  }

  .pre-main {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

    margin-bottom: 5px;
  }
  
  .login-details {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 5px;
  }

  .login-details input, .login-details button {
    padding: 5px;
  }

  .login-details label {
    font-size: 120%;
  }

  main {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    gap: 20px;

    box-shadow: 1px 1px 8px rgb(10,10,10);
    padding: 10px 20px;

    margin-bottom: 30px;
  }

  main button {
    padding: 15px 30px;
    background-color: rgb(128, 191, 86);
    color: white;
    font-size: 100%;
    width: 100%;

    border: none;
  }

  main h2 {
    color: rgb(196, 88, 136);
  }

  .event-creation-options {
    position: relative;

    display: flex;
    flex-direction: row;
    align-items: start;
    gap: 8%;
    
    justify-content: center;
  }

  .event-2024, .future-event {
    position: relative;

    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 5px;
    width: 30%;
  }

  .link {
    color: rgb(8, 167, 196);
    text-decoration: none;

    font-weight: bold;
  }

  .divider {
    position: relative;

    width: 80%;
    height: 1px;
    background-color: lightgray;
    left: 10%;
  }

  .search button {
    margin-top: 5px;
    width: 65%;
  }

  footer ul {
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: center;
  }

  .footer-nav {
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: center;
  }

  .quick-links, .explore, .about-us {
    position: relative;
    display: flex;
    flex-direction: column;
  }

  .footer-end {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

</style>
