# Memory-match-card-game
A simple, fun memory matching game built with HTML, CSS, and JavaScript. Players click on two cards to reveal card and try to match pairs. If the selected cards match, they disappear; if not, they flip back so players can try again.


🧠 Game Mechanics

-Click two cards to reveal their images.

-Matched cards stay revealed or disappear.

-Unmatched cards flip back.

-The goal is to match all pairs with the fewest attempts.

💡 Ideas for Future Enhancements

-Add a scoring system based on the number of attempts.

-Introduce a countdown timer or time tracking.

-Add more cards to increase difficulty.

-Implement multi-player support with score comparison.

🚀 Deployment Environment

-The application is deployed on an Amazon EC2 instance running a basic web server (e.g., Apache or Nginx). Static files (HTML, CSS, JS, images) are hosted directly on the instance.

🛠 How It Works

-A virtual server (EC2 instance) is provisioned via the AWS Management Console.

-The web server is configured to serve the game files.

-Files are uploaded to the instance via SSH and SCP/SFTP.

-Changes to the game code are manually updated on the instance.

💰 Cost

-This project can be deployed using the AWS Free Tier. 

-Be sure to stop or terminate your EC2 instance when not in use to avoid unnecessary charges.

