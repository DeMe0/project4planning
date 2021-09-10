# project4-planning#  ⏱️

## Description
Using Gatsby and a CMS such as contentful, my goal for this project is to create a modern website for my family's old small business - Father & Son Sewer Service.
I'll be studying up on GraphQL in order to learn how to get data from the CMS to show on the front end.
The site will showcase the company's history in an About section, a detailed list services in our scope of work, a photo gallery, a contact form, and a another form for for reviews/customer feedback.
I'm hoping that with the use of Contentful's data structure along with Gatsby's ability to render different endpoints on the same static site, it shouldn't be too idealistic to think that I can make each service and photo clickable so that they link to a new endpoint and provide additional information, prices, descriptions, etc.


### Project Links

- [Back end Contenful]()
- [Front end git]()

- [Back end deployed (routes are /----,  /----)]()
- [Front end deployed]()

### Wireframes and Architecture

- Wireframes: -[All Wireframes](https://wireframepro.mockflow.com/view/MKa6uxjpImb)
- Architecture: [Google Drawing]()

### Time/Priority Matrix

| Component                       | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------------------- | :------: | :------------: | :-----------: | :---------: |
| Git management                  |    H     |      4hrs      |               |             |
| Q&A and bug fixes               |    H     |     3.5hrs     |               |             |
| Connection/initial deployment   |    H     |      1.5hr     |               |             |
| Populate Contentful CMS data    |    H     |      8hr       |               |             |
| Routes                          |    H     |      2hrs      |               |             |
| Deployment bugs                 |    H     |      1hrs      |               |             |
| Install and set up react router |    H     |     0.5hrs     |               |             |
| Switch, Links, Routes           |    H     |      1hrs      |               |             |
| Header                          |    H     |      2hrs      |               |             |
| Home                            |    H     |      4hrs      |               |             |
| Navbar @ footer                 |    H     |      2hrs      |               |             |
| aboutus/aboutuspage             |    H     |      2hrs      |               |             |
| Contact me/formspree            |    H     |      4hr       |               |             |
| list of services                |    H     |      2hrs      |               |             |
| Styling                         |    H     |      8hrs      |               |             |
| Responsiveness                  |    H     |      5hrs      |               |             |
| Service details                 |    L     |      7hrs      |               |             |
| Extra Styling                   |    L     |      4hrs      |               |             |
| Total                           |    H     |     61hrs      |               |            |



## Components - Descriptions

- LogoHeader: renders our logo at the top of each page
- NavBar:
  - mobile: footer that sticks to the bottom of the screen even when you scroll
  - desktop: standard header navbar at top of page
- Video.js: renders our youtube video
- Carousel.js: an image/link carousel that renders a few images of our choice
- ServicesList.js: list of services from our api
- Reviews.js: - a component that shows a few customer reviews linked to other sites
- Contact.js - a component that is a formspree.io form that allows us to receive data submitted by users.
- About - a page about my father

## Additional Libraries

- React, react-router-dom, Gatsby
- Contentful CMS
- Bootstrap?
- Node
