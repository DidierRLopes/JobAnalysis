# JobAnalysis
This repository aims to extract an insight of your job statistics.

The idea is to have an easily readable Excel where you can update your work days, and use a Jupyter notebook (with common Python libraries for data science) to process this data and extract further insights.


The Excel is pretty straightforward. Each table corresponds to a week work where you can add:
 * Entry and Exit hours, which will automatically calculate your working hours and update the total weekly hours. 
This is particularly convenient when you have a flexible schedule as long as you respect the working hours.
 * Status, which contains the project you are working on and your location, with the format: Project (location).
Notice that you should write "DAY OFF" or "BANK HOLIDAYS" on the Status column when you did not work on that day.
 * Comment, allowing you to remember that particular day (e.g. Discussed with XXX about ZZZ product).
 
<img width="1079" alt="captura de ecra 2019-02-08 as 23 28 24" src="https://user-images.githubusercontent.com/25267873/52511754-64d45980-2bf9-11e9-8506-3af987e93282.png">

Here are some examples of the type of insights that you can extract from the data.

<img width="1101" alt="repository-image" src="https://user-images.githubusercontent.com/25267873/52511668-ee375c00-2bf8-11e9-932e-57c50fc63078.png">


