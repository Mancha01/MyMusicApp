#How too change some of the default colors of chakra ui:
App Layout: Chakra ui

#Changing some default settings in chakra ui:
App Layout: Chakra ui

#N.B: The great thing about chakra ui is that we can modify it's default styles as much as we want unlike some other frontend frameworks.

#How to wrap all the components for a next js app within the \_app.tsx file:
App Layout: Creating Player Layout

#Chakra ui 'List' for creating a menu
App Layout: Creating the sidebar

#Creating part of the Nav menu:
Navigation: Create a ListNav with LinkBox

#Using data in a data structure(in this case an array of objects), along with the map method to do a repititive task-in this case populate multiple list items of the menu in the ui. Typically we can use the map method to consume data in a context repititively:
Navigation: Create a ListNav with LinkBox

#How to create a scrolling/scrollable sidebar:
Navigation: Create Playlist Menu

#Start of backend stuff:
Data modeling: Setup Prisma & PostgrSQL on Heroku

#Workaround for databases by creating a shadow database when working with Heroku:
Data modeling: Setup Prisma & PostgrSQL on Heroku

#Sample Prisma syntax and explanation of usage:
Data Modeling: Prisma Schema

#How to model your data based on the design you can see on the ui[looking at the design and figuring out the data design model needed]
Data Modeling: Data Modeling

#One to Many relationships, many to many relationships[generally, looking at how relationship types are established]:
Data Modeling: Data Modeling
Data Modeling: Creating Schema and Migrations with Prisma

#Syncing the database we created to Prisma:
Data Modeling: Creating Schema and Migrations with Prisma

#Migration
Data Modeling: Creating Schema and Migrations with Prisma

#Exception error handling for the data base connection
Data Modeling: Seeding Data

#Writing a Seed Script:
Data Modeling: Seeding Data

#Nested Inserts:
Data Modeling: Seeding Data

#Using the map method on the data in conjunction with Prisma:
Data Modeling: Seeding Data

#Next js being a fullstack framework, not just a frontend but also backend as seen in the pages folder which has an api folder and all of the files in there have serverless functions that we can use to , that has a url that they can hit, they can access the database and the frontend can talk to that:
Data Modeling: Seeding Data

#We can also use the database directly inside the components as well without even going through the API:
Data Modeling: Seeding Data

#Working with Prisma & Next js:
https://www.prisma.io/nextjs

#pushing to the database:
Data Modeling: Seeding Data

#Running Prisma Studio:
Data Modeling: Seeding Data

#Encrypting our passwords:
Data Modeling: Seeding User Data

#Running Migrations:
Data Modeling: Seeding Playlist Data Q & A

#Suggested approach to building fullstack app:
Authentication: Severless Api Overview

Httppie usage:
Authentication: Severless Api Overview

Httppie Installation:
Authentication: Severless Api Overview

Serverless functions:
Authentication: Severless Api Overview

Routes for form signup:
Authentication: Severless Api Overview

Signup process explained:
Authentication: Severless Api Overview

#Creating Api for user to signup and handling exception error using the try catch block if there's a problem in the process:
Authentication: Signup API Route

#Tokens:
Authentication: Signup API Route

#csrf:
Authentication: Signup API Route

Cookies:
Authentication: Signup API Route

Create first account using http pie:
Authentication: Signup API Route Recap & Test

#SignIn Api:
Authentication: SignIn API Route

Checking if a user exists and then issuing the same token as a cookie:
Authentication: SignIn API Route

