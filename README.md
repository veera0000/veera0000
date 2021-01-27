<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
 
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  
  <title>Frontend Mentor | [Challenge Name Here]</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>
<body class="default">

  <div class="header">
    <div class="container">
      <div class="contain">
        <div class="main-text">
          <h2>Social Media Dashboard</h2>
          <p>Total Followers: 23,004</p>
        </div>
        <div class="check-btn">
          <div class="text">
          <h2>Dark Mode</h2>
          </div>
          <div class="btn">
          <input type="checkbox" id="toggle-btn">
          </div>
        </div>
      </div>
    </div>
  </div>


  <!-- Main Cards -->

  <div class="main">
    <div class="container">
      <div class="cards">
        <div class="card facebook">
          <div class="user">
            <img src="images/icon-facebook.svg" alt="icon-facebook">
            <p>@nathanf</p>
          </div>
          <div class="text">
            <h1>1987</h1>
            <p>FOLLOWERS</p>
          </div>
          <div class="status">
            <img src="images/icon-up.svg" alt="icon-up">
            <p>12 Today</p>
          </div>
        </div>

        <div class="card twitter">
          <div class="user">
            <img src="images/icon-twitter.svg" alt="icon-twitter">
            <p>@nathanf</p>
          </div>
          <div class="text">
            <h1>1044</h1>
            <p>FOLLOWERS</p>
          </div>
          <div class="status">
            <img src="images/icon-up.svg" alt="icon-up">
            <p>99 Today</p>
          </div>
        </div>

        <div class="card instagram">
          <div class="user">
            <img src="images/icon-instagram.svg" alt="icon-instagram">
            <p>@nathanf</p>
          </div>
          <div class="text">
            <h1>11K</h1>
            <p>FOLLOWERS</p>
          </div>
          <div class="status">
            <img src="images/icon-up.svg" alt="icon-up">
            <p>1099 Today</p>
          </div>
        </div>

        <div class="card youtube">
          <div class="user">
            <img src="images/icon-youtube.svg" alt="icon-youtube">
            <p>@nathanf</p>
          </div>
          <div class="text">
            <h1>8239</h1>
            <p>SUBSCRIBERS</p>
          </div>
          <div class="status">
            <img src="images/icon-down.svg" alt="icon-down">
            <p>144 Today</p>
          </div>
        </div>
      </div>
    </div>
  </div>


  <!-- Overview Section -->

  <div class="overview">
    <div class="container">
      <div class="overview-heading">
        <h1>Overview - Today</h1>
      </div>
      <div class="overview-cards">
        <div class="sections">
          <div class="section1">
            <div class="card first facebook">
              <div class="reactions">
                <h3>Page Views</h3>
                <img src="images/icon-facebook.svg" alt="icon-facebook">
              </div>
              <div class="stats">
                <h1>87</h1>
                <div class="percentage">
                  <img src="images/icon-up.svg" alt="icon-up">
                  <p>3%</p>
                </div>
              </div>
            </div>

            <div class="card second facebook">
              <div class="reactions">
                <h3>Likes</h3>
                <img src="images/icon-facebook.svg" alt="icon-facebook">
              </div>
              <div class="stats">
                <h1>52</h1>
                <div class="percentage">
                  <img src="images/icon-down.svg" alt="icon-up">
                  <p>2%</p>
                </div>
              </div>
            </div>

            <div class="card third instagram">
              <div class="reactions">
                <h3>Likes</h3>
                <img src="images/icon-instagram.svg" alt="icon-instagram">
              </div>
              <div class="stats">
                <h1>5462</h1>
                <div class="percentage">
                  <img src="images/icon-up.svg" alt="icon-up">
                  <p>2257</p>
                </div>
              </div>
            </div>

            <div class="card fourth instagram">
              <div class="reactions">
                <h3>Profile Views</h3>
                <img src="images/icon-instagram.svg" alt="icon-instagram">
              </div>
              <div class="stats">
                <h1>52K</h1>
                <div class="percentage">
                  <img src="images/icon-up.svg" alt="icon-up">
                  <p>1375%</p>
                </div>
              </div>
            </div>
          </div>
          <div class="section2">
            <div class="card fifth twitter">
              <div class="reactions">
                <h3>Retweets</h3>
                <img src="images/icon-twitter.svg" alt="icon-twitter">
              </div>
              <div class="stats">
                <h1>117</h1>
                <div class="percentage">
                  <img src="images/icon-up.svg" alt="icon-up">
                  <p>303%</p>
                </div>
              </div>
            </div>

            <div class="card sixth twitter">
              <div class="reactions">
                <h3>Likes</h3>
                <img src="images/icon-twitter.svg" alt="icon-twitter">
              </div>
              <div class="stats">
                <h1>507</h1>
                <div class="percentage">
                  <img src="images/icon-up.svg" alt="icon-up">
                  <p>553%</p>
                </div>
              </div>
            </div>

            <div class="card seventh youtube">
              <div class="reactions">
                <h3>Likes</h3>
                <img src="images/icon-youtube.svg" alt="icon-youtube">
              </div>
              <div class="stats">
                <h1>107</h1>
                <div class="percentage">
                  <img src="images/icon-down.svg" alt="icon-down">
                  <p>19%</p>
                </div>
              </div>
            </div>

            <div class="card eighth youtube">
              <div class="reactions">
                <h3>Total Views</h3>
                <img src="images/icon-youtube.svg" alt="icon-youtube">
              </div>
              <div class="stats">
                <h1>1407</h1>
                <div class="percentage">
                  <img src="images/icon-down.svg" alt="icon-down">
                  <p>12%</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="https://www.facebook.com/lucifer0x446/">Ahmed Samy</a>.
  </div>

  <script src="app.js"></script>
