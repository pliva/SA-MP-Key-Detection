# SA-MP-Key-Detection
It's c# application that allows you to connect to SA:MP server and send key when you press it

In application source you need to change IP:Port and adapt them for your server.

  private const int port = 7777;
  private const string IPasdress = "127.0.0.1";

In SA:MP filterscript you need to setup only PORT:
#define PORT 7777
