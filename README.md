# 🍽️ Zomato Data Analysis

This project performs exploratory data analysis (EDA) on a Zomato restaurant dataset using Python, Pandas, Matplotlib, and Seaborn. The aim is to extract insights from customer ratings, online ordering behavior, cost for two, and restaurant types.

---

## 📁 Dataset

The dataset used is named `Zomato data .csv` and contains information about various restaurants, including:

- Restaurant name
- Online ordering availability
- Table booking option
- Rating
- Votes
- Approximate cost for two people
- Type of listing (e.g., Buffet, Cafes, Dining)

---

## 📊 Key Steps Performed

### 1. **Data Loading & Inspection**
- Loaded CSV into a pandas DataFrame
- Inspected with `.head()`, `.tail()`, `.describe()`, `.info()`

### 2. **Data Cleaning**
- Converted rating column (`'4.1/5'`) to float (`4.1`)
- Renamed long column names for easier access

### 3. **Exploratory Data Analysis**
- Count of restaurants by type
- Total votes per restaurant type
- Online ordering vs ratings (boxplot)
- Rating distribution (histogram)
- Cost for two people distribution
- Heatmap: Online order vs Restaurant type
- Identified restaurant with highest votes

### 4. **Visualizations**
- `Seaborn` and `Matplotlib` used for:
  - Count plots
  - Line plots
  - Box plots
  - Histograms
  - Heatmaps

---

## 📈 Visual Outputs

Some of the key visuals generated include:
- Countplot of restaurant types
- Histogram of customer ratings
- Boxplot of rating vs online ordering
- Line plot of total votes by type
- Heatmap showing restaurant type vs online order availability

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ParthaDas-666/zomato-data-analysis.git
   cd zomato-data-analysis
