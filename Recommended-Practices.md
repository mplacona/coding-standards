This section is for items that have not quite attained broad appeal or widespread adoption it takes to be called "best" practices, but are _recommended_ nonetheless.

## ASP.NET/Ajax Architecture
6. When developing the web services which will be consumed by your Ajax calls, in lieu of .asmx files, .aspx WebMethods or WCF .svc files, use RequestRouters, which you can load in the `Application_Start` method in `Global.asax.cs`. This keeps things cleaner and more RESTful, as you won't have to use file extensions in the URL.

## Go ahead... embrace the future!
1. In contrast to the IDesign standards, we recommend using the default parameters/named parameters features introduced in C# 4.0. It’s an opportunity to reduce the number of methods per class as opposed to overloaded methods. Those of us who have used JavaScript or VB or other languages that have this feature have typically missed it in C#, so it’s great to finally have it.