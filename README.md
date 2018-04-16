# webcam-celeb-recognition-demo
Recognize celebrities in near real-time with a webcam, JavaScript, and the Amazon Rekognition API

## How to run this demo
1. Create an Amazon Cognito Identity Pool, allow anonymous users, and ensure that the IAM role associated with anonymous users has read permissions fpr the Amazon Rekognition API.
1. Edit `index.html`, replacing the placeholder Cognitio Identity Pool ID with your own.
1. Open the `index.html` file in your browser (tested with Firefox and Chrome).
1. Get a celebrity on camera (or use your phone to show a picture of one).
1. See identified celebrities show up on the page.