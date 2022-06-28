Personal Dashboard (Chrome Extension)

This program is a customized dashboard that I made using a few different API's. 


When the user opens a new tab in google chrome, instead of it being the default chrome page. The application 
renders a customized dashboard featuring a randomized (chicago themed) background, 
the latest crypto price for Shiba COIN, the local time, as well as the local Weather.


I avoided using aysnc and await in my API fetch calls just for the sake of simplicity. 

In order to be able to have a changing/dynamic background I had to access the document's body via Javascript,
specifically the background image property for the body via body.style.backgroundImage. Which I set to the random 
image url provided to us by the data we accessed UnSplash API.

I used the catch method in case there was an issue with the API fetch that just rendered a preset image. 




