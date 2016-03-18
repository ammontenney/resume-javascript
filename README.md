## JavaScript Resume

This project started by cloning [udacity/frontend-nanodegree-resume](https://github.com/udacity/frontend-nanodegree-resume).

### Overview

1. My work in this project is largely found in **js/resumeBuilder.js**
2. Using JavaScript, JSON, jQuery, and the included js/helper.js I populated the content for the resume
3. I built the JSON data structure using the following schema:

    a. `bio`

            name : string
            role : string
            contacts : an object with
                  mobile: string
                  email: string
                  github: string
                  twitter: string
                  location: string
            welcomeMessage: string
            skills: array of strings
            biopic: url
            display: function taking no parameters

    b. `education`

            schools: array of objects with
                 name: string
                 location: string
                 degree: string
                 majors: array of strings
                 dates: integer (graduation date)
                 url: string
            onlineCourses: array with
                 title: string
                 school: string
                 date: integer (date finished)
                 url: string
            display: function taking no parameters

    c. `work`

            jobs: array of objects with
                 employer: string
                 title: string
                 location: string
                 dates: string (works with a hyphen between them)
                 description: string
            display: function taking no parameters

    d. `projects`

            projects: array of objects with
                  title: string
                  dates: string (works with a hyphen between them)
                  description: string
                  images: array with string urls
            display: function taking no parameters
