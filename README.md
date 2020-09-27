# Weather App

This week's project was to build a simple weather web app that shows today's weather and temperature, and a 5-day forecast using a weather API.

For this week I aimed for the blue level. And I also completed two of the red level requirements as below:

**🔵  Blue Level (Minimum Requirements)**

- Fetch data from the API using `fetch()` in JavaScript
- All required data should be present and fetched from the API
- The presentation of the data should be in a specified format.
- The page should work on mobile (mobile first!), tablet and desktop (Be responsive)

**🔴  Red Level (Intermediary Goals)**

- Change the colors of the page based on the weather. If the weather is warm – use warm colors. If the weather is colder, use cold colors. If you really want to push you CSS muscles you can even make a background gradient.
- Include visual indicators for the type of weather, cloudy/sunny/rainy/etc.

## The problem

I started out on monday doing mob-programming with some of my teammates. We all found that mob-programming was a good way to faster get over the first obstcles and uncertainties that often occur when starting a new project. For me personally it also helped a lot in that I didn't panic on my own, but rather got a foundation that I could continue to build on on my own. Because the available time to put into the project differs a lot between team-members, It was difficult to continue with the mob-programming for the remainder of the week. Because I also work half-time I felt quite behind on the project by the middle of the week compared to others. I got valuable help from teammates that had gotten further on the project though. 

I think this project was fun and I gained at least basic knowledge about how to fetch data from API:s. I would like to explore this further in the future. But overall I had to realize that I can only accomplish so much with the time and knowledge I have, so I try to be happy about the fact that I managed to finish the blue level on time. Overall I am still very much struggling with basic Javascript and I often got stuck when I tried to write functions. For exampla I tried to make a function with an if-statement to be able to show different backgrounds on weather today depending on time of the day (before/after sunrise/sunset), but got stuck on that so decided to change it to different colors depending on temperature. 
I have booked a code-coach session after the weekend to get some input on how to make the function mentioned above to work.

Also I feel I have to re-watch Max lecture from this week to learn more on how to better structure the code for this project. I didn't have time for that however, but might return to this project in the future and make it better and more advanced when my knowledge has improved.

I did a quite simple styling for this project, that didn't need too much tweaking to make it responsive.
I had some difficulties positioning the background image on .weathertoday using CSS background-size/object-fit/object-position. I couldn't get the pictures positioned where I wanted. I don't know why it didn't work, since I used this before on previous projects. I solved it by instead cropping the pictures, but they still don't have ideal position for bigger screens.

I noticed that for some reason the weather today is not quite aligned with weather forecast. But in the inspector-tool they seem to be aligned. They are the same vw, so I don't know why this happened. I tried to check if there were any margins that caused this, but didn't figure it out. UPDATE: I fixed it by setting 100vw on body. But still there is a problem in that the content isn't quite centered on the page, which I can't figure out how to solve.


## View it live

https://app.netlify.com/sites/youthful-ardinghelli-e80e81/
