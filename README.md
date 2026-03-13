# AI Travel Itinerary Planner

An AI-powered travel planning system that generates structured, budget-aware travel itineraries using **Google Gemini**, interactive maps, and automated travel calculations.

The system combines **Generative AI with deterministic backend logic** to ensure reliable itinerary generation, distance optimization, and professional travel plan outputs.

---

## Features

- AI-powered itinerary generation using Google Gemini
- Budget-aware travel planning
- Distance and travel time calculation
- Interactive route map visualization
- Editable travel itinerary
- AI place enrichment for custom locations
- Per-place chat assistant
- Airport transfer calculations
- PDF export of travel plans

---

## Tech Stack

**Programming**
- Python

**AI Model**
- Google Gemini 2.5 Flash

**Framework**
- Streamlit

**Mapping**
- Folium  
- Streamlit-Folium

**PDF Generation**
- ReportLab

**Utilities**
- dotenv
- Haversine distance calculation

---

## Project Structure

```
travel-itinerary-ai
│
├── app.py
│
├── services/
│   ├── gemini_client.py
│   ├── itinerary_service.py
│   ├── place_service.py
│   └── chat_service.py
│
├── utils/
│   ├── airport_renderer.py
│   ├── daily_itinerary_renderer.py
│   ├── itinerary_renderer.py
│   ├── header_renderer.py
│   ├── hotel_renderer.py
│   ├── chat_renderer.py
│   ├── tips_renderer.py
│   ├── distance_calculator.py
│   ├── map_renderer.py
│   └── pdf_generator.py
```

- **services/** → AI services and backend logic  
- **utils/** → UI rendering, maps, distance calculations, PDF generation  
- **app.py** → Main Streamlit application

---

## Installation

Clone the repository

```
git clone https://github.com/Dhyey2294/AI-Travel-Itinerary-Planner.git
```

Navigate to the project folder

```
cd AI-Travel-Itinerary-Planner
```

Install dependencies

```
pip install -r requirements.txt
```

Run the application

```
streamlit run app.py
```

---

## System Architecture

```
User Input
   ↓
Gemini AI
   ↓
Structured JSON Extraction
   ↓
Distance Calculation Engine
   ↓
Map Rendering
   ↓
Editable Itinerary
   ↓
AI Place Enrichment
   ↓
Chat Assistant
   ↓
PDF Export
```

---

## Author

**Dhyey Patel**

Computer Engineering Student  
Interested in Artificial Intelligence, Machine Learning, and Data Science