# Lab 8 - Starter
**Name: Katie Ngo** (Completed Individually)

[View Deployed Site](https://kttngo.github.io/Lab8_Starter/)

## Question: How are graceful degradation and service workers related?
**Answer:** Graceful degradation and service workers are related because they both aim to provide users with a smooth, stable experience even under limited network conditions. Graceful degradation is the idea that an application should still provide its core functionality when advanced features fail. Instead of it completely breaking, it "degrades" into a simpler, functional version. Service workers support graceful degradation by acting as a middle layer between the web application and the internet. When the network becomes unavailable, the service worker provides the cache versions instead. This allows the app to continue operating smoothly using local resources rather than making the user wait per request.