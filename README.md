 Zomato Data Analysis

This project performs exploratory data analysis on a Zomato restaurant dataset using Python and popular data science libraries. The analysis provides insights into restaurant types, ratings, and voting patterns across different categories.

 📂 Project Structure

* `zomato data analysis .ipynb` – Jupyter Notebook containing all code and visualizations.
* Dataset– The notebook assumes the dataset is saved as `Zomato data .csv` in the same directory.

## 📊 Key Features of the Analysis

 **Data Cleaning**:
  * Handled and cleaned the "rate" column using a custom function to extract numeric values.

 **Exploratory Data Analysis**:

  * Used `Seaborn` and `Matplotlib` for plotting restaurant types and vote distributions.
  * Analyzed restaurant type distribution using count plots.
  * Plotted total votes received per restaurant type.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📌 How to Run the Notebook

1. Clone this repository or download the `.ipynb` file.
2. Ensure the Zomato dataset is named **`Zomato data .csv`** and placed in the same folder.
3. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Run the notebook using Jupyter:

   ```bash
   jupyter notebook "zomato data analysis .ipynb"
   ```

---

## 📈 Sample Visualizations

* 📦 Count plot for restaurant types
* 📉 Line graph of total votes per restaurant type

## 💡 Future Improvements

* Add more visualizations: cuisine popularity, average ratings by location, etc.
* Incorporate geographic data for map-based insights.
* Use interactive tools like Plotly or Tableau for dashboards.
