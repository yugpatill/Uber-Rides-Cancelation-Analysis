# 🚕 Uber Ride Cancellation Analysis

This project analyzes **Uber ride booking data** to understand the patterns and reasons behind ride cancellations.  
Using **Python, Pandas, NumPy, Matplotlib, and Seaborn**, the project explores cancellation trends across drivers, customers, vehicle types, locations, and time.

---

# 📊 Project Overview

Ride cancellations negatively affect:

- Customer satisfaction
- Driver efficiency
- Platform reliability

This project analyzes **150,000 Uber ride bookings** to uncover patterns and generate insights that could help improve ride fulfillment rates.

Key questions explored:

- Who cancels more rides — drivers or customers?
- Which vehicle types have the highest cancellations?
- Which pickup and drop locations experience the most cancellations?
- At what time of day do cancellations peak?

---

# 📂 Dataset

The dataset contains **150,000 ride booking records** with **21 features** including:

| Feature | Description |
|------|------|
| Date | Booking date |
| Time | Ride booking time |
| Booking Status | Completed / Cancelled / Incomplete |
| Vehicle Type | Type of ride booked |
| Pickup Location | Starting location |
| Drop Location | Destination |
| Booking Value | Ride fare |
| Ride Distance | Distance of the ride |
| Driver Ratings | Rating given to driver |
| Customer Rating | Rating given by driver |
| Payment Method | Mode of payment |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🔎 Project Workflow

### 1️⃣ Data Loading
- Imported dataset
- Checked dataset structure

### 2️⃣ Data Cleaning
- Handled missing values
- Standardized vehicle types
- Converted date and time formats
- Replaced unknown values

### 3️⃣ Exploratory Data Analysis (EDA)

Analysis included:

- Booking status distribution
- Driver vs customer cancellations
- Cancellations by vehicle type
- Top pickup locations with highest cancellations
- Top drop locations with highest cancellations
- Cancellations by hour of the day

### 4️⃣ Data Visualization

Used visualizations such as:

- Pie charts
- Bar charts
- Count plots
- Line plots
- Tree maps

---

# 📈 Key Insights

### Driver vs Customer Cancellations

Drivers cancel significantly more rides than customers.

- Driver cancellations ≈ **25,000**
- Customer cancellations ≈ **10,000**

This suggests possible **driver availability or operational challenges**.

---

### Vehicle Type Analysis

Vehicle types with highest cancellations:

- Auto
- Go Mini
- Go Sedan

Four-wheelers appear more prone to cancellation.

---

### Pickup Locations with Highest Cancellations

Areas with the most cancellations:

- Saket
- Pragati Maidan
- Akshardham
- Vinobapuri
- Nehru Place

These locations likely face **high demand with limited driver availability**.

---

### Drop Locations with Highest Cancellations

Frequent cancellation destinations include:

- Uttam Nagar
- Keshav Puram
- Ghaziabad

Possible reasons include long distance or traffic conditions.

---

### Peak Cancellation Hours

Highest cancellation times:

- **10 AM**
- **3 PM**
- **6 PM**

These hours represent peak demand periods.

---

# 💡 Business Recommendations

Based on the analysis:

- Increase driver supply in high-demand areas
- Introduce incentives during peak hours
- Improve driver–customer matching
- Monitor high-cancellation vehicle categories
- Optimize driver allocation in peak zones

---

# 🚀 How to Run the Project

Clone the repository:

```bash
git clone https://github.com/yugpatill/Uber-Rides-Cancelation-Analysis.git
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```
uber-rides-cancelation-analysis.ipynb
```

---

# 📁 Repository Structure

```
Uber-Rides-Cancelation-Analysis
│
├── uber-rides-cancelation-analysis.ipynb
├── README.md
```

---

# 👨‍💻 Author

**Yugandhar Patil**


GitHub:  
https://github.com/yugpatill

---
