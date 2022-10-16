Project:  Knesset Members - HTML-TXT Decompiler




1. What the project does:


A tool I developed for my project: "The Israel Kneseet by Generations"

This python program extracts a CSV file with the full names, date of birth, 
and candidacy of the Israeli Knesset members from the Official Israeli Kneset website by year of Knesset.

After combining all the data in excel I then manipulate it using conditional formatting to produce
a graph which colors the different generations in each Israeli Knesset cycle.



2. Why the project is useful:


After many failed attempts to scrape the Israeli Knesset website online,
I decided to build a local offline HTML scraper in order to obtain the data.



3. How to start working with the project:


- Go to the Israeli Knesset website, then to candidacy by year of Knesset: - https://main.knesset.gov.il/mk/Pages/Previous.aspx?pg=mkpknessethist&knesset=1
- Change the last digit of the previous link to the desired Knesset cycle. (Currently 1-24)
- Copy the entire HTML source code of the webpage to a local .txt file.
- In the Python script, change the link in: 0. Insert Path TXT - file_temp to your local .txt file.
- Run the code and you now should have a CSV file with the full names, date of birth, 
and candidacy of the Israeli Knesset members from the Official Israeli Kneset website by year of Knesset.



4. Help with thw project:


If you want to help with making the project into a proper online scraper you can contact me at - vadim.makeev.91@gmail.com

Made by Vadim Makeev @VadimM91