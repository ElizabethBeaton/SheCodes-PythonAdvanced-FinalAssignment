# SheCodes-PythonAdvanced-FinalAssignment


## Internet Population Visualization by Continent
### Overview
This project is a Python-based data visualization tool that analyzes and displays internet population data for different continents over time. The project is designed as part of a course where I explored key programming concepts such as **API usage, data structures, object-oriented programming (OOP), file manipulation, data visualization**, and **data manipulation**.

Using data sourced from Our World in Data, the project reads and processes a CSV file to generate a dictionary of population data and plots it for easy interpretation.

---

### Features
**Data Extraction and Transformation:**

* The CSV file is parsed using Python's csv library.
* The data is structured into a dictionary, grouping years and population values by continent.

**Dynamic Data Visualization:**
* Population trends are visualized using matplotlib.
* Each continent's data is displayed with unique markers and labels for clarity.
  
**Reusable Functions:**
 The project is modular, with two main functions:
1. generate_population_dictionary_from_csv: Reads the CSV and organizes the data into a structured dictionary.
2. generate_population_plots_from_dictionary: Uses the dictionary to dynamically create plots.
   
**Programming Concepts:**
* **API**: While not explicitly used in this project, this course has covered API integration, demonstrating how to source and process data programmatically from web services.
* **Data Structures**: Custom dictionaries were used to organize and manage the data efficiently.
* **Object-Oriented Programming (OOP)**: Modular functions reflect best practices in programming for maintainability and scalability.
* **File Manipulation**: CSV files are read and processed for data extraction.
* **Data Visualization**: Line charts provide a clear visual representation of the data, making trends easily discernible.
* **Data Manipulation**: Data was cleaned and transformed (e.g., converting strings to integers) to ensure compatibility with plotting tools.

---
  
## Usage Instructions
**Requirements**
Ensure the following libraries are installed:

* matplotlib
* csv (built-in Python library)
  
You can install matplotlib using pip:

bash
Copy code
pip install matplotlib

**How to Run**
1. Clone the repository:
bash
Copy code
git clone https://github.com/your-username/internet-population-visualization.git
cd internet-population-visualization
2. Place your CSV file (data.csv) in the WEEK5_PYTHON_FINAL_PROJECT folder. Ensure it contains columns for:
continent
year
population
3. Run the Python script:
bash
Copy code
python main.py
4. View the generated plot showing internet population trends by continent.

---
   
### File Structure
internet-population-visualization/
├── WEEK5_PYTHON_FINAL_PROJECT/
│   └── data.csv          # Source data for the project
├── main.py               # Main Python script
├── README.md             # Documentation for the project

---

### Sample Output
Once executed, the script generates a line plot where:

* **X-axis**: Years
* **Y-axis**: Internet population (in billions)
* Different lines represent different continents.
* Each line has markers and a legend for better readability. Gridlines enhance the interpretability of the graph.

---

### Lessons Learned
This project consolidates key programming and data analysis skills, including:

* **Extracting and Structuring Data**: Using dictionaries to organize information by key attributes like continents and years.
* **Data Transformation**: Cleaning and converting raw data for visualization.
* **Modular Programming**: Writing reusable functions to ensure the code is clean, understandable, and scalable.
* **Visualization Techniques**: Creating meaningful charts to make data trends visually compelling and easy to understand.

---
  
### Future Improvements
1. **Dynamic Data Source**:
* Implement API integration to fetch live data instead of relying on a static CSV file.
2. **Interactive Plots**:
* Use libraries like plotly or bokeh for interactive visualizations.
3. **Expanded Analysis**:
* Add statistical summaries (e.g., average growth rate, maximum population).
4. **Custom Styling**:
* Enhance chart aesthetics with custom color palettes and themes.

---
  
### Acknowledgments
This project is part of a Python programming course that covered topics like:

* **API Integration**
* **Data Structures**
* **Object-Oriented Programming (OOP)**
* **File and Data Manipulation**
* **Data Visualization**

Special thanks to **Our World in Data** for the dataset.

---

### Contact
If you have any questions or feedback, feel free to reach out:
* **GitHub**: ElizabethBeaton
* **Email**: elizabethbeaton23@outlook.com
