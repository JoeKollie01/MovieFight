🎬 Movie Fight
Movie Fight is an interactive web app that allows users to search for and compare movies side by side using the OMDb API. Users can type in the name of a movie on both sides of the interface and get key statistics like box office numbers, ratings, awards, and more to determine which movie is "better."

🚀 Live Demo
(If deployed, insert link here)

📦 Features
🔍 Autocomplete Search: Built-in dropdown search powered by OMDb API.

📊 Side-by-Side Movie Comparison: Compare two movies across multiple metrics like:

Box Office

IMDB Rating & Votes

Awards

Metascore

📷 Movie Posters & Details: Instantly displays movie posters and a brief plot.

⚡ Debounced Input: Minimizes API requests during typing.

🛠️ Tech Stack
HTML5, CSS3 (Bulma Framework)

JavaScript (Vanilla)

Axios for HTTP requests

OMDb API for movie data

📁 File Structure
bash
Copy
Edit
├── index.html          # Main HTML layout
├── style.css           # Custom styles (optional, referenced in HTML)
├── index.js            # Main logic and comparison mechanics
├── autocomplete.js     # Reusable autocomplete component
├── utils.js            # (Optional) Utility functions
🔧 Setup & Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/movie-fight.git
cd movie-fight
Open index.html in your browser

No build step or server needed — it's a static site!

🧪 Development Tips
The autocomplete system is modular and reusable. You can adapt createAutoComplete() from autocomplete.js for other data sources.

To test different movie matchups, just enter different titles on the left and right input fields.

API key for OMDb is hardcoded (46c7aa43) — make sure it’s valid or replace it with your own from OMDb API.

📸 Preview
(Insert screenshots or a short gif of the app in action)

💡 Future Improvements
Add animations or highlight the "winning" movie per stat.

Responsive design enhancements for mobile users.

Store recent searches or compare history.

