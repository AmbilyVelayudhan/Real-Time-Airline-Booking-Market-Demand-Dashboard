# ✈️ Real-Time-Airline-Booking-Market-Demand-Dashboard

📌 Project Overview

This project is a real-time web dashboard built using Streamlit, designed to visualize and analyze market demand in the airline booking industry. It leverages the Aviationstack API to fetch live flight data and displays interactive visualizations that help understand trends such as:

* Most popular routes

* Frequently used airlines

* Busiest departure airports

* Flight status distribution (Scheduled, Active, Delayed, Cancelled)

🎯 Objectives

✅ Automatically fetch live airline booking data from a public API

✅ Clean and process the data for trend extraction

✅ Provide visual insights via charts (Altair) and tables

✅ Display a real-time summary report for business understanding

✅ Keep the interface user-friendly, intuitive, and non-technical

🚀 Features

🔁 Real-Time Data Fetching

* Connects to Aviationstack API

* Pulls the latest 100 global flights every time the dashboard is loaded

* No user input required — data auto-refreshes

📊 Visual Insights

* Popular Routes: See where most flights are departing and arriving

* Top Airlines: Identify the most active airlines at the moment

* Flight Status Trends: Monitor operational performance (on-time, delayed, cancelled)

* Top Departure Airports: Find out which airports are most active right now

📝 Auto-Generated Summary

A live overview is generated from the latest data including:

* Top 3 airlines

* Top 3 departure airports

* Busiest route currently

* Flight status breakdown

🖥️ Tech Stack

| Component | Tool                      |
| --------- | ------------------------- |
| Web App   | Streamlit                 |
| API       | Aviationstack (Free tier) |
| Charts    | Altair                    |
| Data      | Pandas                    |
| Language  | Python                    |

📁 Project Structure

airline_demand_app/

├── app.py                     
├── aviationstack_api.py       
├── utils.py                   
├── requirements.txt           
├── README.md                  

⚙️ Setup Instructions

1. Clone the repository
    git clone https://github.com/yourusername/airline-demand-dashboard.git
    cd airline-demand-dashboard

2. Install dependencies
    pip install -r requirements.txt

3. Add your Aviationstack API key
    In aviationstack_api.py, replace 'YOUR_API_KEY_HERE' with your actual API key from https://aviationstack.com.

4. Run the app
    streamlit run app.py
   
📦 Requirements

    streamlit
    pandas
    altair
    requests
 

