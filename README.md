# Use-Webscraping-to-Extract-Tesla-Revenue-Data
Use the `requests` library to download the webpage https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm Save the text of the response as a variable named `html_data`.
Parse the html data using `beautiful_soup` using parser i.e `html5lib` or `html.parser`.
Using `BeautifulSoup` or the `read_html` function extract the table with `Tesla Revenue` and store it into a dataframe named `tesla_revenue`. The dataframe should have columns `Date` and `Revenue`.
Display the last 5 row of the `tesla_revenue` dataframe using the `tail` function. Take a screenshot of the results.
