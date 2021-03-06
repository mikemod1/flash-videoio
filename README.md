# Flash-based audio and video communication widget #

> This project was migrated from <https://code.google.com/p/flash-videoio> on May 17, 2015  
> Keywords: *Flash Player*, *Recorder*, *Video*, *RTMP*, *RTMFP*, *FLV*, *Conferencing*, *VideoIO*, *Facebook*, *Stratus*, *Google App Engine*  
> Members: *kundan10* (owner), *theintencity*, *voipresearcher*, *mamtasingh05*  
> Links: [Support](http://groups.google.com/group/myprojectguide), [Tutorial](http://myprojectguide.org/p/flash-videoio), [Download](https://github.com/theintencity/flash-videoio/tree/download), [Wiki](https://github.com/theintencity/flash-videoio/tree/wiki)   
> License: [GNU Lesser GPL](http://www.gnu.org/licenses/lgpl.html)  
> Others: starred by 73 users  

![logo](/logo.png)

This project implements example applications for Flash-based audio and video communication using the [Flash-VideoIO](http://myprojectguide.org/p/flash-videoio/index.html) component. <em>The software is licensed as LGPL, so if you make a modification to the source you should contribute back the modifications</em>. The Flash-VideoIO component is a reusable generic Flash application to record and play live audio and video content. It can be used for a variety of use cases in audio and video communication, e.g., live camera view, recording of multimedia messages, playing video files from web server or via streaming, live video call and conferencing using client-server as well as peer-to-peer technology. This project web site provides several examples applications and tutorial with (open) source code on how to do these scenarios.

# Announcements #
**New**: The VideoIO sources are now checked in and available as LGPL. It is our humble request to please please contribute back any improvements or modifications. If you have major improvements, we will be happy to add you as a committer/contributor. Thank you!

<font color='red'>IMPORTANT</font> Please send any bug/support request to the [support group](http://groups.google.com/group/myprojectguide) instead of directly to the owner

# Introduction #


## Motivation ##

Please see my slides on <a href='http://kundansingh.com/talks/singh-kundan-flashbased.pdf'>flash based audio and video communication</a> presented at VoIP conference and expo at Illinois Institute of Technology in Oct 2010.

Our white paper on <a href='http://arxiv.org/pdf/1107.0011v1'>Flash based audio and video communication in the cloud</a> gives an overview of why Flash Player for communication? motivation for our API and how various example application scenarios are built on top of our API?

## Getting Started ##

Follow the links below for a tutorial on how to use VideoIO.
  1. [How to embed VideoIO in your web page?](http://myprojectguide.org/p/flash-videoio/1.html)
  1. [How to show live camera view?](http://myprojectguide.org/p/flash-videoio/2.html)
  1. [How to work with media server?](http://myprojectguide.org/p/flash-videoio/3.html)
  1. [How to record and play a video message?](http://myprojectguide.org/p/flash-videoio/4.html)
  1. [How to play a video file?](http://myprojectguide.org/p/flash-videoio/5.html)
  1. [How to do two-party video call?](http://myprojectguide.org/p/flash-videoio/6.html)
  1. [How to do one-to-many video broadcast?](http://myprojectguide.org/p/flash-videoio/7.html)
  1. [How to do multi-party video conference?](http://myprojectguide.org/p/flash-videoio/8.html)
  1. [How to do peer-to-peer video call?](http://myprojectguide.org/p/flash-videoio/9.html)
  1. [How to use the VideoIO API?](http://myprojectguide.org/p/flash-videoio/10.html)
  1. [How to do SIP-based VoIP call?](http://myprojectguide.org/p/flash-videoio/11.html)
  1. [How to embed VideoIO in your Flex application?](http://myprojectguide.org/p/flash-videoio/12.html)
  1. [How to do video broadcast using multicast group?](http://myprojectguide.org/p/flash-videoio/13.html)
  1. [How to take snapshot image as binary data?](http://myprojectguide.org/p/flash-videoio/14.html)

After you have gone through the above tutorial you can click on [the demonstration and testing of VideoIO API](http://myprojectguide.org/p/flash-videoio/test.html) page to try out and test the various properties of VideoIO. The test page allows you to see the behavior of various properties as you set some properties. Before you use this project, **please check** the [FAQ](https://github.com/theintencity/flash-videoio/blob/wiki/Faq.md) page for common gotchas!

## Download ##

You can download the example applications source code in this project under the source tab. You can get the latest version of VideoIO.swf from the [download](://github.com/theintencity/flash-videoio/tree/download) page.

## Support ##

If you are a developer who wants to add a new feature to VideoIO or use the software in your project, feel free to post a message to the support group to let us know. The goal is to make VideoIO independent of the example applications, so that developers do not need to understand or know Flash programming.

You can post a message to the [support group](http://groups.google.com/group/myprojectguide). You don't need to subscribe to that group to post a message. **I look forward to hearing from you!**

# Example Projects #

These examples are available in SVN under `examples` directory. These applications are tested only on Firefox browser, and are also reported to work on Chrome and Safari. These applications: IIT Web Conference, Intencity AIRphone, and Public Chat are portable across different browsers and systems. Other applications **do not work on Internet Explorer (IE) browser** because I used some Javascript that is unsupported in IE.

  * [IIT Web Conference](http://gardo1.rice.iit.edu/webconf/): <a href='http://gardo1.rice.iit.edu/webconf/'><img src='http://myprojectguide.org/p/flash-videoio/webconf-logo.jpg' align='right' border='0' /></a>This web-based application allows you to do multiparty conference and slides presentation using Flash based real-time audio and video. It has been tested on Chrome, Safari, Firefox and IE8, using Flash Player 10.3. It is built as part of the [Voice and Video on Web](https://sites.google.com/site/vvowproject/) project at IIT Chicago, and is an open source project and <a href='https://github.com/theintencity/vvowproject'>source code is available here</a>. It uses RESTful Websocket (and Socket.io)-based signaling for web communications and Flash VideoIO for audio and video communication. Please see a demo video on youtube at [http://www.youtube.com/watch?v=O2kJbI9sETU](http://www.youtube.com/watch?v=O2kJbI9sETU). _Keywords_: web conference, slides presentation, distance education, websocket, REST.<br />
  * [Intencity AIRphone](http://theintencity.com/products.html#airphone): <a href='http://theintencity.com/products.html#airphone'><img src='http://www.theintencity.com/airphone/image.png' align='right' border='0' /></a> This is a free desktop video phone application built on Adobe Integrated Runtime (AIR) platform. It uses the Flash-VideoIO component to handle end-to-end media path, and resource-oriented web service of IIT web conference to handle the signaling. It presents a device user interface on desktop and allows two party video call. This is not an open source application. Please see a demo video on youtube at [http://www.youtube.com/watch?v=MeJX-qs5ztY](http://www.youtube.com/watch?v=MeJX-qs5ztY).  _Keywords_: video phone, AIR-based video call.<br />
  * ~~[iVideoChat](http://apps.facebook.com/iVideoChat/) and [Face Talk](http://apps.facebook.com/face-talk): (Does **not** work after Facebooks recent change in authentication API.) These are face-to-face two-party video chat applications on Facebook. They allow you to video chat with your online friends. They use Adobe Stratus for peer-to-peer media streams, and Facebook's text chat and live messaging for signaling. A friend of mine and I created these projects as demonstrations of Flash VideoIO on Facebook. The main source file is available as [index.php](/examples/face-talk/index.php). Please replace the app-id and secret based on your Facebook API developer key. Please see the [demo video](https://github.com/theintencity/flash-videoio/blob/download/demo-facetalk.mp4) using [VLC](http://www.videolan.org/vlc/) media player on how to get started. _Keywords_: video call, facebook, adobe stratus, live messaging.~~<br />
  * [iChatNow](http://apps.facebook.com/ichatnow): <a href='http://apps.facebook.com/ichatnow'><img src='http://myprojectguide.org/p/flash-videoio/ichatnow-logo.png' align='right' border='0' /></a>A Facebook application that allows you to publish your audio and video stream for others to view and listen. This is a zero configuration service that uses Adobe Stratus for peer-to-peer media streams. View the [source code](/examples/ichatnow/index.html) of the single HTML/JavaScript page for this project. _Keywords_: video streaming, facebook, adobe stratus.<br />
  * [Random-Face](http://random-face.appspot.com/): This is a chatroulette-type application built using the Flash VideoIO component on Adobe Stratus service and Python-based Google App Engine. This site is just a demonstration of how such services can be built using the generic Flash-VideoIO component. It uses the Channel API of the App Engine for asynchronous XMPP-style messaging and events. You can view the source code of two files, [index.html](/examples/random-face/with-channel-api/index.html) that renders the front end user interface and [main.py](/examples/random-face/with-channel-api/main.py) that forms the back-end service. _Keywords_: random video call, google app engine, adobe stratus, channel api.<br />
  * [Public-Chat](http://public-chat.appspot.com/) ([auto](http://public-chat.appspot.com/?auto=true)): <a href='http://public-chat.appspot.com/?auto=true'><img src='http://myprojectguide.org/p/flash-videoio/publicchat-logo.png' align='right' border='0' /></a>This is a multi-party audio, video and text chat application built on top of Python-based Google App Engine and using Channel API for asynchronous instant messaging and presence. This site is a demonstration of how such services can be built using the generic Flash-VideoIO component. It allows public and hidden chat rooms, user listing, and persistent messages. You can publish your video stream or play the streams of others who are publishing, by a click on checkbox items. Developers can see the source code files: [index.html](/examples/public-chat/with-channel-api/index.html) is the front-end user interface, [webtalk.js](/examples/public-chat/with-channel-api/static/webtalk.js) is the client side Javascript to do signaling, and [main.py](/examples/public-chat/with-channel-api/main.py) is the back-end service code. **This application works on Internet Explorer.** Older version with Ajax/polling based source code files are also available under `with-polling` directory in SVN. Please see the [demo video on youtube](http://www.youtube.com/watch?v=Q4RR0jseXN0) on how to use the system. Alternatively, please see the [demo video](https://github.com/theintencity/flash-videoio/blob/download/demo-public-chat.mp4) using [VLC](http://www.videolan.org/vlc/) media player on how to get started. _Keywords_: video conference, google app engine, adobe stratus, channel api, ajax polling.<br />
  * [Video Office](http://flash-videoio.appspot.com/office/kundan10@gmail.com/): <a href='http://flash-videoio.appspot.com/office/kundan10@gmail.com/'><img src='http://myprojectguide.org/p/flash-videoio/videooffice-logo.png' align='right' border='0' /></a>This is a web-based video office that allows others visit my office to talk to me. It uses Adobe Stratus for peer-to-peer media streams, Google App Engine for back-end service, its Channel API for asynchronous events, and its XMPP module for interacting with Google chat. When someone visits my video office, I get a Google chat notification, so that I can open my office for live video chat. The application allows you to create your own video office using your Google Mail account. The source code is available in SVN under `django-apps` directory. _Keywords_: video office, video call, adobe stratus, google app engine, channel api, xmpp.<br />
  * [Talk to Experts](http://flash-videoio.appspot.com/experts/): This is an extension of Video Office project, that allows you to also search for experts based on a topic, see their calendar, sign up to talk to them in their calendar, and video chat with them in real-time. It uses Adobe Stratus for peer-to-peer media streams, Google App Engine for back-end service, its Channel API for asynchronous events, and its XMPP module for interacting with Google chat. The can get notified on Google chat when a visitor wants to chat with him. The application allows you to sign up as an expert on some topic, and potentially monetize your time giving expert advice. The source code is available in SVN under `django-apps` directory. _Keywords_: video office, talk to experts, video call, adobe stratus, google app engine, channel api, xmpp.<br />
  * [SIP in Javascript](https://github.com/theintencity/sip-js): This is an implementation of SIP in Javascript to promote endpoints in the browser without depending on the server-side SIP translation. It uses other projects to implement the networking and media component of the demonstration SIP phone in the browser. The media device access and display is accomplished by the Flash VideoIO component running in the browser. Please see [the demo video](http://www.youtube.com/watch?v=tfwmBgJHpWs) of a web-based SIP phone. _Keywords_: Web-based, SIP phone, SIP in Javascript.<br />
