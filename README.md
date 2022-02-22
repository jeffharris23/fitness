# Fitness App
I was too lazy to pay for fitbit premium but would like to see more detailed metrics on my activies so I built something myself. This also provides a demo of my skills as a full stack developer.

## Overview
Provides a web app to login and connect your fitbit account to it to pull in all your fitness activities to see detailed metrics that normally require a fitbit premium account to see these details.

## Functionality
* Auth
* Connect Fitbit Account
    * Wires up to Fitbit API
    * Scheduled task to regularly pull in raw data
    * Normalize data
    * Initially reporting will be derived on the fly from the data we save (move to saving snapshots)
* Activies screen
    * Summaries on activities
    * Some basic date filtering
  
## Technologies Used
1. React
2. Remix
3. Tailwind
4. Prisma
5. Fly.io ???

## Mocks/Design
Not a designer so I'll rely heavily on Tailwind to rescue me but will build out wireframes to show my ux process

## Roadmap
* Different providers in the futures to connect your account with eg (RunKeeper)
* Allow the ability to enter your weight and summaries around these
* Make is responsive (support desktop design)



