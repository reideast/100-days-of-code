# #100DaysOfCode Log - Round 1 - Andrew Reid East

The log of my #100DaysOfCode challenge. Started on [January 1, Wednesday, 2020].

## Log

### R1D1 1/1/2020
`cv-blog-js` - Started an Express + React app, following FreeCodeCamp tutorial, intended to become a new "about me" homepage https://github.com/reideast/cv-blog-js

### R1D2 2/1/2020
`cv-blog-js` - Connected a simple API endpoint to frontend; npm audit & warnings version bumps; Add in simple CI with tests through GitHub Actions https://github.com/reideast/cv-blog-js

### R1D3 3/1/2020
`cv-blog-js` - Split frontend and backend to separate repos. Deployed both successfully to separate Heroku apps. Set up both for Continuous Deployment upon commit to `master` and passing CI in GitHub Actions https://github.com/reideast/cv-blog-js https://github.com/reideast/cv-blog-js-backend

### R1D4 4/1/2020
`cv-blog-js` - Attempted to get a http mock working with the 'nock' library for node environments, but needs work. https://github.com/reideast/cv-blog-js

### R1D5 5/1/2020
`cv-blog-js` - Successfully got testing working the the Enzyme library https://github.com/reideast/cv-blog-js

### R1D6 6/1/2020
`cv-blog-js` - Set up a basic CV with CSS flexbox; restructured into Reach components; stubbed with my basic CV data. Created a Heroku pipeline and a Staging/Release branch https://cv-blog-js-staging.herokuapp.com/

### R1D7 7/1/2020
`cv-blog-js` - Restructured the CV detail items so that the HTML hierarchy has distinct items that I can style with CSS. Use grid-auto-flow to make each dl item: `##|######` https://github.com/reideast/cv-blog-js

### R1D8 8/1/2020
`cv-blog-js` - Customised HTML tags to better express data stored within (justified with some quick research: [Custom HTML Tags](https://dev.to/jfbrennan/custom-html-tags-4788)). Inlined header elems into inline flow. https://github.com/reideast/cv-blog-js/tree/release

### R1D9 9/1/2020
`cv-blog-js` - Entered the my user data; restructured the HTML tags some more, paying attention to DOM structure for reqiured container elements https://github.com/reideast/cv-blog-js/tree/flexbox-grid

### R1D10 10/1/2020
`cv-blog-js-backend` - Move the "jobs" data into a basic API, to be consumed by the front end https://github.com/reideast/cv-blog-js-backend/tree/api-job

### R1D11 11/1/2020
Dockerfiles - Working with the docker build, making the layers execute properly to reduce space (Technically for work, but this wasn't required, so I'm OK calling it "hobby" programming)

### R1D12 12/1/2020
Dockerfiles - A bunch more dockerfile hacking. Still interesting!

### R1D13 13/1/2020
React tutoral - To re-learn React doing the back to basics with the official docs https://github.com/reideast/cv-blog-js/tree/tutorial-react-main-concepts

### R1D14 14/1/2020
React tutorial - Events, state, etc. https://github.com/reideast/cv-blog-js/tree/tutorial-react-main-concepts

### R1D15 15/1/2020
React tutorial - Lists of elems, forms, and controlled components. (Was tired, but still got into it; small victory!) https://github.com/reideast/cv-blog-js/tree/tutorial-react-main-concepts

### R1D16 16/1/2020
`cv-blog-js` Consume the /cv/jobs API on the frontend, separate out into list items https://github.com/reideast/cv-blog-js/

### R1D17 17/1/2020
`cv-blog-js` `cv-blog-js-backend` Serve all the CV data from API endpoints, consume in the same way on the frontend https://github.com/reideast/cv-blog-js https://github.com/reideast/cv-blog-js-backend

### R1D18 18/1/2020
`cv-blog-js` Refactor fetch code and API loading/error messages called from React render() so that it can be generic for all components. Required playing around with first order functions and JavaScript `this` binding https://github.com/reideast/cv-blog-js

### R1D19 19/1/2020
`cv-blog-js` Created a code project component https://github.com/reideast/cv-blog-js

### R1D20 20/1/2020
`cv-blog-js` Back to making headway on TDD with tests for actual react components (just CodeProject for now) https://github.com/reideast/cv-blog-js

### R1D21 21/1/2020
`cv-blog-js` Use jest mocks to test fetch() api methods with the generic, extracted functions https://github.com/reideast/cv-blog-js
