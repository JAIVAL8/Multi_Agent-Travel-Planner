# Multi-Agent Trip Assistant

This project is a multi-agent trip planning assistant powered by LLMs and LangChain. It helps users plan travel itineraries and find budget flights using weather and flight APIs.

## Features

- Detailed 1-week travel itinerary planning
- Weather data integration for destinations
- Flight search using Amadeus API
- Budget evaluation for round-trip flights
- Gradio web interface

## Setup

1. **Clone the repository**

2. **Install dependencies**

   ```
   pip install -r requirements.txt
   ```

3. **Set environment variables**

   - `GROQ_API_KEY`
   - `OPENWEATHERMAP_API_KEY`
   - `AMADEUS_CLIENT_ID`
   - `AMADEUS_CLIENT_SECRET`

   You can use a `.env` file or set them manually.

4. **Run Ollama server** (if using local LLM):
   ```
   ollama serve
   ```

## Usage

Run the notebook or launch the Gradio interface:

```
python tripPlanner.ipynb
```

Or:

```
python <script_with_gradio_interface>.py
```

## File Structure

- `tripPlanner.ipynb` — Main notebook with all logic
- `Readme.md` — Project documentation
- `.gitignore` — Ignore sensitive and unnecessary files

## Notes

- Ensure API keys are kept secret.
- For Amadeus API, register for credentials at [Amadeus for Developers](https://developers.amadeus.com/).
- For OpenWeatherMap, get your API key at [OpenWeatherMap](https://openweathermap.org/api).

## License

MIT License
