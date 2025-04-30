<!DOCTYPE html>


<div class="section">
  <h1>🏠 Airbnb Bookings Analysis (NYC 2019)</h1>
  <p><strong>Project Type:</strong> EDA (Exploratory Data Analysis)<br>
     <strong>Contributor:</strong> Himanshu Sharma</p>
</div>

<div class="section">
  <h2>📌 Project Summary</h2>
  <p>This project analyzes the Airbnb NYC 2019 dataset to understand how room types, neighborhoods, pricing, availability, and reviews impact guest behavior and host success. The main goal is to help Airbnb hosts make better decisions about pricing and listing management based on data trends.</p>
</div>

<div class="section">
  <h2>🗂️ Dataset Info</h2>
  <ul>
    <li>48,000+ listings across New York City</li>
    <li>Fields: <code>price</code>, <code>room_type</code>, <code>neighbourhood_group</code>, <code>reviews_per_month</code>, <code>availability_365</code>, etc.</li>
    <li>Source: Airbnb Open Data (2019)</li>
  </ul>
</div>

<div class="section">
  <h2>🧹 Cleaning & Preparation</h2>
  <ul>
    <li>Missing values handled in <code>reviews_per_month</code> and <code>host_name</code></li>
    <li>Outliers removed from <code>price</code> and <code>minimum_nights</code></li>
    <li>Dropped columns like <code>id</code> and <code>host_id</code> for clarity</li>
  </ul>
</div>

<div class="section">
  <h2>📊 Key Insights</h2>
  <ul>
    <li>Most listings are in Manhattan and Brooklyn</li>
    <li>Entire homes have the highest prices, but private rooms get more reviews</li>
    <li>Hosts with many listings tend to charge more (professional hosts)</li>
    <li>Most listings priced under $300 per night</li>
    <li>Availability is often either full year (365 days) or seasonal (few days)</li>
  </ul>
</div>

<div class="section">
  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li>Python 3.x</li>
    <li>Pandas, NumPy, Matplotlib, Seaborn</li>
    <li>Jupyter Notebook</li>
  </ul>
</div>

<div class="section">
  <h2>▶️ How to Run</h2>
  <pre><code>pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook eda.ipynb
</code></pre>
</div>

<div 

</body>
</html>
