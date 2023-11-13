class App {
    function __construct() {
        $this->printHeader();
        $this->printContent();
        $this->printFooter();
    }

    private function printHeader() {
        echo '<!DOCTYPE html>
              <html lang="en">
              <head>
                  <title>Your Webpage Title</title>
                  <style>
                      body {
                          font-family: Arial, sans-serif;
                          color: darkblue;
                      }
                      .container {
                          width: 80%;
                          margin: auto;
                      }
                      img {
                          display: block;
                          margin: 0 auto;
                      }
                  </style>
              </head>
              <body>';
    }

    private function printContent() {
        echo '<div class="container">
                  <h1 align="center">Hi 👋, I\'m Piumi Saranga</h1>
                  <h3 align="center">A passionate frontend developer from Sri Lanka</h3>
                  <img alt="Coding" width="400" src="https://res.cloudinary.com/practicaldev/image/fetch/s--2bZIjPGC--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/d4tvukbt5mra37cvwklk.gif">
                  <h4>👨‍💻 I’m a Computer Science undergraduate at the University of Colombo School of Computing</h4>
                  <p>📫 How to reach me <strong>piumisarangag@gmail.com</strong></p>
                  <h3>Connect with me:</h3>
                  <p>
                      <a href="https://linkedin.com/in/piumi ganegoda" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="piumi ganegoda" height="30" width="40" /></a>
                      <a href="https://facebook.com/your-facebook-profile" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Your Facebook" height="30" width="40" /></a>
                  </p>
                  <h3>Languages and Tools:</h3>
                  <p>
                      <!-- Your language and tool icons go here -->
                  </p>
              </div>';
    }

    private function printFooter() {
        echo '</body></html>';
    }
}

$app = new App();
