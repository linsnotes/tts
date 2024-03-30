# Text-to-Speech and Pinyin Conversion

## Introduction
This website is entirely written using HTML, CSS, and JavaScript, which are standard technologies supported by all modern web browsers. These technologies do not require server-side processing.

## Key Features

### Client-Side JavaScript
The interactivity and dynamic aspects of the website, such as text-to-speech conversion and Pinyin generation, are handled by JavaScript running on the client's side (in the user's browser). The JavaScript code utilizes the SpeechSynthesis Web API for text-to-speech—a feature natively provided by browsers—and the `pinyin-pro` library (loaded via a script tag) for converting Chinese text to Pinyin.

### No Server-Side Data Processing
All processing is done client-side using JavaScript, with no server-side data processing or database interactions required.

### Static Assets
Elements like images and the favicon are static and loaded directly by the browser, eliminating the need for server-side processing.

## Functionality

### Text-to-Speech
The website leverages the SpeechSynthesis Web API, optimally supported on desktop operating systems due to advanced speech synthesis capabilities. While modern smartphones also support this API, desktops typically offer better voice variety, quality, and control over parameters like rate and pitch.

### Pinyin Conversion
Pinyin conversion is handled by the `pinyin-pro` library, a JavaScript-based solution effective across all devices with a compatible browser.

## Technical Details

### SpeechSynthesis API
Part of the Web Speech API, set as a standard by the World Wide Web Consortium (W3C), the SpeechSynthesis API has varying implementations across different browsers, affecting available voices, quality, and functionality.

## Recommendations for Users

### Windows Users
Optimal experience is likely on a Windows computer, particularly using the Microsoft Edge browser, known for strong support of web standards and a wide range of voices in the SpeechSynthesis API.

### Mobile Users
While mobile devices support these features, the experience may be limited compared to desktops or laptops, particularly in voice variety and control in speech synthesis. Modern smartphones with updated versions of Chrome, Safari (for iOS), or Edge are still capable of supporting text-to-speech synthesis.
