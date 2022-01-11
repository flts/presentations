# Intro to Azure Container Apps

Short introduction of the new offering Azure Container Apps.
Simple weather application in this case showing how Container Apps within an Container App Environment can communicate out-of-the-box (so not using Dapr).

In the file `demo.azcli` you can find the different steps needed to setup an environment, build and deploy both the Frontend and Backend API projects as Container Images.

In the web project the following files can be changed to add the Weather Forecast page and APi request to the second Container App. 
- src/WebApp/Program.cs
- src/WebApp/SharedNavMenu.razor
- src/WebApp/Pages/Weather.razor

- src/WebApp/Pages/Index.razor (optionally change V1 to a higher number)