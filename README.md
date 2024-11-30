# DSA210 Course Project

## YouTube Watching Habits: Analyzing Content, Time, and Location

### Description
This project analyzes my personal YouTube watch history to uncover patterns in video consumption across different categories, times of the year, and locations. The aim is to understand how my viewing habits correlate with various contexts, such as being at home, on campus, or during specific times like midterm weeks or holidays.

### Dataset
- **YouTube Watch History** 
- **Location Data** 
- **Video Categories**

### Tools and Methods
- **Tools:**
  - Python (pandas, matplotlib, seaborn, geopy)
  - Jupyter Notebook for data processing and analysis
  - YouTube Data API for fetching video metadata
- **Methods:**
  - Data cleaning and integration
  - Exploratory data analysis (EDA)
  - Visualization of trends and correlations (bar charts, heatmaps, scatter plots)
  - Time-location alignment using GPS coordinates and timestamps

### Project Plan

#### Data Collection
- Export YouTube watch history
- Gather location history

#### Data Integration
- Match YouTube watch history timestamps with location history timestamps
- Use timestamps to categorize video watching behavior into time of day segments

#### Data Enrichment
- Retrieve additional metadata for videos, such as categories or tags

#### Analysis
- Explore patterns in video consumption across different times of day, locations, and time periods
- Investigate correlations between video watching behavior, location, and time

#### Visualization
- Develop visual representations like scatter plots, heatmaps to illustrate insights
- Highlight trends such as the type of content watched during academic periods or at specific locations

#### Conclusion and Insights
- Summarize findings
- Propose recommendations

### Deliverables
- **GitHub Repository:** Publicly accessible repository containing:
  - Python scripts for data cleaning, enrichment, and analysis
  - Visualizations illustrating insights from the data
  - A detailed README.md explaining datasets, workflow, and findings
- **Final Report:** A summary of key insights supported by visualizations, focusing on found conclusions

