

# **Dream11 T20 World Cup 2022 Dashboard**

## **Overview**  
This project involves creating an interactive and insightful dashboard using **Power BI** to analyze and visualize player performance data from the **T20 World Cup 2022**. The goal is to identify the top 11 players and form the ultimate Dream11 cricket team based on statistical performance. Data preprocessing and advanced analytics were performed to ensure the accuracy and relevance of the results.

---

## **Features**  
- **Data Integration**: Combined multiple datasets, including player details, match summaries, batting, and bowling statistics.  
- **Interactive Dashboard**: Created a visually appealing and user-friendly dashboard in Power BI for detailed analysis.  
- **Advanced Analytics**: Utilized calculated columns and DAX measures for insights like player rankings, team performance, and match outcomes.  
- **Team Selection**: Developed an algorithmic approach to shortlist the top-performing players across batting, bowling, and all-rounder categories.  
- **Data Preprocessing**: Processed raw datasets using Python and Jupyter Notebook to ensure clean, structured, and normalized data.  

---

## **Technologies Used**  
- **Power BI**: Dashboard creation and data visualization.  
- **Python**: Data preprocessing using libraries like Pandas and NumPy.  
- **Jupyter Notebook**: For scripting and exploratory data analysis (EDA).  
- **DAX (Data Analysis Expressions)**: For calculated columns and measures in Power BI.  
- **JSON/JavaScript**: To handle structured data for visualization.  

---

## **Datasets**  
1. **dim_match_summary.csv**: Match details and summary.  
2. **dim_players.csv**: Player information, including team and roles.  
3. **dim_players_no_images.csv**: Players' data without images for cleaner analytics.  
4. **fact_batting_summary.csv**: Detailed batting statistics for each player.  
5. **fact_bowling_summary.csv**: Detailed bowling statistics for each player.  
6. **t20_wc_match_results.json**: Comprehensive match results in JSON format.  
7. **t20_wc_player_info.json**: Player performance details in JSON format.  

---

## **File Structure**  
- **Power BI Files (.pbix)**:  
  - `DREAM 11.pbix`: Dashboard focusing on top player selection.  
  - `PLAYER DETAILS.pbix`: Visualization of player details and performance.  
  - `PROJECT - DREAM 11 WORLD CUP.pbix`: Complete project dashboard.  

- **Data Preprocessing**:  
  - `t20_data_preprocessing.ipynb`: Python notebook for cleaning and preparing datasets.  

- **Scripts**:  
  - JavaScript and JSON files for structured data representation.  

---

## **Steps to Reproduce**  
1. **Preprocess Data**:  
   - Use `t20_data_preprocessing.ipynb` to clean and preprocess raw data files.  
   - Ensure all CSV, JSON, and JS files are placed in the same directory.  

2. **Load Data into Power BI**:  
   - Import the cleaned datasets into Power BI.  
   - Use DAX measures and calculated columns to generate insights.  

3. **Explore the Dashboard**:  
   - Interact with the dashboard to analyze player statistics, match summaries, and team performance.  

---

## **Key Insights**  
- Identified top players for the Dream11 T20 World Cup team based on batting and bowling efficiency.  
- Visualized team and player performance trends across the tournament.  
- Highlighted key match-winning players and their contributions.  

---

## **Future Enhancements**  
- **Dynamic Team Selection**: Automate the selection process using machine learning techniques.  
- **Real-Time Updates**: Integrate APIs for live data streaming and updates.  
- **Enhanced Visualizations**: Add more charts and graphs for deeper analysis.  

---

