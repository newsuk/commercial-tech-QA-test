# commercial-tech-QA-test

![](./logo-cypress.jpeg)

# Interview schedule

* Introduction.
* 45 minutes to complete the challenge.
* Review the challenge and other potential solutions.
* Questions.
* Wrap up.

# Setup

This is a basic cypress setup .It is ready to writing your tests.

1. Make sure you're using node v18.16.1 or greater. If you have `nvm` setup then feel free to run `nvm use`.
2. Run `npm i`
3. Run `npx cypress open` - this will open cypress ui

https://www.cypress.io/blog/2020/02/12/working-with-iframes-in-cypress

# QA Test

Candidate is require to do cypress  typescript/ javascript  test 

Scenario:

1. Visit - https://www.thesun.co.uk/sport/26213764/ten-hag-jamie-carragher-man-utd-sky-sports/
2. Check network request :  gampad/ads
3. Extract request body 
4. Extract  correlator
5. Check if the correlator  is same in  all  gampad/ads  requests

Test will be evaluated based on :
     Expected results,
     Approach,
     Coding standards,
     Behavior.

Candidate can use IDE of choice and need to do screen share  during test 

Manual Steps

1 visit the url provided
2 before proceeding I need to accept the cookies -> mandatory to proceed
3 wait for teh page to fully load 
4 look for any requests with partial match of 'gampad/ads'
5 save the payload/ body of teh request 
6 then  extract the correlator id  present in teh request 'correlator' 
7 confirm that teh correlator is teh same in all available/presnet 
    for the partial match of  'gampad/ads'