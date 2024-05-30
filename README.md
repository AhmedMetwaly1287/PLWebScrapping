<h1>Premier League Players Data Scrapping</h1>

<h2>Overview</h2>

<p>This project demonstrates simple web scrapping skills using Selenium and BeautifulSoup, it uses BeautifulSoup for the purpose of extracting the link leading to more data on the player, and Selenium to automate the process of accessing the pages of each player and scraping the data inside of it and Pandas to handle Data Processing and Wrangling.</p>


<h3>Tools Used</h3>

<ol>
    <li>
        <strong>Selenium</strong>
        <ul>
            <li>Serves as an automation tool, where it scrolls down to the end of the page to ensure that everytime the page is accessed, all player links are extracted (Using BeautifulSoup), then it automates the process of accessing each page, scraping the data inside of it and storing it in a Dictionary for future use.</li>
        </ul>
    </li>

<li>
    <strong>BeautifulSoup</strong>
    <ul>
        <li>Handles the process of extracting the links of the players to be accessed by Selenium, reformating the links so that they're in the correct format and then storing them in a List.</li>
    </ul>
</li>

<li>
    <strong>Pandas</strong>
    <ul>
        <li>Pandas is utilized for data processing and wrangling, handling missing/null values and then filtering the players by their position and saving each to a CSV file.</li>
    </ul>
</li>
</ol>





