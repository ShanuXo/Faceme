#Faceme

WebRTC is a set of Javscript API's that allow to establish peer to peer connection between two browsers to exchange the data such as audio and video in real time

-> Real Time Communication
-> Lower Latency

WebSockets VS WebRTC

WebSockets -> Real Time Communication through Server
WebRTC -> Real Time Communication betwwen browsers. Data never touches server.

So what exactly is sent between the two clients and how is it sent ?
1.SDP - A Session Description Protocol is an object containing information about the session connection such as the codec,address,media type,audio and video and so on.
2.ICE Candidates - An ICE candidates is a public IP address and port that could potentially be an address that receives data.
