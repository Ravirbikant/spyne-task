#Captioned Video Player Web App
This web application allows users to add captions to a hosted video (specifically YouTube videos) and play the video with synchronized captions.

#Features
-Load and Play Video: Users can enter a YouTube video URL to load and play the video.
-Add Captions: Users can enter captions along with timestamps indicating when each caption should be displayed.
-Remove Captions: Captions can be removed individually.
-Synchronized Caption Display: Captions are displayed at the correct timestamps while the video is playing.

#Getting Started
To run the application locally, follow these steps:

-Clone the repository
-Simply open the index.html file in your preferred web browser.
-Enter a YouTube Video URL:
-In the provided text box, enter a valid YouTube video URL.
-Add Captions:
  Enter captions in the textarea and provide timestamps (format: hh:mm
  ).
  Click on "Add Caption" to add the caption.
-Click on "Load and Play Video with Captions" to load the video with added captions.

#Technical Decisions
-YouTube Player API: Utilized YouTube's iframe API to embed and control the video player.
-JavaScript: Implemented functionality using plain JavaScript for simplicity and minimal dependencies.
-CSS: Used basic CSS for styling to maintain a clean and responsive design.
-Data Handling: Captions are stored in an array in memory, making it straightforward but limited to a single session.
-User Experience Considerations
-Intuitive UI: Designed a clean and user-friendly interface with clear instructions and feedback messages for user actions.
-Error Handling: Implemented validation for YouTube URL, timestamp format, and mandatory fields for captions to enhance user experience.
-Responsive Design: Ensured the application layout adapts to different screen sizes for a consistent experience.

#Trade-offs and Future Improvements
-Persistence: Currently, captions are stored in memory and reset upon page refresh. Implementing backend storage (e.g., using localStorage or a backend database) would enable persistence across sessions.
-Accessibility: Enhancing accessibility features such as keyboard navigation and screen reader support would make the application more inclusive.
-Advanced Features: Adding features like editing captions directly on the video timeline, support for more video platforms beyond YouTube, and sharing capabilities could enhance functionality.

#Feedback and Contributions
If you have any feedback or suggestions for improvements, feel free to open an issue or pull request. Your input is highly valued!
