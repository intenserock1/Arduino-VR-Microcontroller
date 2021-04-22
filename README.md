# Arduino-VR-Microcontroller
Creation of a VR controller using an Arduino Nano 33 IoT, VRidge, Riftcat, and a C# Server

This code was used to help design a VR controller using an Arduino Nano 33 iot, Arduino integrated development environment for a client, Visual Studio integrated development environment for a C# Server, VRidge and Riftcat, along with other physical parts. The Arduino client connects with a C# Server using TCP first, and then UDP is used to send packets containing controller information to the C# Server. The C# Server sends this information to VRidge, which sends it to Riftcat, which is used in accordance with SteamVR.

