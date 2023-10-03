# datasci_4_web_viz

The objective of this assignment was to "Explore web-based platforms for interactive data visualization, contrasting R's Shiny with Python's equivalents and harnessing these tools to present data in interactive and user-friendly ways"

## Reflections

## 1. R's Shiny Visualization
Shiny App Link- https://zf21.shinyapps.io/shinyApp/
I did not face any major issues while deploying the app on Shiny App io. I used the tutorial on the Posit.co website to first deploy a sample application and then put in the code for the web application to display data showing age-adjusted diabetes prevalence in various counties in California.

## 2. Python's Shiny Visualization:
Although I was able to deploy the app using ```shiny run cdc.py --reload``` in Google Shell Cloud, I had issues with deploying the app through Shinyapps.io and coming up with a web-accessable URL endpoint. An error appeared when I ran ```rsconnect deploy shiny /path/to/app --name <NAME> --title my-app```. I entered ```rsconnect deploy shiny shiny_python/cdcpy.py --name cdcpy.py --title my-app``` and the error stated that the path to the app was incorrect.

## 3. Flask with Matplotlib Visualization:
I did not have any issues when deploying the Flask app. I deployed the app using ```python app.py``` in Google Shell Cloud.
