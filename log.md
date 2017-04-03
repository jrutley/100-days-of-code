# 100 Days Of Code - Log


### Day 80 April 2, Sunday

**Today's Progress**: 
Set up Node backend. Transferring "mongo" data from backend

**Thoughts**  
I had a little bit of trouble with the form data and the this variable... I was using an arrow function, which caused this to be the "proper" thing and not the class that I was expecting. 

The Node piece took a little bit of work for proxying the connection, but it was just a learning curve -- things like needing to know in the development window that it was going to show the original request address... it's totally unaware that it's being proxied. After some trial-and-error I could see what it was doing

**Links to work** .   
1. [Dynamic Form Generation - not a public link](https://git-codecommit.us-east-1.amazonaws.com/v1/repos/dynamicFormGeneration) . 


### Day 79 April 1, Saturday

**Today's Progress**: 
Got form successfully set up. Added Bootstrap

**Thoughts**  
It's nice to have the ability to import a package and just have Stuff Just Work, which happened in the case of Bootstrap.

**Links to work** .   
1. [Dynamic Form Generation - not a public link](https://git-codecommit.us-east-1.amazonaws.com/v1/repos/dynamicFormGeneration) . 


### Day 78 March 31, Friday

**Today's Progress**: 
New Vue app prototype for work

**Thoughts**  
We're probably not supposed to post work-related stuff, but I got to work on it all day and it's really AWESOME!! plus I may have worked a little bit overtime on it

**Links to work** .   
1. [Dynamic Form Generation - not a public link](https://git-codecommit.us-east-1.amazonaws.com/v1/repos/dynamicFormGeneration) . 


### Day 77 March 30, Thursday

**Today's Progress**: 
Still in progress adding the same Karma spec to front end

**Thoughts**  
Angular's testing components are really complicated. All I want to do is get this product list to show up in the test. It took me quite a long time before I realized that my product list wasn't updating due to a lack of change event, but now it'll be a challenge to make that test pass

**Links to work** .   
1. [Review Management](https://github.com/jrutley/ReviewManagement) . 


### Day 76: March 29, Wednesday

**Today's Progress**: 
Adding Karma specs to front end

**Thoughts**  
It's a bit hard for me to get into the right frame of mind... just getting started is the key. There's still a bunch of hoops that I seem to need to jump through, but a quick Google or reading the docs get me up quickly. I'm sure a lot of this will make more sense once I get more accustomed to it

**Links to work** .   
1. [Review Management](https://github.com/jrutley/ReviewManagement) . 



### Day 75: March 27, Monday

**Today's Progress**: 
Lots of Angular learning today. Modifying the default app to suit my purposes

**Thoughts**  
There is a lot to take in with Typescript and Angular 2. The Heroes tutorial takes a long time to go through...holy moley. I had a few missteps on the way, but made it most of the way through

**Links to work** .   
1. [Review Management](https://github.com/jrutley/ReviewManagement) . 



### Day 74: March 26, Sunday

**Today's Progress**: 
More Angular learning, EF Core learning as well

**Thoughts**  
I spent quite a bit of time today looking at documentation, when I realized that I hadn't written any code. So now I've created a SQL backend all in .NET Core using SQLite since I'm back on the Mac. I haven't looked to see if SQL Server is available for Mac too. The .NET Core code looks pretty easy to pick up overall after having done .NET 4.5 for quite some time. There's a few differences here and there, like wiring up DI, it's built-in to ASP.NET Core. The documentation that is used doesn't explicitly use an interface to access the DB. I guess somebody realized that DbContext implements the Repository pattern. For testing purposes, there's an in-memory DB that's available. I'm going to try using that just for something to compare against.

**Links to work** .   
1. [Review Management](https://github.com/jrutley/ReviewManagement) . 


### Day 73: March 24, Friday

**Today's Progress**: 
No actual progress other than learning more about Angular 2

**Thoughts**  
I got a fairly good understanding of the components and router. Next up I think will be services and backend support. Tutorials probably don't count, but that's all I had time for today.

**Links to work** .   
0. None, unfortunately

### Day 72: March 23, Thursday

**Today's Progress**: 
Finding out that .gitignore is too strict for this project 

**Thoughts**  
I spent some time marvelling at how well this app works so well from any OS that runs .net core that I considered moving back to my Mac to work on this. I found out the hard way that a couple of vendor js files located in the dist folder haven't been added to the repository due to a line in the .gitignore file. Once I get that resolved, I'll be able to merrily go down the Angular path

**Links to work** .   
1. [Review Management](https://github.com/jrutley/ReviewManagement) . 


### Day 71: March 22, Wednesday

**Today's Progress**: 
Basic ASP.NET Core / Angular 2 app

**Thoughts**  
Getting projects up and running in ASP.NET Core + Angular 2 is easy if you have the right sources (https://jonhilton.net/2017/02/21/create-a-vs2017-angular-2-and-net-core-site-using-the-command-line/). I'm eager to see if the development cycle is sped up here with regard to hot reloading and compiling compared to my current day job

**Links to work** .   
1. [Review Management](https://github.com/jrutley/ReviewManagement) . 


### Day 70: March 20, Monday

**Today's Progress**: 
Added percent to calculator

**Thoughts**  
I'm pretty drained today, so I had to cut this one short. Percent could open up a can of worms, now that I'm adding parentheses to the mix. I read about functional setState, and that is really useful to know. Also, I deployed the app locally just using serve -- lots of built-in ways to deploy this, which is awesome

**Links to work** .   
1. [Online calculator](https://github.com/jrutley/calc) . 

### Day 69: March 19, Sunday

**Today's Progress**: 
Added more functionality to calculator. Fixed a bunch of bugs, added the clear ability

**Thoughts**  
There are way more edge cases than expected. I'm discovering new ones every minute. Haven't covered % or +/- yet either.

**Links to work** .   
1. [Online calculator](https://github.com/jrutley/calc) . 



### Day 68: March 18, Saturday

**Today's Progress**: 
Added more functionality to calculator. It now processes basic math equations. On to clear button and edge cases!

**Thoughts**  
This went smoother than expected. Eval worked like a charm. BDD is proving very useful with regard to preserving accuracy of tests

**Links to work** .   
1. [Online calculator](https://github.com/jrutley/calc) . 


### Day 67: March 17, Friday

**Today's Progress**: 
Refactored unit tests to use Enzyme. Finished the entry for a single number

**Thoughts**  
I got a tweet reply from Dan Abramov pointing me in the right direction for the Enzyme unit tests... it turned out that there is Enzyme documentation that works with create-react-app after all right on the site. I refactored and now it works quite nice, though the way I had it before was more "pure" in the functional sense.

**Links to work** .   
1. [Online calculator](https://github.com/jrutley/calc) . 


### Day 66: March 16, Thursday

**Today's Progress**: 
Added ability to click buttons to make the digits display on the screen. Added unit tests to test button logic

**Thoughts**  
It's tough when a group of developers tries to make things simple e.g. create-react-app if it's missing something, because you're not necessarily familiar with the internals of it. Apparently I need to use Enzyme if I want to make my tests work as expected in React, and not do what I did by extracting what I want to test into a new function. In the end, what I did was simpler, but it's more verbose and otherwise exposes a "public" function.
If I want to use Enzyme, there's nothing about how to use it with create-react-app, so following their instructions, I don't know if it would work or not. Usually in a case like this it's more of a "not"

**Links to work** .   
1. [Online calculator](https://github.com/jrutley/calc) . 


### Day 65: March 15, Wednesday

**Today's Progress**: 
Refactoring on the Tic Tac Toe game

**Thoughts**  
I moved some elements to more logical places component-wise. Much cleaner code now. Yesterday I had trouble with the spread operator, but I tried again and it worked first time, like magic.

**Links to work** .   
1. [Tic tac toe](https://codepen.io/jrutley/pen/jBLXmP) . 


### Day 64: March 14, Tuesday

**Today's Progress**: 
Started to break the calculator down into components... found that I could use a little bit of tutorial on React

**Thoughts**  
Going through the tic tac toe tutorial was eye opening. I love the principles behind React, but I also find it a bit verbose... will need to build a few apps with it before I can pass judgement on it.

**Links to work** .   
1. [Calculator](https://github.com/jrutley/calc) . 
2. [Tic tac toe](https://codepen.io/jrutley/pen/jBLXmP) . 

### Day 63: March 13, Monday

**Today's Progress**: 
Trying out React for the calculator

**Thoughts**  
So far React is easy and has lots of tooling -- way more than vue.js. I didn't get as much done as I hoped, but at least the buttons line up

**Links to work** .   
1. [Calculator](https://github.com/jrutley/calc) . 


### Day 62: March 12, Sunday

**Today's Progress**: 
Filling in all data properly

**Thoughts**  
Travelling makes it a bit rough to get at my coding, so I'm back after a short hiatus. Inspired by https://egghead.io/lessons/javascript-use-javascript-es6-generators-with-promises-to-handle-async-flows I refactored to use a generator and a coroutine. 10 fewer lines of code, and more clear. I'm really happy with the results.


**Links to work** .   
1. [Twitchviewer@Github](https://github.com/jrutley/twitchviewer) . 
2. [Twitchviewer@Heroku](https://twitchviewer.herokuapp.com) . 

### Day 61: March 9, Thursday

**Today's Progress**: 
Filling in all data properly

**Thoughts**  
I'm wondering if I'm chaining those Promises together properly. They look like they were treated like regular callbacks... perhaps I should flatten them. Otherwise things went quite smoothly today


**Links to work** .   
1. [Twitchviewer@Github](https://github.com/jrutley/twitchviewer) . 
2. [Twitchviewer@Heroku](https://twitchviewer.herokuapp.com) . 

### Day 58-60: March 6-8, Monday-Wednesday

**Today's Progress**: 
Using the Twitch API to display stream data

**Thoughts**  
I struggled again with getting data into the Vue model.. especially with the Promises. It turned out that I had to populate an item with the result of the Promise.


**Links to work** .   
1. [Twitchviewer@Github](https://github.com/jrutley/twitchviewer) . 
2. [Twitchviewer@Heroku](https://twitchviewer.herokuapp.com) . 


### Day 57: March 5, Sunday

**Today's Progress**: 
Deployed app to Heroku

**Thoughts**  
I thought it would be less complicated than that to get a deployment to Heroku. Bare-bones express app + webpacked code in the dist folder. I probably should have used https://medium.com/@sagarjauhari/quick-n-clean-way-to-deploy-vue-webpack-apps-on-heroku-b522d3904bc8#.aa37icn6i but ended up moving all dependencies as production dependencies.


**Links to work** .   
1. [Twitchviewer@Github](https://github.com/jrutley/twitchviewer) . 
2. [Twitchviewer@Heroku](https://twitchviewer.herokuapp.com) . 


### Day 56: March 4, Saturday

**Today's Progress**: 
Got Bootstrap styles to show up properly.. finally!

**Thoughts**  
I made some more sense of webpack, and actually understood what was going on when I had errors, so that is a plus... also I found out in the end that I didn't need to add an entry for sass-loader because the vue loader already takes care of Sass. Perhaps if I want to use Pug, I'll have a clue what to do. 
I finally found out why the table styles weren't loading properly. To start off, Bootstrap 4 does not have the themes when you install with npm. Very important, that!
So I installed Bootstrap 3 instead, and that caused an issue when I tried to run it: fonts. More research required to fix that: (file-loader)
Lastly, I got the icons working, but the tables still weren't. Eventually I compared what I had written with the Bootstrap sample, and it turns out I was missing thead/tbody; I had th and tr, which is probably outdated.

**Links to work** .   
https://github.com/jrutley/twitchviewer


### Day 55: March 3, Friday

**Today's Progress**: 
Learned some more about Webpack

**Thoughts**  
After taking the time to sit back instead of copying and pasting *.config.json, this makes a lot more sense. Also, I played around with a few vue.js bits, adding and removing, so it doesn't look like I accomplished a whole lot.
I'm having trouble with Bootstrap though... I'm not able to make the background colours appear, even though I think I'm doing what's in the documentation

**Links to work** .   
https://github.com/jrutley/twitchviewer


### Day 54: March 2, Thursday

**Today's Progress**: 
Not even a little bit

**Thoughts**  
I got lost in the sea of webpack, vue components, and more webpack. I tried to load Bootstrap but couldn't make it load.

**Links to work** .   
https://github.com/jrutley/twitchviewer


### Day 53: March 1, Wednesday

**Today's Progress**: 
More AWS config, basic Vue app

**Thoughts**  
Downloaded and installed the AWS elastic beanstalk command-line tools. I'll probably do a simple deployment tomorrow. Vue app is up and running, but I'm seriously lacking inspiration for how to go about it. I need to add the Bootstrap JS and CSS libraries and it's not obvious where to do it except right inline on the Vue template. I'm starting to think Vue is a little complicated when bringing in Webpack and all its friends, but that seems to be par for the course for a front-end JS framework

**Links to work** .   
https://github.com/jrutley/twitchviewer



### Day 52: February 28, Tuesday

**Today's Progress**: 
Not much... some AWS config

**Thoughts**  
Deploying to AWS is a heavy endeavour in the beginning. I did a deployment of something else before but it was quite some time ago and it appears that much is forgotten. I spent some time trying to figure out how the Vue app gets activated.

**Links to work** .   
(Not posting twitch.tv viewer to Github yet - only basic app ATM)


### Day 51: February 27, Monday

**Today's Progress**: 
FreeCodeCamp Advanced Algorithm Scripting

**Thoughts**  
Classic problems to solve, with a bit of a twist. JavaScript Date objects are a bit of a pain. Also, I started setting up the Twitch app using vue.js but the vue-cli app was really complicated when using webpack. Much simpler to use the webpack-simple option. I'm going to push forward with that, and make sure I get proper unit testing and such.

**Links to work** .   
1. [Friendly Date Ranges](https://www.freecodecamp.com/challenges/friendly-date-ranges)
2. [Make a Person](https://www.freecodecamp.com/challenges/make-a-person)
3. [Map the Debris](https://www.freecodecamp.com/challenges/map-the-debris)
4. [Pairwise](https://www.freecodecamp.com/challenges/pairwise)
(Not posting twitch.tv viewer to Github yet - only basic app ATM)

### Day 50: February 26, Sunday

**Today's Progress**: 
FreeCodeCamp Advanced Algorithm Scripting

**Thoughts**  
Halfway already. These algorithms are more of the same. Classic problems to solve, with a bit of a twist.

**Links to work** .   
1. [Inventory Update](https://www.freecodecamp.com/challenges/inventory-update)
2. [No repeats please](https://www.freecodecamp.com/challenges/no-repeats-please)

### Day 49: February 25, Saturday

**Today's Progress**: 
FreeCodeCamp Advanced Algorithm Scripting

**Thoughts**  
Finally solved it, though I had to work around that array bug

**Links to work** .   
1. [Exact change](https://www.freecodecamp.com/challenges/exact-change)


### Day 48: February 24, Friday

**Today's Progress**: 
FreeCodeCamp Advanced Algorithm Scripting (almost one problem)

**Thoughts**  
Still haven't solved it. Part of my problem appears to be a FreeCodeCamp bug in array expansion...? JS bug? Seems unlikely. When I expand a certain array, it shows [0.01] as a value for example, but when I expand it, it shows array length of 0. ???

**Links to work** .   
1. [Exact change](https://www.freecodecamp.com/challenges/exact-change)


### Day 47: February 23, Thursday

**Today's Progress**: 
FreeCodeCamp Advanced Algorithm Scripting (almost one problem)

**Thoughts**  
This exact change problem is the toughest one yet, considering it's the first time I haven't finished one. I'm close. So close.

**Links to work** .   
1. [Exact change](https://www.freecodecamp.com/challenges/exact-change)


### Day 46: February 22, Wednesday

**Today's Progress**: 
FreeCodeCamp Advanced Algorithm Scripting

**Thoughts**  
It's tricky to code when you're in front of the TV. I got thrown off on this test because it said that I had all the right values, but I had the wrong number of values. A console.log quickly showed me that I had to de-dupe some arrays before processing.

**Links to work** .   
1. [Symmetric Difference](https://www.freecodecamp.com/challenges/symmetric-difference)


### Day 45: February 21, Tuesday

**Today's Progress**: 
FreeCodeCamp Intermediate and Advanced Algorithm Scripting

**Thoughts**  
The "truthy" problems always get me... otherwise these are straightforward imperative exercises. I try to use functional when I can, but in some cases, like the record colletion one, it's pretty much set up to do it imperatively.

**Links to work** .   
1. [Steamroller](https://www.freecodecamp.com/challenges/steamroller)
2. [Binary Agents](https://www.freecodecamp.com/challenges/binary-agents)
3. [Everything be true](https://www.freecodecamp.com/challenges/everything-be-true)
4. [Arguments optional](https://www.freecodecamp.com/challenges/arguments-optional)
5. [Validate US Telephone Numbers](https://www.freecodecamp.com/challenges/validate-us-telephone-numbers)
6. [Record Collection](https://www.freecodecamp.com/challenges/record-collection)

### Day 44: February 20, Monday

**Today's Progress**: 
FreeCodeCamp Intermediate Algorithm Scripting

**Thoughts**  
I finished the ones I struggled with, and more

**Links to work** .   
1. [Spinal Tap Case](https://www.freecodecamp.com/challenges/spinal-tap-case)
2. [Sum odd fibonacci numbers](https://www.freecodecamp.com/challenges/sum-all-odd-fibonacci-numbers)
3. [Sum all primes](https://www.freecodecamp.com/challenges/sum-all-primes)
4. [Smallest common multiple](https://www.freecodecamp.com/challenges/smallest-common-multiple)
5. [Finders Keepers](https://www.freecodecamp.com/challenges/finders-keepers)
6. [Drop It](https://www.freecodecamp.com/challenges/finders-keepers)

### Day 43: February 19, Sunday

**Today's Progress**: 
FreeCodeCamp Intermediate Algorithm Scripting attempts to complete

**Thoughts**  
By the time I started, I was already too tired and was unable to focus. I tcried implementing 3 of the code camp exercises, but didn't end up solving any of them

**Links to work** .   
1. [Spinal Tap Case](https://www.freecodecamp.com/challenges/spinal-tap-case)
2. [Sum odd fibonacci numbers](https://www.freecodecamp.com/challenges/sum-all-odd-fibonacci-numbers)
3. [Sum all primes](https://www.freecodecamp.com/challenges/sum-all-primes)

### Day 42: February 18, Saturday

**Today's Progress**: 
FreeCodeCamp Intermediate Algorithm Scripting half completed

**Thoughts**  
The Boolean exercise threw me for a bit, but everything else was pretty straightforward

**Links to work** .   
1. [Sum all numbers in a range](https://www.freecodecamp.com/challenges/sum-all-numbers-in-a-range)
...
11. [Convert HTML entities](https://www.freecodecamp.com/challenges/convert-html-entities)


### Day 41: February 16, Thursday

**Today's Progress**: 
Completed the Wikipedia viewer.

**Thoughts**  
 Couldn't figure out how to load Wikipedia pages... was looking for a URL, not realizing that you can just link directly with the ID. I used https://coolors.co/f4a442-e2efde-afd0bf-808f87-9b7e46 for my colour scheme, and it took surprisingly little time to get the hover to work for changing the colours. Had a bit of trouble with the template and string interpolation, where I ended up posting the http link to wikipedia + url on every result, which I think is wasteful. ah well.

**Links to work** .   
1. [Wikipedia Viewer](http://codepen.io/jrutley/pen/XpgEbP)

### Day 40: February 15, Wednesday

**Today's Progress**: 
Almost done the Wikipedia viewer.

**Thoughts**  
 I finally figured out how to navigate through the Wikipedia API, then moved on to getting some results into the list. In the end, I had to ultimately iterate over the properties, because it looks like Wikipedia returns the pages as individual keys, not in an array. After that was done, it took me a couple minutes to figure out why the results weren't updating.. and that's because I was using an ajax call and had to store "this" prior to the call.
 Only thing left to do on the viewer is display the titles+description instead of just the title, and format it nicely

**Links to work** .   
1. [Wikipedia Viewer](http://codepen.io/jrutley/pen/XpgEbP?editors=1010)


### Day 39: February 14, Tuesday

**Today's Progress**: 
I updated my portfolio a little bit, then moved back on to the Wikipedia viewer.

**Thoughts**  
 I started to get the hang of vue.js... awesome! It turns out the Wikipedia viewer is wayyyy more complex than I thought. I expected it to take two minutes to get what I needed, but there's so many options.

**Links to work** .   
1. [Wikipedia Viewer](http://codepen.io/jrutley/pen/XpgEbP?editors=1010)


### Day 38: February 13, Monday

**Today's Progress**: 

**Thoughts**  
Finished my Valentine webpage. I used http://bennettfeely.com/clippy/ for drawing the heart, which was immensely useful... still having trouble with basic things like centering divs and relative positioning. Shoutout to csswarp.eleqtriq.com for helping me make a curved path.

**Links to work** .   

1. [Happy Valentine's](https://carrie-valentine.herokuapp.com/)
2. [Link to Github](https://github.com/jrutley/valentine)


### Day 37: February 12, Sunday

**Today's Progress**: 

**Thoughts**  
Being away from home this week, I thought I'd make a CSS Valentine's Day card for my wife. Starting out with drawing a heart

**Links to work** .   

1. unfortunately this is empty, because I'm too tired at the moment to remember how to make a bare repo in order to push to Github.

### Day 36: February 11, Saturday

**Today's Progress**: 

**Thoughts**  
Just started on the Wikipedia search tool. Thought I would try out vue.js. Seems more complicated than I thought it would be. I can see how I would want to return a list of entries that have been called by the Wikipedia API, but I can't seem to make the connection of entering in the search bar and clicking Enter. I guess I have to just do it via an on-click event, and then submit for feedback to see if I did it right or not.

**Links to work** .   

1. [Wikipedia](http://codepen.io/jrutley/pen/XpgEbP)


### Day 35: February 9, Thursday

**Today's Progress**: 

**Thoughts**  
Quick touchup to finish the weather page. It could use some more styling, but oh well. On to the Wikipedia viewer! Looking at vue.js to see it it's a good fit.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)
2. [Deployed](https://intense-sea-60365.herokuapp.com)

### Day 34: February 8, Wednesday

**Today's Progress**: 

**Thoughts**  
Found a way forward to fix the hotlinking error... phew! Do the request on the server side using the "request" library, telling it to not follow redirects. Tomorrow I'll have it move on to the next image if it encounters one. On the client side, using data source saved my bacon.
Since it takes so long for geolocation, I had to add a "loading" page.


**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)
2. [Deployed](https://intense-sea-60365.herokuapp.com)


### Day 33: February 7, Tuesday

**Today's Progress**: 

**Thoughts**  
I got a hotlinking error when trying to load an image, so I thought I'd try to load the images and check for 302 errors, but I'm getting CORS errors instead. :(


**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)
2. [Deployed](https://intense-sea-60365.herokuapp.com)


### Day 32: February 6, Monday

**Today's Progress**: 

**Thoughts**  
I ended up going back to the standard geolocation. Lesson learnt.  
Also, I added a loading screen and a fallback to loading from IP -- in doing so, it returns Toronto for me, mainly since that's where the interconnection is. Annoyingly, the openweather API returns really tiny neighbourhoods rather than the actual town/city, so I had to double check just exactly where Sinclair Shore is. Since in the fallback method it actually returns Toronto, I can pass that along and do a lookup by city name.
Otherwise, I could make a call to Google's geocode API to retrieve the locality, then filter the results from the weather API.  
Maybe I'll do that next.
Loading page is pretty ugly and bare. That could be spiced up a bit.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)
2. [Deployed](https://intense-sea-60365.herokuapp.com)


### Day 31: February 5, Sunday

**Today's Progress**: 

**Thoughts**  
Successful deployment to Heroku. This is when I find out that the geolocation that is performed by Google is done server-side. Ashburn US every time.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)
2. [Deployed](https://intense-sea-60365.herokuapp.com)

### Day 30: February 4, Saturday

**Today's Progress**: 

**Thoughts**  
I finished but I'm not really happy with the front end portion because of no unit/integration tests and global variables on the front end. I'm tempted to just move on though and use cycle.js or React for my next project. Also, time to deploy to Heroku.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)


### Day 29: February 3, Friday

**Today's Progress**: 

**Thoughts**  
Long day of travel today, so I cut it short a bit. I still managed to show a night background when it's actually nighttime, and did some styling, so it's not a total gong show.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)

### Day 28: February 2, Thursday

**Today's Progress**: 

**Thoughts**  
A little slow today, mainly due to lack of sleep, but I managed to add the current city to the page. So far this looks straightforward, though the weather result of "clear sky" shows a bright and sunny day even though it's the middle of the night. Fortunately the weather API returns the sunrise and sunset in Unix time, so I can leverage that to append "night" to the end of the image search.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)

### Day 27: February 1, Wednesday

**Today's Progress**: 

**Thoughts**  
A significant amount of my time was spent looking at API documentation rather than writing any actual code. In the end, I needed to implement some form of error handling, and the best way to do that as far as I can see is to use Promises, so I've moved the weather app over to use them

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)

### Day 26: January 31, Tuesday

**Today's Progress**: 

**Thoughts**  
As I was looking for alternatives to Google's image search, I stumbled across a page with a working example of how the imge search works. Now I'm finally able to set the background to be an image.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)


### Day 25: January 30, Monday

**Today's Progress**: 

**Thoughts**  
Google's image search is not exactly what I was hoping for. I wanted to essentially call Google's API and get the results that are on images.google.com. Instead we have to provide a custom search engine key, which ends up giving radically different results. Ah well.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)


### Day 24: January 29, Sunday

**Today's Progress**: 

**Thoughts**  
Being on a plane away from network access makes things a little tricky when you need to use an API. Having unit tests would have been a real bonus. I am getting the URL wrong for the weather function somehow, though it shows up in the browser. Turns out it's nice to have http:// in front (sigh).
I got the geo and weather information pulling successfully... next step is to pull an image from Google search API and set it as the background

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)


### Day 23: January 28, Saturday

**Today's Progress**: 

**Thoughts**  
Node isn't the easy and puffy environment that everyone makes it out to be... lots of manual steps and a million ways to do something, which does have appeal. Today I added a Google API partly because Geolocation fails on non-https in Chrome. Next steps are to integrate with the weather API

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)

### Day 22: January 26, Thursday

**Today's Progress**: Playing with gulp, livereload

**Thoughts**  
I fixed my popup window by dumping nodemon+express+browserstack in favour of livereload. It works how I want it to now, but I'm not sure if it'll work if I have multiple html pages

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)

### Day 21: January 25, Wednesday

**Today's Progress**: Playing with gulp, BrowserStack, nodemon

**Thoughts**  
Firefox works for Geolocation.  For a fallback, I may try to query for the IP address.  
I'm pretty much having to relearn all the Node + express stuff all over again. It's pretty Spartan, but there's tons of documentation everywhere. I've signed up for an API key from the weather location. If I use an MVC model, I can pull the requests from the API without exposing the keys to the outside world.  
Every time I restart Gulp, I get a new browser window popping up, and that's ... quite annoying.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)


### Day 20: January 24, Tuesday

**Today's Progress**: Fighting with geolocation

**Thoughts**  
I've decided to move to Heroku for the deployment, so that means figuring out how to host it locally. Geolocation isn't working unfortunately in Chrome... trying to access Google APIs when getting the location. I'm going to try using Firefox to see if I get the same result.
I've never used Gulp and BrowserStack before.. we'll see how that works out for me -- so far it's pretty good.

**Links to work** .   

1. [Weather App](https://github.com/jrutley/weather-app)

### Day 19: January 23, Monday

**Today's Progress**: Only just getting started on the weather app

**Thoughts**  
Looking for a free API tool for image searching is not working. I spent quite a bit of time working on that. I don't like having the secrets exposed in the website either. Maybe I'll use Heroku instead of Codepen for this one. I couldn't get the Ajax request to respond with anything either... need to look into that a bit

**Links to work** .   

1. [Weather App](https://codepen.io/jrutley/pen/XpgEbP)

### Day 18: January 22, Sunday

**Today's Progress**: Finished the quote generator to my satisfaction, more or less.

**Thoughts**  
SVG is not as responsive as I thought. It would have been nice to always get the text to show up in the middle of the yellow "bang" on the background, but I'm still not at that point yet.

**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)

### Day 17: January 21, Saturday

**Today's Progress**: Got the alignment of the quote generator down

**Thoughts**  
vh is my new CSS friend. That is all.

**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)


### Day 16: January 20, Friday

**Today's Progress**: Practically nothing

**Thoughts**  
Still lost in a bunch of nested divs. Particularly I'm having trouble centering the box on the page like I would like, while allowing it to auto adjust

**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)


### Day 15: January 19, Thursday

**Today's Progress**: Quote generator is now fully functional.

**Thoughts**  
Got the Twitter quote working. Started looking through the API documentation before finally stumbling across intents. I was not about to expose an API key on a public site.  Only thing left to do now is to make it pretty. I discovered https://startbootstrap.com/ and added the Agency css to my Portfolio page just to see what it looks like when it's not minified. Way longer than I thought.


**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)


### Day 14: January 18, Wednesday

**Today's Progress**: Tweaked the UI a little bit. Got the JS working

**Thoughts**  
I gave up on using http://api.forismatic.com/api/1.0/ because it was just not working. https://www.reddit.com/r/FreeCodeCamp/comments/4b1fox/free_api_for_random_quote_machine/ had promise, but ultimately ended up not working for me. There was an error response of "wrong method" despite following the documentation. Chuck Norris is much more accommodating though.
I added some Bootstrap markup to a button, but the margin won't expand to the bottom, so I have to check my options.

**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)

### Day 13: January 17, Tuesday

**Today's Progress**: Tweaked the UI a little bit. Started adding some JS

**Thoughts**  
I'm exhausted from a lack of sleep and work commitments, but just had to press on with this for a bit. I'm having a bit of trouble with the JSON call from Codepen. There's a success callback, but no error one -- silently failing.
The Bootstrap buttons are prettier than what I had with vanilla CSS... maybe I'll use Bootstrap for those.

**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)

### Day 12: January 16, Monday

**Today's Progress**: Started work on the random quote generator

**Thoughts**  
Most of my time was spent picking out backgrounds. I'm forgoing Bootstrap in favour of flexbox; it took me a couple of tries to get things centered. First I put the buttons on the bottom, but then decided to put them on the top, so that when someone presses the New Quote button, they don't have to move the mouse

**Links to work** .   

1. [Random Quote Generator](http://codepen.io/jrutley/pen/qRqOZj)
2. [^^^ on Github](https://github.com/jrutley/random-quote-generator)

### Day 11: January 15, Sunday

**Today's Progress**: Finished Basic Algorithm Scripting JS exercises and FreeCodeCamp's JSON APIs and AJAX series. Time to build the Random Quote Machine next!

**Thoughts**  
The Falsy Bouncer problem was a lot harder to solve than I thought... I had to resort to checking if x !== x for isNaN, otherwise I couldn't tell the difference between a string and NaN.  
I learned about the arguments property today. I don't see how it should be used unless you've designed yourself into a corner

**Links to work** .   
1. [Falsy Bouncer](https://www.freecodecamp.com/challenges/falsy-bouncer)  
2. [Free Code Camp JS up to Geolocation data](https://www.freecodecamp.com/challenges/get-geolocation-data)  

### Day 10: January 14, Saturday

**Today's Progress**: Continued Portfolio page and JS exercises

**Thoughts**  
I twiddled with the Portfolio page a little bit, adding some Flex container to try and even out the thumbnails... and then ripped through a bunch of Javascript exercises, trying to do them as functionally(?) as I can

**Links to work** .   
1. [Portfolio page](http://codepen.io/jrutley/pen/BpKzxL)  
2. [Free Code Camp JS up to Mutations](https://www.freecodecamp.com/challenges/mutations)  

### Day 9: January 13, Friday

**Today's Progress**: Continued Portfolio page

**Thoughts**  
I finished all the user stories for the portfolio page... to the letter. Needs more time to be "nice" though. I'll either work on that tomorrow, or move on :)

**Links to work** .   
1. [Portfolio page](http://codepen.io/jrutley/pen/BpKzxL)  

### Day 8: January 12, Thursday

**Today's Progress**: Continued Portfolio page

**Thoughts**  
Found a really awesome Bootstrap tutorial on w3schools that I'm going to check out tomorrow. Mostly today I spent fiddling with the nav bar and trying to see how it ticks. I've converted to using Pug because it's so much more terse than straight HTML.

**Links to work** .   
1. [Portfolio page](http://codepen.io/jrutley/pen/BpKzxL)  

### Day 7: January 11, Wednesday

**Today's Progress**: Started Portfolio page

**Thoughts**  
Had a massive design paralysis issue. Spent several hours figuring out what I want to do. Found a really cool site for design, and that's canva.com. In the end I've opted to go with a simple design for now, and get fancier as it gets more complete, if so desired  

**Links to work** .   
1. [Portfolio page](http://codepen.io/jrutley/pen/BpKzxL)  

### Day 6: January 10, Tuesday

**Today's Progress**: Worked toward my img-to-amp transformer

**Thoughts**  
I was tempted today for the first time to skip. Today was so draining, but I pushed through and made a little bit of progress on my conversion app. I can see the end of it; I just need to push a little bit more!

**Links to work** .   
1. [img-to-amp tool](https://github.com/jrutley/img-to-amp)  


### Day 5: January 9, Monday

**Today's Progress**: Finally done the Tribute page

**Thoughts**  
It turned out the carousel needed the same size of image. I spent some time resizing them, and now it looks good. I'm not totally happy with the inner text, but I don't think it's the end of the world; it got the point across.

**Links to work** .   
1. [Elon Musk Tribute page](https://codepen.io/jrutley/pen/RKPBpG)  

### Day 4: January 8, Sunday

**Today's Progress**: Almost finished the Tribute page

**Thoughts**  
I'm not sure how many hours I spent on this. It went from child-like, to bad, to worse, to hey I'm not too embarrassed by this. I've started to overcome all the options that are present in Bootstrap. And looking at examples on Bootstrap's page... it's like looking at a completely different language! I should record my current progress on this tribute page to show how far I've come.

**Links to work** .   
1. [Elon Musk Tribute page](https://codepen.io/jrutley/pen/RKPBpG)  


### Day 3: January 7, Saturday

**Today's Progress**: I've gone through all the jQuery exercises on FreeCodeCamp, and started on the Tribute page

**Thoughts**  
Working through exercises is a completely different beast from designing a webpage from scratch. This is a lot harder than I thought! I don't find the documentation for Bootstrap very good -- at least I haven't found a comprehensive list. There's a number of examples that are on the website that I have run View Source on, and after copying and pasting the same code into CodePen, it behaves differently.

**Links to work** .   
1. [Learn how Script tags and document ready work](https://www.freecodecamp.com/challenges/learn-how-script-tags-and-document-ready-work)  
...  
2. [Use jQuery to modify the entire page](https://www.freecodecamp.com/challenges/use-jquery-to-modify-the-entire-page)  
3. [Elon Musk Tribute page](https://codepen.io/jrutley/pen/RKPBpG)  

### Day 2: January 6, Friday

**Today's Progress**: I've gone through all the Bootstrap exercises on FreeCodeCamp.

**Thoughts**  
Had to cut it short today. Ultimate Frisbee night.

All these divs nested inside one another seems tedious and it quickly becomes cluttered with a small text input area. The benefits of using Bootstrap outweigh that complaint though, especially when it comes to using the grids. In the tutorial, they tell you to use col-xs-*, but how do we know to use that compared to the medium-sized ones? Isn't that the point of being responsive in the first place?
The layout that was built is also set up for the jQuery section coming up.

Also, Font Awesome is pretty cool.

**Links to work** .   
1. [Use the Bootstrap Grid to put elements side by side](https://www.freecodecamp.com/challenges/use-the-bootstrap-grid-to-put-elements-side-by-side)  
...  
2. [Using comments (yee haw!)](https://www.freecodecamp.com/challenges/use-comments-to-clarify-code)


### Day 1: January 5, Thursday

**Today's Progress**: I've gone through all the HTML exercises on FreeCodeCamp.

**Thoughts**  
Most of this was review, but there were a few things near the end that I had forgotten about. Next section is on Bootstrap, and that's totally new to me, so I'm looking forward to it.  

I also spent some time working on an app for a client, which should count, because I'm experimenting with functional programming and observable sequences in Javascript when there was really no need to. It was just to see if I can do it. Will probably migrate that to GitHub for visibility rather than in my Amazon CodeCommit repo.  

I ended up spending a few minutes going over a few of the Bootstrap lessons too.  

**Link(s) to work** 
1. [Say hello to html elements](https://www.freecodecamp.com/challenges/say-hello-to-html-elements) 
...
60. [Use rgb to mix colours](https://www.freecodecamp.com/challenges/use-rgb-to-mix-colors) 
...
72. [Warn users of a dangerous action](https://www.freecodecamp.com/challenges/warn-your-users-of-a-dangerous-action)
