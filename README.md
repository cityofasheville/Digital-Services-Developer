# Digital Services Developer Skills Assessment
This is a skills assessment for the Digital Services Developer Position.

# The Problem


The City of Asheville provides a way for citizens to report issues and watch them get fixed through a web and mobile app called [The Asheville App](http://www.ashevillenc.gov/Departments/ITServices/OnlineServices/CitizenServiceRequests.aspx). Using the app, citizens can report issues such as potholes on their street, graffiti on a property, or cracks in the sidewalk, and they can choose to be notified when the street, property, or sidewalk has been repaired. The Asheville App does a good job at allowing individual citizens to track the status of their request, and view and filter different request types by location and date range. However, it doesn’t provide a way for citizens to explore patterns of citizen service requests or how the City performs at completing requests submitted through The Asheville App.


To meet this need and others like it, we are currently redesigning and rethinking a web app developed by the City of Asheville called [SimpliCity](http://simplicity.ashevillenc.gov). The redesign will include some new citizen focused dashboards on a number of topics. One of those topics will be citizen service requests submitted through The Asheville App. 


# The Task


Design and develop a Citizen Service Request Dashboard web application that tells a compelling story or stories about citizen service requests submitted through The Asheville App.


The dashboard could potentially help the citizen answer some or all of following questions: 


- How many requests have been submitted by request type?
- How long does it typically take to complete each request type?
- Are there geographic “hot spots” of request activity? If so, what do these mean?
- Are there any trends or changing patterns over time in the types of requests made?


The assessment will be evaluated based on 3 aspects which are integral to the position you’re applying for: data, design, and development (see more details below). We don’t expect you to be an expert in each aspect, but a successful candidate will at least be competent in each. Play to your strengths. For instance, if you are really strong with data, focus on creating some solid analysis and SQL queries. If you are stronger with design, show us that you can create an awesome user experience. If your strengths lie more in development, show us that you really know how to build a modern web application React or Angular 2.




## Data


The data is available in this [Google sheet](https://docs.google.com/spreadsheets/d/1bi6Rx8h1iomfu3MQyFOJDSyUtrbGz-mtnZwo7XjlXok/edit?usp=sharing). We opted against providing this data through an REST API because we wanted to minimize any potential technical failures during the assessment, and we wanted to give you some options in how you approach the data. We do not want you to write a full REST API. Our main interest is in how you pull out statistics from the dataset and prepare data for use in your app. You could go in a lot of directions with this.  




## Design


Once you have a sense of the data involved, we would like to learn more about your approach to design and your aesthetic. This could take the form of hand drawn sketches, wireframes, Sketch files, Photoshop files, or even screenshots if you like to dive directly into the CSS. We are not only interested in your ability to design a compelling UI, but also in your ability to design awesome UX that tells an intriguing story with the data.
 
## Development


Ultimately we want to deliver this dashboard to citizens through the web, so we’d like to see your design implemented as a web site. Ideally the web site should be built using React or another modern web framework such as Angular 2 (NOTE: SimpliCity is currently being rebuilt using React and Redux), but you can use whatever you are comfortable with. The web site should also be hosted and accessible somewhere on the web. We recommend Github Pages (it's free and easy for client side apps).




# Deliverables
1. A web site accessible somewhere on the web
2. Write up which includes the following:
 - Link to your code or a pull request if you fork this repo
 - Description of your approach to each of the 3 aspects of this project: data, design, and development
 - Additional Materials: SQL Queries, design files


# Resources
Additional datasets that might be useful:
[Asheville City Boundaries](http://data.ashevillenc.gov/datasets/dbce72a8752a47468e9ff0fed184e92b_0)
[Census](http://data.ashevillenc.gov/datasets?q=census&sort_by=relevance)
[Neighborhoods](http://data.ashevillenc.gov/datasets/3450b18c20bf432eb8db7a002e631046_0)
[Zip codes](http://data.ashevillenc.gov/datasets/ff22415f6653498db1519ce670bd08b3_0)
