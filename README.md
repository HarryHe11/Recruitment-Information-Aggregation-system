# Recruitment-Information-Aggregation-system
The system collects data from famous recruitment information websites in China, and provide a web application to demonstrate visualized data. 

Major components:
- web crawler: uses Requests to crawl, and uses lxml and beautifulsoup4 to parse, data comes from famous recruitment information websites in China, the basic data required is readily available.
- data analysis: Use numpy and pandas to analyze data, use pyecharts for visualization 
- backend development: use Flask for web backend construction. Data is stored and communicated through csv, MySQL, and configuration files.

install: 
1. Run install_package.bat (try it with administrator privileges)
2. Modify mysql configuration located in /analysis/analysis_main.py The system itself has a visual configuration file, that is, you do not need to import data for analysis. If you want to re-analyze, you need to import database data and modify the content of input_data.py according to the database fields
3. Unzip js.7z and put it in the /static directory
4. Run server.py to run the web server
5. Access http://127.0.0.1 with Chrome
