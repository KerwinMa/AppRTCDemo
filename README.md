##WebRTC4iOS Client Demo-AppRTCDemo#
===
####About AppRTCDemo#
This is a WebRTC4iOS client demo. The demo show how 2 ios clients have a real-time video communication. If you have the TURN server, they can communicate in different LAN.

####About WebRTC#
[WebRTC](http://www.webrtc.org/home) is a free, open project that enables web browsers with Real-Time Communications (RTC) capabilities via simple JavaScript APIs. The WebRTC components have been optimized to best serve this purpose. 

####About WebRTC Native APIs and libjingle#
To implement real time communication, web developer can use WebRTC API, but we, as native developer, can use what? Thsese are: [WebRTC Native APIs](http://www.webrtc.org/reference/native-apis) and [libjingle](https://code.google.com/p/libjingle/source/browse/#svn%2Ftrunk%2Ftalk%2Fapp%2Fwebrtc), they can enable Native APP to implement RTC(Real-time communication) function.

In fact, the official has provided us some [Native Example Applications](https://code.google.com/p/webrtc/source/browse/#svn%2Ftrunk%2Ftalk%2Fexamples). Here is the [official iOS example](https://code.google.com/p/webrtc/source/browse/#svn%2Ftrunk%2Ftalk%2Fexamples%2Fios%2FAppRTCDemo%253Fstate%253Dclosed), but it's not good. This is a better [iOS example](https://github.com/gandg/webrtc-ios "gandg/webrtc-ios") based the official one.
	
####About Signaling Service#
Signaling protocols and mechanisms are not defined by WebRTC standards, so you need to build it by yourself.

The demo use XMPP to build the signaling service.It implements this with [XMPPFramework](https://github.com/robbiehanson/XMPPFramework).

####The Demo Show#
![](AppRTCDemo.gif)