</body>
<style>
  .default {
    --facebook: #198ff5;
    --twitter: #1ca0f2;
    --instagram: #df4996;
    --youtube: #c4032a;
    --bg-dark: #1e202a;
    --bg-top: #1f212e;
    --cardbg-dark: #252a41;
    --primary-text-dark: #ffffff;
    --secondary-text-dark: #8b97c6;
    --hover-color: #363e57;
    --lime-green: #1db489;
    --bright-red: #dc414c;
}
  
.light-theme {
    --facebook: #198ff5;
    --twitter: #1ca0f2;
    --instagram: #df4996;
    --youtube: #c4032a;
    --bg-dark: #ffffff;
    --bg-top: #f5f7ff;
    --cardbg-dark: #f0f2fa;
    --primary-text-dark: #1e202a;
    --secondary-text-dark: #63687e;
    --hover-color: #bfc1c7;
    --lime-green: #1db489;
    --bright-red: #dc414c;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    font-size: 16px;
    height:100vh;
    background-color: var(--bg-dark);
}

.container {
    max-width: 1440px;
    margin:0 auto;
    padding: 0 20px;
}
.main .card:hover,
.overview .card:hover
{
    background-color: var(--hover-color);
    cursor: pointer;
    transition: all 0.9s;
    transform:scale(1.05, 1.05)
}

