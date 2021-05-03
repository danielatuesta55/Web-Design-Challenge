# Web-Design-Challenge

## Web Design Homework - Web Visualization Dashboard (Latitude)

### Intention of the Repository

This Repository has been made to summit the homework assignment for my Data Science Bootcamp at Northwestern University

Web Desing challenge

Student: Jorge Daniel Atuesta

May, 2021

### Inside of this repository

In this repository, the reader will encounter my solution to the homework assignment Web desing challange. The repository is organized in folders and a README.md (The file you are currently reading). Here is the list of the folders and their contents so you can navigate through them.

I hope you find my work not only to be complete but to display all the knowledge learned throughout this portion of the Data Science Bootcamp at Northwestern University.1. **Images**: Inside this folder you will find the images for the instructions provided by the institution. *You can skip this folder if you want*.
2. **WEB-DESIGN-CHALLANGE**: Inside this folder, you will have the chance to access my code for the assignment and all the output data. I encourage you to take a look inside as you will find the solution to the project and screenshots from it. Here are what's inside:

* *assets*: You will find my CSS style sheet that I created for my page.
* *Resources*: You will see a CSV file that I used as well as images for the grpahs.
* *citydata_to_html: *here you will find my pandas code used to turn the csv into html.
* *cloudiness.html*: the html code for this webpage
* *comparisons.hmtl:* the html code for this webpage
* *data.html* : the html code for this webpage
* *humidity.html:* the html code for this webpage
* *index.html*: the html code for this webpage
* *max-temp.html*: the html code for this webpage
* *table_data.html*: the html code for this webpage
* *wind-speed.html*: the html code for this webpage

3. **README.md**: it's the current file you are reading. I strongly suggest navigating through it and look at the project's objective solution and analysis.

I hope you find my work not only to be complete but to display all the knowledge learned throughout this portion of the Data Science Bootcamp at Northwestern University.

## Web Design Challange

### Project's Aim

Using HTML, CSS and Bootstrap I was tasked to create a webpage to display the data collected from the OpenWeatherMap API.

#### Project's Challanges

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme to customize your website. You may use a tool like [Bootswatch](https://bootswatch.com/). Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state. See the screenshots below.

## References

Littel, T. (2021, May 3). Tutoring session May 3rd 2021. (J. D. Atuesta, Interviewer)

## Assignment instructions provided by Northwestern Data Science Bootcamp


### Web Design Homework - Web Visualization Dashboard (Latitude)

#### Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![Images/landingResize.png](Images/landingResize.png)

#### Before You Begin

1. Create a new repository for this project called `Web-Design-Challenge`. **Do not add this homework to an existing repository**.
2. Clone the new repository to your computer.
3. Inside your local git repository, create a directory for the web challenge. Use a folder name to correspond to the challenge: **WebVisualizations**.
4. Add your **html** files to this folder as well as your **assets**, **Resources** and **visualizations** folders.
5. Push the above changes to GitHub or GitLab.
6. Deploy to GitHub pages.

### Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

#### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

#### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

#### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme to customize your website. You may use a tool like [Bootswatch](https://bootswatch.com/). Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state. See the screenshots below.

#### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

##### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](Images/landingResize.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
￼

##### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)

##### <a id="data-page"></a>Data page

Large screen:

![data page large screen](Images/data-lg.png)

Small screen:

![data page small screen](Images/data-sm.png)

##### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![visualize page small screen](Images/visualize-sm.png)

##### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)

#### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
