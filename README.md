# VR-Casting

Oculus has created a means to cast the Oculus Go to a mobile phone. For Oculus Go casting to work, make sure both the headset and your phone or tablet are on the same WIFI network. 

Oculus Go Casting using Javascript, Three.js and WebVR

Open-source method for casting the Oculus Go to any Web connected device from anywhere. Instead of streaming the Oculus Go content to a remote device, only control data is sent using AJAX. The data sent contains a control flag followed by the camera position (x, y, z) and the camera rotation (x, y, z).

Casting the Oculus Go from Oculus:
* Slow casting over slower networks.
* No audio. 
* Only works on mobile devices on the same network.
* Can’t cast development builds.

Casting the Oculus Go from open-source code:
* High speed casting by sending control information.
* Audio can be implemented over the communications protocol.
* Works on all devices on any network.
* Cast development builds.

Link to example: www.pmsmicro.com/oculusgocasting.html
