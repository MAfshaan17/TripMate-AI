# TripMate-AI 


This is multi agent project wherein we evrything is done together using LangGraph, MCP, supervisor and HITL

this project is made to implement the work of what i have leanrt so far evrything here is hard coded so lets build thus project for now this is my readme later i will modify this in to a professional wala lets do it...

Agents:
1. Flight Agent - Search flights and finds best option
 AviationStack api key 
2. Hotel Agent - Search hotels and compares options
Tavily search
Itinerary Agent - Creates day-wise itinerary, places to visit activities
 Tavily search 
Final response - Combines all information and generates final response
 groq LLm ( llama 3)
 
Shared State (TravelState)
suer_query  flight_results hotel_results itinerary final_response message

Everything is sued in PostgreSQL -- Long-term Memory 
stores -
   Conversation history
   User perferences
   Agent outputs and state updates
   

# How to run ?

1. Create the Virtual Envirnoment

```bash
conda create -n travel python=3.11 -y

2. Activate the Environment 

```bash
conda activate travel 

3. Install the requirements

```bash 
 pip install -r requirements.txt

