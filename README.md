An interactive sales analytics dashboard built with Plotly.js and styled with a glassmorphism UI.
It allows you to upload your own sales JSON file and instantly explore performance insights through interactive charts.

🚀 Getting Started

Follow these steps to set up and run the dashboard:

2️⃣ Open the Project

Navigate to the project folder and open the file:

sales_dashboard_glass.html


You can open it directly in your browser (Chrome, Firefox, Edge, Safari).

⚠️ No server or installation is required — everything runs client-side!

3️⃣ Prepare Your JSON Data

Your sales data should be structured like this (one record per order):

{
  "ORDERNUMBER": 10107,
  "QUANTITYORDERED": 30,
  "PRICEEACH": 95.7,
  "ORDERLINENUMBER": 2,
  "SALES": 2871,
  "ORDERDATE": "2/24/2003 0:00",
  "STATUS": "Shipped",
  "QTR_ID": 1,
  "MONTH_ID": 2,
  "YEAR_ID": 2003,
  "PRODUCTLINE": "Motorcycles",
  "MSRP": 95,
  "PRODUCTCODE": "S10_1678",
  "CUSTOMERNAME": "Land of Toys Inc.",
  "PHONE": 2125557818,
  "ADDRESSLINE1": "897 Long Airport Avenue",
  "CITY": "NYC",
  "STATE": "NY",
  "POSTALCODE": 10022,
  "COUNTRY": "USA",
  "TERRITORY": "NA",
  "CONTACTLASTNAME": "Yu",
  "CONTACTFIRSTNAME": "Kwai",
  "DEALSIZE": "Small"
}


👉 You can also upload an array of multiple order objects in the same format.

4️⃣ Upload Your Data

Open sales_dashboard_glass.html in your browser.

Click Upload sales JSON.

Select your JSON file from your computer.

The dashboard will automatically parse the data and generate charts.

📊 Visualizations

The dashboard generates five key insights:

📈 Sales Trend Over Time – Line chart showing revenue growth.

📦 Sales by Product Line – Bar chart highlighting product performance.

🥧 Sales by Deal Size – Pie chart for small/medium/large deals.

🌍 Sales by Country – Choropleth map for regional sales distribution.

🏆 Top 10 Customers – Horizontal bar chart of best customers.

🎨 UI & Design

Glassmorphism Styling:

Transparent cards with frosted glass effect

Rounded corners and smooth shadows

Background: Icy blue gradient

Chart Padding: 40% width per chart for neat layout

Responsive: Scales well across screen sizes

📂 Project Structure
.
├── sales_dashboard_glass.html   # Main interactive dashboard
└── README.md                    # Documentation

🛠️ Tech Stack

HTML5 / CSS3 – Layout & styling

JavaScript (ES6) – Data handling

Plotly.js
 – Interactive charting library

Glassmorphism Design – Modern UI effect

🔮 Future Enhancements

Add filter dropdowns (Year, Product Line, Country)

Enable export to PNG/PDF/CSV

Add animated transitions when switching charts
