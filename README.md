# tableau-challenge

Collected data from [Citi Bike](https://www.citibikenyc.com/system-data) and leveraged python to clean and reduce the datasets to a more manageable size. Jupyter notebooks are stored on this repository.

Upon completion, the data was converted into a tableau story.  Based on the data available, there is a fully year 2018 and continuing through May 2019 as Q2 was the latest posted on certain datasets (though it was noted June 2019 was incomplete and therefore ommitted from the analysis).

My first goal was to hilight a map based on the popularity of the station (noted by size of marker) and colored according to average duration of rentals. Noting that bike availability is essential to ensuring coninued rentals in higher demand areas this coloring is reversed to display those with higher durations as focal points (red).  Many of these were more outliers from the city though there were some averaging more than a day closer in.

Looking at the monthly operating reports, our story continued by highlighting the revenue tied to the different pass types (annual membership and short-term - Day and 3 Day Passes) as well as comparison to total during the duration of the analysis. Not suprisingly, peak months were April to October based on location and weather.  

Lastly, to better understand the customers engaging with bike rentals, the analysis concludes with a page based on Gender and Generation. A focus on the To 10 stations and the customers using it (though in prime tourist locations) as well as how the different types of subscribers (annual or short-term) split by gender or generationa. Finishing with a view of average age by Gender across the Quarters highlighted in color by the density of the customers made up by that segment (green means more records and rust means less).  This page is interactive by filtering through clicking on the charts themselves.


To view the final story and download the file, please go to:
[CitiBike Dashboard](https://public.tableau.com/views/CitiBikeDashboard_15842443285120/CitiBikeSummary?:display_count=y&:origin=viz_share_link)