using bcrypt again[it's also used in the signup.ts file] for encryption,
using jason web token[jwt, also used in the signup.ts file]:
Authentication: SignIn API Route

setting rules for the Api:
Authentication: SignIn API Route

#Using http only, making sure that the cookie can only be accessed via http, making it more secure as basically you won't be able to access it through Javascript on the frontend:
Authentication: SignIn API Route

testing out the signin Api with one of the accounts
Authentication: SignIn API Route

mechanism to interact with Apis:
Authentication: Fetcher & Auth Mutation

creating a function that will make an Api call to either sign in or sign up using a fetcher:
Authentication: Fetcher & Auth Mutation

type checking:
Authentication: Auth Pages

Creating the signup and signin Component:
Authentication: Auth Pages

#Opting out of our default layout wrapper for the signup/signin as a user that isn't signed in shouldn't be able to see the sidebar with the playlists and all:
Authentication: Auth Pages

#Opting out of default components wrapping behaviour using a ternary conditional:
Authentication: Auth Pages

#Updating the local cache:
Authentication: Auth Pages

#Continuation of auth form / signin / signup:
Authentication: Sign In and Sign Up

#Using useState for passing the input values as state variables:
Authentication: Sign In and Sign Up

#Doing pseudo state styling with Chakra ui(for example to change the hover color):
Authentication: Sign In and Sign Up

#Loading progress button for submit event:
Authentication: Sign In and Sign Up

#Navigating to the homepage after signing in or signing up:
Authentication: Sign In and Sign Up

#Creating a component for both signing in and signing up
Authentication: Sign In and Sign Up

#making an Api call:
Authentication: Sign In and Sign Up

#Protecting things: like say creating mechanisms to protect some of the Api routes, make Api routes to get the user, Api routes to interact with playlists, we've got to find a way to protect that to make sure that you are who you say you are (you're identified, you're authorized). Then protecting the pages, also making sure you cannot go there unless you're signed in:
Authentication: Protected Route Handler

#checking token, cookie for valid user:
Authentication: Protected Route Handler

#Authorized vs Unauthorized users:
Authentication: Protected Route Handler

#Api to get the user:
Authentication: Protected Route Handler

#edge functions:
Authentication: Protected Route Handler

#determining pages to be protected:
Middleware: Middleware Edge Functions

#set up to redirect user who tries to go to one of the protected pages without being signed in(redirect said user to signin page):
Middleware: Middleware Edge Functions

#Forcing unauthenticated user back on the signin page:
Middleware: Middleware Edge Functions

#Creating a custom hook:
Fetching Data: Custom hooks for Fetching data

#SWR library for data fetching:
Fetching Data: Custom hooks for Fetching data
https://swr.vercel.app/

#naming convention for custom hooks:
Fetching Data: Custom hooks for Fetching data

#preferance to using SWR vs Redux:
Fetching Data: Custom hooks for Fetching data

#Api to get playlists:
Fetching Data: Fetch and render data into Components

#Fetching data from our playlists and populating in our ui using our Api
Fetching Data: Fetch and render data into Components

#Scenarios to use chakra uis Image vs Next image
UI Layout:Gradient Background and Image Box

#Using gradients in chakra ui to create a beautiful linear gradient background that has different color densities at different levels. Also, making the gradient color have multiple options
UI Layout:Gradient Background and Image Box

#Server side data: Server side data fetching being able to be done on pages and not on components
UI Layout: Load Artists Data

#optimal choices when considering whether data will change while user is looking at it or whether it will stay the same after the initial render
UI Layout: Load Artists Data

#function to get server side props to be injected into a page(function will be called everytime page is requested):
UI Layout: Load Artists Data

#getStaticProps getServerSideProps:
UI Layout: Load Artists Data

#Applying one color to all the text inside a container:
UI Layout: Artists List UI Layout

#When in production, don't run command 'npx prisma db push', use migrations instead as we can't have data being wiped when in production. This command was used in a testing scenario:
Dynamic UI: Seed User Data

#npx prisma migrate reset:
Dynamic UI: Seed User Data

#Sample usage of template strings
Dynamic UI: Seed User Data

#Dynamic query parameter in Next js:
Dynamic UI: Build dynamic Playlist Pages

#Dynamic variable:
Dynamic UI: Build dynamic Playlist Pages

#Dynamic routing to dynamic pages:
Dynamic UI: Build dynamic Playlist Pages

#Restricting access to dynamic pages based on the user id:
Dynamic UI: Build dynamic Playlist Pages

#Setting rules for fetching data/ setting Api rules:
Dynamic UI: Build dynamic Playlist Pages

#using 'include' within the context of prisma queries:
Dynamic UI: Build dynamic Playlist Pages

#Setting rules for specificity when fetching data using prisma:
Dynamic UI: Build dynamic Playlist Pages

#Create a random color generator for our backgrounds(for colors within the context of chakra ui) (using Math.floor , Math.random within the syntax for randomization):
Dynamic UI: Playlist page UI

#Random image linking:
Dynamic UI: Playlist page UI

#transparent divs(chakra ui) for glass like design:
Dynamic UI: Songs Table UI

#semi transparent line design:
Dynamic UI: Songs Table UI

#Adding hover state using in-line styling in chakra ui:
Dynamic UI: Songs UI and time format

#Getting the index when iterating over a data source using the map method
Dynamic UI: Songs UI and time format

#Iterating over a data source and consuming individual properties of data source in a design using the map method:
Dynamic UI: Songs UI and time format

#Formatting date and time using formatDuration library:
Dynamic UI: Songs UI and time format

#Global state for components to be able to communicate with each other[Using Easy Peasy(an alternative option would be Redux or hooks plus the context Api)]:
State Management: Player State with Easy Peasy

#Using React Howler: A React.js wrapper for howler.js (audio player). howler.js is an audio library for the modern web. It defaults to Web Audio API and falls back to HTML5 Audio.
State Management: Player Controls Ui

#Keeping track of data/state, like the songs, what song is currently playing and all:
State Management: Player Controls State

#Another example for conditional rendering of components/data using the ternary conditional:
State Management: Player Controls State

#Passing conditional style values using the ternary conditional:
State Management: Player Controls State

#create a function for Toggling state true or false and getting the absolute current value of state at the time that you call it, then switch it to the boolean inverse:
State Management: Player Controls State

#Implementing our easy peasy context:
State Management: Playing Songs State

#More conditional rendering:
State Management:Playing songs state

#Using easy peasy in conjunction with React Howler to handle audio and the state context of the audio being played. React howler for the audio functionality:
State Management:Playing songs state

#Updating state using a function that will have in it's context the setting function that is meant to update the state variable.
State Management:Shuffle and Next Song Controls

#Implementing shuffle logic for randomization using Math.floor and Math.random, for when the next button is clicked and the shuffle state is true. Also account for if the song index that is generated by our logic is the same as that of the current song playing:
State Management:Shuffle and Next Song Controls

#Implementing logic for song repeat on end of playing using state in conjunction with our useRef hook:
Callbacks: Seek Bar Controls

#accessing duration of current audio using React Howler:
Callbacks: Seek Bar Controls

#accessing values for the range component in chakra ui:
Callbacks: Seek Bar Controls

#using the chakra ui range component:
Callbacks: Seek Bar Controls

#Another example of not calling the setting function directly but within the context of another function, this time within the context of an anonymous function:
Callbacks: Seek Bar Controls

#A mention fro Xstate:
Callbacks: Seek Bar Controls

#animation:animating a value, animation frames:
Callbacks: Seek Bar Controls

#Implementing logic for the prev and next song buttons:
Callbacks: End Song & Repeat Handlers

#implementing and debugging the player's next, previous, repeat, and shuffle functions.
Callbacks: End Song & Repeat Handlers

s
