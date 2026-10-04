📸 MacroSnap

MacroSnap is a simple AI-powered nutrition analysis application that helps users estimate the nutritional information of food from an image.

Users can upload a food image, and MacroSnap analyzes it to provide useful nutritional information such as calories, protein, carbohydrates, fats, and other relevant details.

🚀 Features

- 📷 Upload a food image
- 🤖 AI-powered food analysis
- 🍽️ Identify food items from images
- 🔥 Estimate calories
- 💪 Estimate protein
- 🍞 Estimate carbohydrates
- 🥑 Estimate fats
- 📊 Display nutritional information in an easy-to-understand format
- 🌐 Simple and user-friendly Streamlit interface

🛠️ Technologies Used

- Python
- Streamlit
- AI / Large Language Model API
- Pillow (PIL)
- Git & GitHub

📂 Project Structure

MacroSnap/
│
├── app.py
├── prompts.py
├── requirements.txt
├── .gitignore
├── .streamlit/
│   └── secrets.toml.example
└── README.md

⚙️ Installation

1. Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL
cd MacroSnap

2. Create a virtual environment

python -m venv venv

Activate the environment on Windows:

venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Configure API keys

Create your Streamlit secrets file:

.streamlit/secrets.toml

Add your required API key according to the configuration used in the project.

Do not upload your actual API keys or "secrets.toml" to GitHub.

5. Run the application

streamlit run app.py

The application will open in your browser, usually at:

http://localhost:8501

🖥️ How It Works

1. Open MacroSnap.
2. Upload a picture of your food.
3. MacroSnap sends the image and appropriate prompt to the AI model.
4. The AI analyzes the food.
5. The application displays the estimated nutritional information.
6. Users can use the results to better understand the nutritional content of their meal.

🌐 Deployment

MacroSnap can be deployed online using a Streamlit-compatible hosting platform.

After deployment, users can access the application through a public web link instead of running it only on "localhost".

🔐 Security

API keys and other sensitive information should be stored using Streamlit Secrets.

Never commit private API keys to GitHub.

The repository includes:

.streamlit/secrets.toml.example

as an example configuration file.

⚠️ Disclaimer

The nutritional values provided by MacroSnap are estimates generated using AI and should not be considered medically accurate or a substitute for professional nutritional advice.

Actual nutritional values may vary depending on ingredients, portion size, preparation method, and other factors.

🔮 Future Improvements

- 👤 User accounts and profiles
- 📱 Improved mobile experience
- 📈 Daily and weekly nutrition tracking
- 🗂️ Meal history
- 🎯 Personalized nutrition goals
- 📊 Nutrition dashboards and charts
- 🔔 Meal and nutrition reminders
- 🌍 Support for more food types and cuisines
- 📲 Progressive Web App (PWA) support

👨‍💻 Author

Ansar Basha

MacroSnap — AI-powered food and nutrition analysis.

---

⭐ If you find this project useful, consider giving the repository a star!
