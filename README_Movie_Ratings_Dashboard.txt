MOVIE RATINGS INTERACTIVE DASHBOARD — README
=============================================

WHAT THIS IS
------------
Movie_Ratings_Interactive_Dashboard.html is an interactive dashboard created
from the MovieRatings sheet in Movie_Ratings_50K_Beginner_Project.xlsx.

It includes:
- KPI cards: Total Ratings, Average Rating, Unique Movies, Unique Users
- Charts for genre ratings, top-rated movies, rating activity over time,
  ratings by country, platform averages, rating distribution, age groups,
  and genre/platform rating volume
- Filters for Genre, Country, Platform, Age Group, and Rating Year
- Automatically calculated insights that update when filters change

HOW TO OPEN IT
--------------
1. Download Movie_Ratings_Interactive_Dashboard.html.
2. Save it somewhere easy to find, such as your Desktop or Documents folder.
3. Double-click the HTML file, or right-click it and choose Open with > Google
   Chrome, Microsoft Edge, or another modern web browser.
4. Keep an internet connection enabled so the dashboard can load the Chart.js
   charting library from its CDN.
5. Use the dropdown filters at the top of the page to explore the data.
6. Click "Reset filters" to clear all selections.

IMPORTANT
---------
- This is an HTML dashboard, not a Power BI .pbix file.
- It is a recreation built from the supplied dataset, not the original Julius AI
  source code.
- The dataset is synthetic practice data. It does not represent real movie
  audiences, streaming platforms, countries, or industry trends.
- Each row is treated as one rating record.
- Top movies are ranked by average rating; titles with few ratings may rank
  highly, so always review the rating count in the details table.
- The dashboard uses Chart.js from a CDN, so charts may not render without
  internet access.
- The dashboard contains the data embedded in the HTML file. Do not publish
  or share the file if you later replace the practice data with private data.

IF SOMETHING DOES NOT WORK
-------------------------
- Make sure you are using a modern browser such as Chrome or Edge.
- Check that your internet connection is working.
- Refresh the page.
- If the file opens as text, right-click it and choose Open with > Chrome or Edge.
- If your college requires a genuine Power BI report, import the original Excel
  workbook into Power BI Desktop and recreate the visuals there. The HTML file
  cannot simply be renamed to .pbix.

FILES
-----
Movie_Ratings_Interactive_Dashboard.html
    Interactive dashboard for use in a web browser.

Movie_Ratings_50K_Beginner_Project.xlsx
    Original Excel workbook containing the 50,000-row MovieRatings sheet,
    StartHere sheet, and DataDictionary sheet.
