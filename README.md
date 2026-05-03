🎬 NETFLIX CONTENT ANALYSIS DASHBOARD

Exploratory analysis and interactive Power BI dashboard built on Netflix's content catalog, uncovering trends in genre distribution, content type, release patterns, and global reach across 7,000+ titles.


📌 Project Overview
This project analyzes Netflix's content library using a dataset of 7,008 titles sourced from IMDb. The goal is to derive meaningful insights about Netflix's content strategy — what types of content dominate, which genres perform best, how the catalog has evolved over time, and where the content originates from.
The findings are presented through an interactive Power BI dashboard designed for quick, visual storytelling.

📊 Dashboard Highlights
VisualInsightContent Type BreakdownMovies vs. TV Series vs. Specials and moreGenre DistributionTop genres across the entire catalogRelease Year TrendHow Netflix's library has grown from 1932 to 2022Country of OriginGeographic spread of content productionIMDb Ratings AnalysisRating distribution across content typesTop Ranked TitlesMost popular titles by IMDb popularity rank

🗂️ Dataset
FieldDescriptionimdb_idUnique IMDb identifiertitleTitle of the contentpopular_rankIMDb popularity ranktypeContent type (movie, tvSeries, tvMiniSeries, etc.)startYearRelease yearruntimeDuration in minutesgenresGenre tagsratingIMDb rating (1.7 – 9.7)numVotesNumber of user votesorign_countryCountry of productionlanguageOriginal languagecastLead cast memberscertificateAge certification
Dataset size: 7,008 rows × 19 columns
Year range: 1932 – 2022
Top producing countries: United States, United Kingdom, Japan, South Korea

🔍 Key Insights

Movies dominate the catalog (~2,923 titles), followed by TV Series (~2,199) and TV Episodes (~785)
Comedy, Drama, and Documentary are the most represented genres
The United States leads content production, followed by the UK, Japan, and South Korea — reflecting Netflix's global content push
IMDb ratings range from 1.7 to 9.7, with most content clustering in the 6–8 range
Netflix's library spans 90 years of content (1932–2022), with a sharp ramp-up post-2010


🛠️ Tools Used

Power BI Desktop – Dashboard creation and interactive visualizations
Microsoft Excel / Power Query – Data cleaning and transformation
Python (pandas) – Exploratory data analysis
IMDb Dataset – Source data


📁 Repository Structure
netflix-content-analytics/
│
├── netflix_list.csv          # Raw dataset (7,008 titles)
├── final_netflix_project.pbix # Power BI dashboard file
├── netflix dashboard screenshot # Dashboard screenshot
├── README.md                 # Project documentation

🚀 How to Use

Clone this repository

bash   git clone https://github.com/your-username/netflix-content-analytics.git

Open final_netflix_project.pbix in Power BI Desktop
Explore the dashboard — slicers allow filtering by content type, genre, country, and year

# Screenshot 

 <img width="1220" height="752" alt="netflix dashboard screenshot" src="https://github.com/user-attachments/assets/aa05d7b9-a21d-4834-87fb-d140a7f03dab" />


👩‍💻 Author
Chandhana
B.Tech Computer Science (AI & ML) | Data Analytics Enthusiast
📍 Bengaluru, India
🔗 LinkedIn | Naukri

📄 License
This project is for educational and portfolio purposes only. Dataset sourced from IMDb public data.
