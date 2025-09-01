StreamLite
StreamLite is a simple, browser-based web application that allows you to turn your phone into a live video camera for your PC. It uses WebRTC (Web Real-Time Communication) to create a direct, real-time peer-to-peer connection for streaming.

The application also includes a built-in feature to record the live stream in a 9:16 aspect ratio, making it perfect for creating content for platforms like YouTube Shorts.

Features
Real-Time Streaming: Live video and audio from your phone's camera streamed directly to your PC.

No Installation Required: Runs entirely in your web browser. Just open the HTML file on both devices.

YouTube Shorts Ready: Records video in a vertical 9:16 aspect ratio.

Simple Connection: Uses a secure Offer/Answer model to establish the connection between devices.

How to Use
Host (PC): Open the index.html file on your PC and click "Host."

Generate Offer: Click the "Start Host" button to generate the connection Offer text.

Client (Phone): Open the same index.html file on your phone, click "Client," and paste the Offer text.

Connect: Click "Generate Answer" on the phone, copy the new Answer text, paste it back into the PC's "Host" section, and click "Connect."

The stream will begin, and you can start recording at any time.

Contribution
This is a personal project, but I welcome feedback and suggestions! Feel free to open an issue or submit a pull request if you have ideas for improvements.
