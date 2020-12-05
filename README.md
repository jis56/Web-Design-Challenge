# Web-Design-Challenge
### https://jis56.github.io/Web-Design-Challenge/landing.html
----

**Latitude Analysis Dashboard**: A dashboard website was created using the visualizations created from the Python API challenge (https://github.com/jis56/Python-API-Challenge). In building this dashboard, individual pages were created for each plot with explanations as well as a means to navigate between each of them. Additionally, a landing page, a comparison page, and a data page were also created.

In total, the webiste consists of 7 pages:

* A landing page containing:

  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

* Four visualization pages, each with:

  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

* A "Comparisons" page that:

  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.


* A "Data" page that:

  * Displays a responsive table containing the data used in the visualizations. The CSV file was converted to HTML as seen in the Resource folder.
 
 Most importantly, at the top of each page, there is a navigation menu that: 
 
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
- Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
- Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

