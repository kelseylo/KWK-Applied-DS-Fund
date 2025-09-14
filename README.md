# KWK-Applied-DS-Fund

The focus of this project explores the globalization of the Korean popular music (K-pop) through the language composition of songs overtime and analyzes the sentiment composition of these songs. As K-pop expands into the international market, its culture has impacted the world and the world has also left an impression in the Korean culture. This project analyzes the industry’s linguistic and sentimental shift overtime. It is important to study the globalization of K-pop as K-pop serves as a medium for cross-culture communication. The ideologies, history, fashion, expression, and countless elements of the Korean culture are exchanged with the world. This fosters a global sense of community across people of diverse backgrounds. Through kpop, people from all countries in the world can connect with each other common interests. 

The data from this project is sourced from various APIs and web-scraping. Data from four major K-pop groups (BTS, BLACKPINK, EXO, and TWICE) are collected. The lyrics of the songs are sourced from the Genius website. The data about the songs and artists are sourced from the Genius API, Spotify API, and Billboard website. 

Various Python packages were utilized in this project. 
- The packages used for getting and loading the data for analysis: BeautifulSoup, requests, and json.
- The packages used to cleaning the data: thefuzz.
- The packages used for processing the data: pycld2, deep_translator, nltk (Natural Language Toolkit).
- The packages used for plotting and visualization of data: seaborn, matplotlib, pandas, NumPy. 

The majority of the program was created by the myself, but there were a couple of areas that were AI assisted code. The areas that were assisted by AI or outside sources are: getting the token in collecting_data.ipynb, sorting the language composition by value in processing_data.ipynb, and formatting the x-axis from ordinal to formatted dates in visualizing_data.ipynb. The code segments that are AI assisted or from outside sources are identified by comments in the code cell. 

The data files are manually moved to specific directories after they have been created. It is indicated in the code cell of the new directory the saved files are moved to. 

This is a project created in tandem with the Kode With Klossy 2025 Applied Data Science Fundamentals Challenge. 