.header {
    background-color: var(--bg-top);
    background-size:cover ;
    padding: 20px 0;
    color:var(--primary-text-dark);
    height: 35vh;
}
.contain {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.main-text {
    padding-top: 20px;
}

.main-text h2 {
    font-weight: 700;
    padding-bottom: 10px;
    font-size: 30px;
}

.main-text p {
    color:var(--secondary-text-dark);
    font-weight: bold;
}

.check-btn {
    display: flex;
    align-items: center;
    height: 100%;
}

.check-btn h2 {
    font-size: 16px;
    margin: 0 10px;
    color: var(--secondary-text-dark);
  }


#toggle-btn {
    -webkit-outline: none;
    -moz-outline: none;
    -ms-outline: none;
    outline: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    -ms-appearance: none;
    appearance: none;
    -webkit-width:50px;
    -ms-width:50px;
    -moz-width:50px;
    width: 50px;
    -webkit-height:25px;
    -ms-height:25px;
    -moz-height:25px;
    height: 25px;
    -webkit-background-image: linear-gradient(
    to right,
    hsl(210, 78%, 56%),
    hsl(146, 68%, 55%)
  );
  
  -ms-background-image: linear-gradient(
    to right,
    hsl(210, 78%, 56%),
    hsl(146, 68%, 55%)
  );
  
  -moz-background-image: linear-gradient(
    to right,
    hsl(210, 78%, 56%),
    hsl(146, 68%, 55%)
  );
  background-image: linear-gradient(
    to right,
    hsl(210, 78%, 56%),
    hsl(146, 68%, 55%)
  );
  position: relative;
  -webkit-border-radius: 50px;
  -moz-border-radius: 50px;
  -ms-border-radius: 50px;
  border-radius: 50px;
}

#toggle-btn:hover {
    cursor: pointer;
}

#toggle-btn::before {
    content: '';
    height:20px;
    width:22px;
    border-radius: 50px;
    background-color: hsl(230, 17%, 14%);
    position: absolute;
    margin:3px;
    transition: all 0.9s;
}

#toggle-btn:checked {
    background-color: hsl(230, 22%, 74%);
    background-image: none;
    transition: background-color 0.9s;
    transition: background-image 0.9s;
}

#toggle-btn:checked::before {
    transform: translate(100%);
    transition: all 0.9s;
    background-color: #fff;
}


/* Main Cards */ 
.main {
    margin-top:-125px;
}

.cards {
    display: flex;
    align-items:center;
    justify-content: space-between;
}

.main .card {
    display: flex;
    flex-direction: column;
    text-align: center;
    height: 250px;
    background-color: var(--cardbg-dark);
    padding: 30px 40px;
    width:25%;
    margin-right:30px;
    border-radius:10px;
}

.card.facebook {
    border-top: 6px solid var(--facebook);
}

