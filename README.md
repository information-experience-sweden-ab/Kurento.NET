# Kurento.NET
Kurento client C# implementation
# About Kurento
Kurento is an open source software project providing a platform suitable for creating modular applications with advanced real-time communication capabilities. For knowing more about Kurento, please visit the Kurento project website: https://www.kurento.org.
# Project structure

+ KMSCreator
   + Generate C# Kurento client based on kms-core, kms-elements, kms-filters provided by kurento
+ Kurento.NET
   + Kurento C# client library
+ KurentoDemo
   + A few simple examples of using kurento

# how to use

1. NuGet references
   > ```Install-Package Kurento.NET```
2. Use
 ```
    var client = new KurentoClient("ws://your kurento ip:8888/kurento", logger);
    var pipeline = client.Create(new MediaPipeline());
    var webRtcEndPoint = client.Create(new WebRtcEndpoint(pipeline));
```

# Instance

Simple Many-to-Many Liezi
(https://github.com/oBears/KurentoDemo)
