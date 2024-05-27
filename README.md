
# WebRTC streamer for Raspberry PI

## General
Notice:  This is a work in progress, 

This Project aims to provide something like a remote desktop software on a webserver on the most popular Raspberry PI hardware. By integrating  [WebRTC](https://webrtc.org/native-code/) and Raspberry PI, we can stream the Raspberry camera feed to browser or native client which talks WebRTC.

Generally, the components of WebRTC service are classified into Signaling Server and WebRTC client. However, RWS(Rpi-WebRTC-Streamer) is built to operate on one piece of Raspberry PI hardware and includes some of Signaling Server functionality. In other words, the Browser or Client supporting WebRTC directly connects to RWS and receives WebRTC streaming service.


