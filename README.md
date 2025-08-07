**Data visualization in D3.js**

**Purpose**
Use D3.js to create charts from the provided data

**Projects**

---

### 1. Monthly Revenue Chart

- Task: Visualize revenue and profit data from January to July using D3.js

- Input: data.csv file containing month, revenue, and profit columns

- Output: A bar chart with labeled axes and a readable layout

- Screenshot

  <img src="/screenshots/Project1.JPG" style="width:35%; height:35%;">

---

### 2. GDP Per Capita

- Task: Create a dynamic scatter plot clone of the Gapminder visualization showing the relationship between life expectancy and GDP per capita over time.

- Input: data.json file containing the following fields for each country and year:

country

year

income (GDP per capita)

life_exp (life expectancy)

population (optional, for circle size)

continent (optional, for color grouping)

- Output: A D3.js-powered scatter plot with:

X-axis: GDP per capita (log scale)

Y-axis: Life expectancy

Circle size: population

Circle color: continent

A year label that updates dynamically over time

Animation using d3.interval() that loops through the years by calling an update() function to redraw the chart with data from each year

- Screenshot

  <img src="/screenshots/Project2.JPG" style="width:35%; height:35%;">

---

### 3. Cryptocurrency Statistics

- Task: Build an interactive line chart to visualize historical cryptocurrency data (price, market cap, or 24h volume) for the top 5 coins. Allow users to select the coin, the metric to display, and the date range.

- Input: coins.json file containing daily data for multiple cryptocurrencies
  Each entry includes:

price_usd

market_cap

24h_vol

date

- Output: A D3.js-powered interactive line chart with:

Dropdown menus to select the coin and metric

Y-axis updating based on selected metric

Date range slider (jQuery UI) to zoom in/out on specific time periods

Smooth transitions for the line and axes on update

Formatted y-axis values (e.g. 1.5K, 2.2M, 43B)

Responsive and clean layout with updated labels and data filtering logic

- Screenshot

<img src="/screenshots/Project3.JPG" style="width:35%; height:35%;">

---

**Reference**
Udemy course: Mastering data visualization in D3.js

**End**
