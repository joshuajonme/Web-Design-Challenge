Web Visualization Dashboard
===========================

Background
----------

My first attempt at using Bootstraps to design a webpage to share data. This
dashboard will contain this [API
project](https://github.com/joshuajonme/python-api-challenge/blob/master/WeatherPy/WeatherPy.ipynb)
to analyze weather across latitudes.

 

For this dashboard, we'll create individual pages for each plot and a means by
which we can navigate between them. These pages will contain the visualizations
and their corresponding explanations. We'll also have a landing page, a page
where we can see a comparison of all of the plots, and another page where we can
view the data used to build them.

 

Requirements
------------

The website must consist of 7 pages total, including:

-   [x] A [landing page](#landing-page) containing:

    -   [x] An explanation of the project.

    -   [x] Links to each visualizations page. There should be a sidebar
        containing preview images of each plot, and clicking an image should
        take the user to that visualization.

-   [x] Four [visualization pages](#visualization-pages), each with:

    -   [x] A descriptive title and heading tag.

    -   [x]The plot/visualization itself for the selected comparison.

    -   [x] A paragraph describing the plot and its significance.

-   [x] A ["Comparisons" page](#comparisons-page) that:

    -   [x] Contains all of the visualizations on the same page so we can easily
        visually compare them.

    -   [x] Uses a Bootstrap grid for the visualizations.

        -   [x] The grid must be two visualizations across on screens medium and
            larger, and 1 across on extra-small and small screens.

-   [x] A ["Data" page](#data-page) that:

    -   [x] Displays a responsive table containing the data used in the
        visualizations.

        -   [x] The table must be a bootstrap table component.
            [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)

        -   [x] The data must come from exporting the `.csv` file as HTML, or
            converting it to HTML. Try using a tool you already know, pandas.
            Pandas has a nifty method approprately called `to_html` that allows
            you to generate a HTML table from a pandas dataframe. See the
            documentation
            [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

-   [x] Has the name of the site on the left of the nav which allows users to
    return to the landing page from any page.

-   [x] Contains a dropdown menu on the right of the navbar named "Plots" that
    provides a link to each individual visualization page.

-   [x] Provides two more text links on the right: "Comparisons," which links to
    the comparisons page, and "Data," which links to the data page.

-   [x] Is responsive (using media queries). The nav must have similar behavior
    as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the
    background color change).

 
