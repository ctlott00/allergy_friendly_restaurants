
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
<img width="1243" height="893" alt="Screenshot 2026-08-03 at 10 41 36 PM" src="https://github.com/user-attachments/assets/5887bed3-dfe8-49e7-a6bd-3b390d51f6fa" />
<img width="1238" height="897" alt="Screenshot 2026-08-03 at 10 42 09 PM" src="https://github.com/user-attachments/assets/4edf2936-d88e-460c-b99d-cd192163c034" />
<img width="1118" height="603" alt="Screenshot 2026-08-03 at 10 43 06 PM" src="https://github.com/user-attachments/assets/29c24f5b-c2ba-4092-b737-8b1653c3f142" />

Future Ideas to Improve
    Better filtering (price, rating, cuisine)
    Map visualization enhancements
    Save favorite restaurants
