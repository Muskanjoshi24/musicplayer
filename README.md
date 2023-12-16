=> js-music-player
This is a simple User Interface of a music player created in HTML, CSS and JavaScript.
```bash
=> Usage
 Play/Pause: Click the play/pause button to control the music playback.
 Track-Selection: Tracks are loaded from the main.js file. To add more tracks, update the tracklist array with the details of each track.
  Enjoy your music!

=> Running the player

The index.html file can be run on any modern browser to run the music player.

=> Adding More Tracks
To add more tracks, follow these steps:

 Open main.js in a text editor.
 Add a new object for each track following the existing format.


const tracklist = [
  {
    title: "New Track",
    Singer: "Singer Name",
    source: "path/to/new-track.mp3",
  },
  // Add more tracks as needed
];

Save the file.

=> Project Structure
index.html: The main HTML file containing the structure of the music player.
style.css: The stylesheet file for styling the music player.
main.js: The JavaScript file with functionality for the music player.