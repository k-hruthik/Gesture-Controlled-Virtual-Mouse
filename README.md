# Gesture Controlled Virtual Mouse &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/xenon-19/Gesture_Controller) 

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.

 _Video Demonstration: [link](https://www.youtube.com/watch?v=ufm6tfgo-OA&ab_channel=Proton)_<br>
Note: Use Python version: 3.8.5

# Features
 _click on dropdown to know more_ <br>

### Gesture Recognition:
<details>
<summary>Neutral Gesture</summary>
 <figure>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/palm.gif" alt="Palm" width="711" height="400"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor</summary>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/e20edfb1f368ffa600d96bd91031942ec97cb2ab/demo_media/move%20mouse.gif" alt="Move Cursor" width="711" height="400"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/left%20click.gif" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/right%20click.gif" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/double%20click.gif" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Scrolling.gif" alt="Scrolling" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/drag%20and%20drop.gif" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/multiple%20item%20selection.gif" alt="Multiple Item Selection" width="711" height="400"><br>
 <figcaption>Gesture to select multiple items</figcaption>
</details>

<details>
<summary>Volume Control</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Volume%20control.gif" alt="Volume Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Volume control. The rate of increase/decrease of volume is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Brightness Control</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Brigntness%20Control.gif" alt="Brightness Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Brightness control. The rate of increase/decrease of brightness is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

### Voice Assistant ( ***Proton*** ):
<details>
<summary>Launch / Stop  Gesture Recognition</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20launch%20stop%20gest.png" alt="launch stop gesture recognition" width="250" height="auto">
<ul>
  <li>
    <code> Proton Launch Gesture Recognition </code><br>
    Turns on webcam for hand gesture recognition.
  </li>
  <li>
    <code> Proton Stop Gesture Recognition </code><br>
    Turns off webcam and stops gesture recognition.
    (Termination of Gesture controller can also be done via pressing <code>Enter</code> key in webcam window)
   </li>
</ul>
</details>

<details>
<summary>Google Search</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20search.png" alt="proton search github" width="800" height="auto">
<ul>
  <li>
    <code>Proton search {text_you_wish_to_search}</code><br>
    Opens a new tab on Chrome Browser if it is running, else opens a new window. Searches the given text on Google.
  </li>
</ul>
</details>

<details>
<summary>Find a Location on Google Maps</summary>
 <img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20find%20location.png" alt="proton find location" width="800" height="auto">
  <ol>
    <li> 
      <code>Proton Find a Location</code><br>
      Will ask the user for the location to be searched.
    </li>
    <li> 
      <code>{Location_you_wish_to_find}</code><br>
      Will find the required location on Google Maps in a new Chrome tab.
    </li>
  </ol>
</details>

<details>
<summary>File Navigation</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20list%20files.png" alt="proton list files" width="250" height="auto">&emsp;
 <img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20open.png" alt="proton open" width="250" height="auto">&emsp;
 <img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20delete.png" alt="proton delete" width="250" height="auto">
<ul>
  <li>
    <code>Proton List Files</code><br>
    Will list all files and folders in the present working directory.
  </li>
  <li>
    <code>Proton Open {file/folder_name}</code><br>
    Opens the required file or changes directory to the required folder.
  </li>
  <li>
    <code>Proton Delete {file/folder_name}</code><br>
    Deletes the required file/folder from the present working directory.
  </li>
</ul>
</details>

<details>
<summary>Finding a Path</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20find%20path.png" alt="proton find path" width="800" height="auto">
<ol>
  <li>
    <code>Proton Find a Path</code><br>
    Will ask the user for starting and destination point to be searched.
  </li>
  <li>
    <code>Starting point</code><br>
    Asks user for starting point.
  </li>
  <li>
    <code>Destination</code><br>
    Asks user for destination.
  </li>
</ol>
</details>

<details>
<summary>Weather Information</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20weather.png" alt="proton weather" width="800" height="auto">
<ol>
  <li>
    <code>Proton Weather Information</code><br>
    Will ask the user for city for which weather information is needed.
  </li>
  <li>
    <code>{City}</code><br>
    Opens weather information of the required city on a new Chrome tab.
  </li>
</ol>
</details>

<details>
<summary>Sending Email</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/4041eedc2f75fa2923902000b606a05a677629e8/demo_media/voice%20commands/proton%20send%20email.png" alt="proton send email" width="800" height="auto">
<ol>
  <li>
    <code>Proton Send Email</code><br>
    Will ask the user for the recipient email address.
  </li>
  <li>
    <code>{recipient_email}</code><br>
    Will ask for the subject.
  </li>
  <li>
    <code>{subject}</code><br>
    Will ask for the message.
  </li>
  <li>
    <code>{message}</code><br>
    Will send the email to recipient.
  </li>
</ol>
</details>

# Requirements
All the dependencies can be installed using `requirements.txt`.

```bash
pip install -r requirements.txt
 Step 4:
  ```bash 
  conda install PyAudio
  ```
  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src`
  
  Step 6:
  
  For running Voice Assistant:
  ```bash 
  python Proton.py
  ```
  ( You can enable Gesture Recognition by using the command "Proton Launch Gesture Recognition" )
  
  Or to run only Gesture Recognition without the voice assisstant:
  
  Uncomment last 2 lines of Code in the file `Gesture_Controller.py`
  ```bash 
  python Gesture_Controller.py
  ```
  

