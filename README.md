## Hi there 👋

<!--
**sylarpy/sylarpy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# ⚽ Football Data Scraper

## 📋 Description

A Python web scraper that automatically extracts football match data from Yalla Kora website. This tool allows you to collect comprehensive match information for any specific date and save it in a structured CSV format for further analysis.

## 🚀 Features

- Extract match results by specific date
- Save data to CSV file format
- Support for Arabic content
- Comprehensive match information (teams, scores, match time, championships)
- Easy-to-use command line interface
- Error handling for invalid dates

## 🛠️ Technologies Used

- **Python 3.x**
- **BeautifulSoup4** - For HTML parsing and data extraction
- **Requests** - For HTTP requests
- **CSV** - For data storage and export
- **LXML** - For faster XML/HTML parsing

## 📦 Installation

```bash
pip install requests beautifulsoup4 lxml
```

## 🏃‍♂️ How to Use

1. Run the script:
```bash
python football_scraper.py
```

2. Enter the date in this format: `mm/dd/yyyy`
```
inter ur date mm/dd/yyy: 12/15/2023
```

3. The program will fetch all matches for that date and save them to a CSV file

## 📊 Extracted Data

- **Championship Name**
- **Team A**
- **Team B** 
- **Match Score**
- **Match Time**
- **Date**

## 📁 Sample Output

```csv
CHAMSHUIP_TAG,TEAMA,TEAMB,SCORE,THIMEMATCH,DATE
Premier League,Manchester City,Arsenal,2-1,90',12/15/2023
La Liga,Real Madrid,Barcelona,1-1,90',12/15/2023
```

## 🔧 Code Structure

The scraper works by:
1. Taking user input for the date
2. Sending GET request to Yalla Kora match center
3. Parsing HTML content using BeautifulSoup
4. Extracting match data from specific CSS classes
5. Organizing data into a structured format
6. Exporting results to CSV file

## 🎯 Use Cases

- Football match analysis
- Building sports databases  
- Tracking favorite teams performance
- League statistics research
- Sports journalism and reporting

## 📝 Notes

- Ensure stable internet connection
- Website response time may vary
- Use correct date format (mm/dd/yyyy)
- CSV file is saved to Downloads folder by default


Got ideas for improvements or new features? Feel free to submit a pull request!


If you need help or have questions, don't hesitate to reach out.

Email: apdoismail550@gmail.com 
 
