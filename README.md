# allergy_friendly_restaurants

EZ Dietaary Dining App: User Guide

This app helps you find restaurants near a location you enter (ZIP, city, or county). Users can search using a radius between 5-50 miles from the location. Users can filter optionally by dietary need (gluten free, vegan, or dairy free right now). It uses a map-based search and displays nearby results based on your input.

Installation Requirements
    Python 3.10+
    pip (Python package manager)

Clone
    gh repo clone ctlott00/allergy_friendly_restaurants

Install Dependencies
    pip install -r requirements.txt
    OR
    pip install streamlit requests pandas

Running the App
    To run on mobile or desktop: use this URL: https://ez-dietary-dining.onrender.com
    Alternatively, I run this using this command in my terminal: streamlit run app.py

    Step 1: Enter Location: type a ZIP code, city, or county into the location box
    Step 2: Adjust Search Radius: Choose how far out to search
    Step 3: Choose dietary needs
    Step 4: Click Search: Results will display below
    Step 5: View Results: Restaurants appear in a map

Common Issues + Fixes
    Problem: No results found
    Solution: Try a larger radius

    Problem: Invalid location	
    Solution: Try a more specific input

Known Limitations
    Some locations may return limited data
    API rate limits may restrict usage
    UI styling may vary slightly across devices

Screenshots
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)

Future Ideas to Improve
    Better filtering (price, rating, cuisine)
    Map visualization enhancements
    Save favorite restaurants