.card.facebook .user {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

.card.facebook .user img {
    padding-right: 8px;
}

.card.facebook .user p {
    color:var(--secondary-text-dark);
}
.card.facebook .text h1 {
    color:var(--primary-text-dark);
    font-weight: 700;
    font-size: 60px;
}

.card.facebook .text p {
    color:var(--secondary-text-dark);
    letter-spacing: 6px;
    font-size: 14px;
}

.card.facebook .status {
    display: flex;
    justify-content: center;
    align-items:center ;
    margin-top: 25px;
}

.card.facebook .status p{
    font-weight: 700;
    color:var(--lime-green);
    font-size: 12px;
    margin-left: 5px;
}

.card.twitter {
    border-top: 6px solid var(--twitter);
}

.card.twitter .user {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

.card.twitter .user img {
    padding-right: 8px;
}

.card.twitter .user p {
    color:var(--secondary-text-dark);
}
.card.twitter .text h1 {
    color:var(--primary-text-dark);
    font-weight: 700;
    font-size: 60px;
}

.card.twitter .text p {
    color:var(--secondary-text-dark);
    letter-spacing: 6px;
    font-size: 14px;
}

.card.twitter .status {
    display: flex;
    justify-content: center;
    align-items:center ;
    margin-top: 25px;
}

.card.twitter .status p{
    font-weight: 700;
    color:var(--lime-green);
    font-size: 12px;
    margin-left: 5px;
}

.card.instagram {
    border-top: 6px solid var(--instagram);
}

.card.instagram .user {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

.card.instagram .user img {
    padding-right: 8px;
}

.card.instagram .user p {
    color:var(--secondary-text-dark);
}
.card.instagram .text h1 {
    color:var(--primary-text-dark);
    font-weight: 700;
    font-size: 60px;
}

.card.instagram .text p {
    color:var(--secondary-text-dark);
    letter-spacing: 6px;
    font-size: 14px;
}

.card.instagram .status {
    display: flex;
    justify-content: center;
    align-items:center ;
    margin-top: 25px;
}

.card.instagram .status p{
    font-weight: 700;
    color:var(--lime-green);
    font-size: 12px;
    margin-left: 5px;
}

.card.youtube {
    border-top: 6px solid var(--youtube);
}

.card.youtube .user {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

.card.youtube .user img {
    padding-right: 8px;
}

.card.youtube .user p {
    color:var(--secondary-text-dark);
}
.card.youtube .text h1 {
    color:var(--primary-text-dark);
    font-weight: 700;
    font-size: 60px;
}

.card.youtube .text p {
    color:var(--secondary-text-dark);
    letter-spacing: 6px;
    font-size: 14px;
}

.card.youtube .status {
    display: flex;
    justify-content: center;
    align-items:center ;
    margin-top: 25px;
}

.card.youtube .status p{
    font-weight: 700;
    color:var(--bright-red);
    font-size: 12px;
    margin-left: 5px;
}

/* Overview Section */ 
.overview {
    width:100%;
    margin-top:50px;
    margin-bottom: 50px;
}

.overview-heading {
    color:var(--primary-text-dark)
}

.overview-cards {
    display: flex;
    align-items: center;
    margin-top: 50px;
    width:100%;
}

.sections {
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    width:100%;
}

.overview-cards .section1 {
    display: flex;
    
}

.overview-cards .section2 {
    display: flex;
}

.overview-cards .card {
    width: 25%;
    height:200px;
    background-color: var(--cardbg-dark);
    text-align: center;
    margin:15px;
    border-radius: 6px;
    padding-top:25px;
}

.overview-cards .first,
.overview-cards .fifth {
    margin-left:0;
} 

.overview-cards .card .reactions,
.overview-cards .card .stats
{
    display: flex;
    justify-content: space-between;
    padding:0 30px;
}

.overview-cards .card .stats {
    padding-top:80px;
}

.overview-cards .card .stats h1 {
    color: var(--primary-text-dark)
}

.overview-cards .card .stats .percentage {
    display: flex;
    justify-content: center;
    align-items: center;
}

.overview-cards .card .stats .percentage p {
    color:var(--lime-green);
    font-size: 13px;
    padding-left: 5px;
}

.overview-cards .card .reactions h3 {
    color:var(--secondary-text-dark);
    font-size: 15px;
}

.overview-cards .second .stats .percentage p,
.overview-cards .seventh .stats .percentage p,
.overview-cards .eighth .stats .percentage p {
    color:var(--bright-red)
}


@media screen and (max-width:480px){
    .contain {
        display: flex;
        flex-direction: column;
        width:100%;
    }

    .main-text {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: center;
        width:95%;
        position: relative;
        margin-bottom:20px;
    }

    .main-text::after {
        content:'';
        width:100%;
        background-color: rgba(182, 182, 182, 0.082);
        position: absolute;
        height:1px;
        top:110px;
    }

    .check-btn {
        margin-top:30px;
        width:98%;
        display: flex;
        justify-content: space-between;
        margin-left: 0;
        padding-left:0;
    }

    .main .cards {
        flex-direction: column;
        margin-top: 70px;
        padding:0;
        justify-content: center;
        align-items: center;
    }

    .main .card {
        width:95%;
        margin-bottom:30px;
        height:250px;
        margin-left: 0;
        margin-right: 0;
        text-align: center;
    }

    .main .card .text{
        padding-bottom: 15px;
    }

    .main .card .text h1 {
        padding-bottom: 20px;
        font-size: 50px;
    }

    .main .card .text p {
        letter-spacing: 3px;
    }

    .overview-heading {
        margin-left:10px;
    }
    
    .section1 {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .section2 {
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .overview .sections .card {
        width:95%;
        margin-left: 0;
        margin-right: 0;
    }
}

.attribution {
    margin-bottom: 20px;
    color:var(--primary-text-dark)
}

.attribution a {
    text-decoration: none;
    color: var(--secondary-text-dark)
}

  
  </style>
</html>
