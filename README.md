# Code Refactor Starter Code

HTML Refactoring:

Added a descriptive <title> making th epage accessible to widest variety of users and enhancing search engine optimization. 

Added alt attributes to img & scr to accessiblity  important to screen readers and other assistive technologies and can also imporve search engine rankings for websites. 

Changed <h2> to <h4> on the bottome linen making it sequestial in <h1> to <h6>, impriving page rendering.

Added HTML attributes at the <head> such as  <meta http-equiv="X-UA-compatible" content="IE=edge"/>
    <meta name="viewpoint" content="width=device-width,initial scale=1.0"/> to add metadata that helps the broweser render the page correctly.

Added <title> to the line of code labeled with .footer, "<title> <h4>Made with ❤️️ by Horiseon</h4>, &copy; 2023 Horiseon Social Solution Services, Inc." </title> making it a metadata and invisible to users. 

CSS file refactor:

Applied DRY rule to multiple codes of line to make is easy and flexible during commits. Ex:
.search-engine-optimization,
.online-reputation-management,
.social-media-marketing {
    margin-bottom: 20px;
    padding: 60px;
    height: 300px;
    font-size: medium;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff 
}

Added <padding> and <margin> to varius aspects of the code to meet the MOCKUP rendering requirement. 
