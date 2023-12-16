**YouTube Playlist Length Calculator
The YouTube Playlist Length Calculator is a web application developed to calculate the total duration of a YouTube playlist by integrating the YouTube Data API. It utilizes JavaScript, HTML, CSS for the front-end interface and Node.js with Express.js for the back-end functionality.

**Features
Retrieve video data from a YouTube playlist using the YouTube Data API.
Calculate the total duration of the playlist by summing up the durations of individual videos.
User-friendly interface to input the YouTube playlist URL.
Display the total duration in hours, minutes, and seconds format.

**Technologies Used
Front-end: HTML, CSS, JavaScript
Back-end: Node.js, Express.js
API Integration: YouTube Data API
HTTP Client: Axios

**Installation
To run this application locally, follow these steps:
1)Clone this repository:
     git clone https://github.com/OmK121/YouTube-Playlist-Length-Calculator.git
     cd YouTube-Playlist-Length-Calculator

2)Install dependencies:
         npm install
         
3)Set up environment variables:
Create a .env file in the root directory.
Add your YouTube Data API key to the .env file:
         API_KEY=YOUR_YOUTUBE_API_KEY

4)Start the server:
     npm start

 5)Access the application in your browser at http://localhost:3000    

**Usage
Enter the URL of the YouTube playlist in the input field provided on the web page.
Click the "Calculate" button to retrieve the playlist data and calculate the total duration.
The total duration of the playlist will be displayed on the screen.

**Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository
Create your branch: git checkout -b feature/new-feature
Commit your changes: git commit -am 'Add new feature'
Push to the branch: git push origin feature/new-feature
Submit a pull request
