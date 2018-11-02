## Last Few Weeks Accomplishments

The previous few weeks have seen tremendous progress both in terms of deciding what paths to take LATE down and concrete work on LATE.
As a team we continued to meet weekly on Saturdays for two hours in my hall's classroom. (Bray) We are actively using GitHub's project boards and issues to 
stay up to date on progress and communicate with each other. The back end and front end teams have solidifed and now everyone knows their
focus in terms of the project.

## SPA
The back end team (mainly me) started developing the backend routes for the entire website (its a Node backend using KoaJS) which meant it was 
for the most part a traditional web server setup serving rendered pages. The main page we knew would have to be dynamic so we started looking
into using VueJS for just the "dashboard" page. This proved difficult and we realized that eventually most of the site would be sort of 
dynamic due to the nature of our time-sensitive use cases.

I then suggested we turn the entire application into a VueJS Single Page Application, which would require a rewrite and would make it much more
complicated for front end to learn and work with, but it would much better suit our use case, and we would learn something new.

We agreed and I then spent the next few days totally revamping the site to be a Vue SPA with the Koa backend serving just the authentication
system and the API for LATE.
