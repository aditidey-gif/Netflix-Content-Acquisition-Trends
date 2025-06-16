🚀 Netflix Content Acquisition Dashboard (2008–2021) 🚀

BUILT IN MICROSOFT EXCEL

I’ve built this dynamic dashboard to analyze Netflix’s content trends over time. The key slicer here is “Became Available on Netflix In”, which is derived from the Date Added field—this represents the year a title was added to Netflix, regardless of its original release date. I extracted the year into a separate column to enable intuitive filtering.

💡 **Key KPIs tracked in this dashboard:**

✅ Total Contents – Distinct count of unique titles added to Netflix.

✅ Total Movies – Number of movies in the total content library.

✅ Average Movie Duration – Average length (in minutes) of movies.

✅ Total TV Shows – Number of TV shows in the total content library.

✅ Average TV Show Seasons – Average number of seasons per TV show.

✅ Dominant Genre – Most frequent genre in Netflix acquisitions for the selected year. 



📊 **Project Insights**

📊 **Top Content Source Countries: Movies vs TV Shows**

📌 United States Dominates
The United States is by far the largest contributor of content to Netflix, with a huge lead in both movies and TV shows. The U.S. is the primary source of Netflix’s library.

📌 Movies > TV Shows for Most Countries
For most countries, the majority of content contributed is movies rather than TV shows. This is especially clear for countries like India, Japan, and France, where movie contributions significantly outnumber TV shows.

📌 United Kingdom is More Balanced
The United Kingdom shows a relatively balanced contribution between movies and TV shows compared to other countries.

📌 Minimal Contributions from Some Countries
Countries like Pakistan and South Korea have contributed fewer titles overall, but still show a mix of both types, with a slight tilt towards TV shows in South Korea.

📌 Diverse Global Sources Beyond the U.S.
While the U.S. dominates, other countries like India, United Kingdom, Japan, and France also contribute significantly, showcasing Netflix’s international acquisition strategy.



📊 **Netflix Age Rating Distribution: Movies vs TV Shows**

📌 TV-MA Dominates Netflix's Library
The TV-MA (Mature Audience) rating has the highest number of titles by a significant margin — both for movies and TV shows. This clearly shows Netflix’s strong focus on mature content.

📌 TV-14 and TV-PG Follow
The next most common ratings are TV-14 and TV-PG, showing that content aimed at older teens and families also forms a sizable part of Netflix’s offering.

📌 Minimal G-rated Content
G-rated (General Audience) content is among the least represented. This indicates that Netflix offers very little content specifically aimed at younger children or general family audiences.

📌 Movies Generally Have Higher Mature Ratings
Movies tend to dominate in the TV-MA, R, and PG-13 categories compared to TV shows, reflecting a trend toward more mature themes in Netflix’s film acquisitions.

📌 Strategic Content Focus
From the chart, it’s evident that from the very beginning, Netflix has prioritized acquiring content for mature audiences over content for younger viewers.



📊 **Yearly Growth of Netflix Library: Movies vs TV Shows**

📌 Sharp Growth Since 2016:
Netflix’s content library grew significantly starting in 2016, with both movies and TV shows being added at a much higher rate. Prior to 2016, content additions were minimal.

📌 2018–2019 Peak Period:
The highest growth occurred in 2018 and 2019, when Netflix added the largest number of titles to its library. This aligns with Netflix’s global expansion and aggressive content acquisition during this period.

📌 Movies Outpace TV Shows:
Movies consistently make up a larger share of the yearly additions compared to TV shows, as seen by the dominant red portion in the stacked bars.

📌 Slowdown After 2019:
There is a noticeable decline in new content additions in 2020 and 2021 compared to the peak years. 



📊 **Trend of Unique Directors Acquired by Netflix (2008–2021)**

📌 Minimal Growth Until 2014
Between 2008 and 2014, the number of unique directors acquired by Netflix was very small, indicating limited content acquisitions during this period.

📌 Major Expansion After 2015
There’s a sharp rise starting from 2015, with acquisitions surging dramatically. This reflects Netflix’s aggressive expansion into original and global content.

📌 Peak in 2019
The number of unique directors peaked at 1,316 in 2019 — marking Netflix’s highest level of diversity in directorial talent.

📌 Decline Post-2019
After 2019, there is a visible decline in the number of unique directors added, with 2020 and 2021 showing fewer acquisitions.



📊 **Diversity of Genres in Netflix Acquisitions (2008–2021)**

📌 Slow Start in Genre Diversity (2008–2013)
Between 2008 and 2013, Netflix acquired content from only a small and fluctuating number of genres, ranging between 2 and 6. This shows a limited focus on genre variety in its early years.

📌 Major Expansion After 2014
Starting in 2014, there’s a sharp increase in genre diversity, jumping to 15 genres and then rapidly rising to 31 genres in 2015. This reflects Netflix’s shift toward broadening its content offerings to cater to diverse audience tastes.

📌 Plateau at Maximum Diversity
From 2016 onwards, Netflix consistently acquired content across 42 unique genres each year, indicating that it achieved and maintained its target for maximum genre variety in its library.

📌 Strategic Global Appeal
The chart highlights how Netflix evolved from a platform with narrow genre offerings to one with wide-ranging content designed to appeal to a global and varied audience.

📌 Content Mix Strategy:
While both types grew, the chart highlights Netflix’s stronger emphasis on movies for expanding its library, with TV shows playing a secondary but significant role.



📁 **Project Files**

This repository contains the following key files:

netflix_raw.csv: This is the original raw dataset obtained from Kaggle. It contains the unprocessed data for Netflix titles.

Netflix Dashboard.xlsx: This Excel file is the core analytical output of this project, providing a comprehensive dashboard and the underlying processed data. It is meticulously organized and contains:

Cleaned Dataset: This sheet serves as the foundation of the analysis, holding the pre-processed and refined Netflix content data. It ensures the accuracy and reliability of all subsequent analyses, derived from the netflix_raw.csv file after cleaning and transformation.

Core Pivot Tables: These tables form the analytical backbone, summarizing and consolidating the cleaned data into actionable metrics. Each pivot table is specifically designed to feed into the various visualizations on the dashboard.

The Interactive Dashboard: This central component dynamically presents key performance indicators and trends through engaging charts and graphs, allowing for intuitive exploration of Netflix's content acquisition strategy.

Supporting Data Table: An additional sheet provides a detailed tabular view of specific data related to the dashboard, offering granular insights that complement the high-level visualizations.






