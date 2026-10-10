# 🌱 AI AGRO AGENT
> **Tagline:** *"Grow Smarter. Sell Directly. Protect Every Harvest."*

AI AGRO AGENT is an AI-powered farming companion and direct agricultural marketplace designed for Indian farmers (specifically tailored to Telangana, with Warangal, Hanamkonda, Karimnagar, and Hyderabad markets).

---

## 🚀 Key Features

### 1. 🏆 8-Step Interactive "Judge Demo" Mode
- Accessible via the **"🏆 Judge Demo"** button in the header.
- Guides judges through an end-to-end interactive journey:
  1. **Step 1:** Farmer lists 500 kg of Hybrid Tomatoes at farmgate.
  2. **Step 2:** Real-time Mandi vs. Direct Buyer Arbitrage Engine calculates transport deductions and highlights **+₹8,500 extra net margin**.
  3. **Step 3:** Matches demand with verified retailers and gated residential societies (Aparna Sarovar, Hyderabad).
  4. **Step 4:** Farmer confirms a 250 kg direct order with 40% advance payment escrow and assigns transport.
  5. **Step 5:** AI Crop Doctor runs leaf pathology on tomato foliage, detecting Early Blight with organic solutions.
  6. **Step 6:** Smart Irrigation Planner credits 42 mm forecasted rainfall and instructs the farmer to shut off the drip pump.
  7. **Step 7:** WeatherGuard issues heavy-rain waterlogging precautions with a 3-phase checklist (Before, During, After).
  8. **Step 8:** AgriShield AutoProtect™ detects 48 mm/h rainfall, passes structural wind checks, and **autonomously deploys the motorized retractable crop canopy**!

---

### 2. 🛡️ AI AGRO AGENT AutoProtect™ (Signature Hardware & IoT Simulator)
- **2D Smart-Farm Canvas:** Features healthy crop furrows and a dynamically animated retractable polyethylene canopy (0% to 100% position).
- **Interactive Micro-Climate Sliders:**
  - Rain Intensity (0 - 100 mm/h)
  - Wind Velocity (0 - 90 km/h)
  - Ambient Temperature (15 - 48°C)
  - Soil Moisture (10 - 100%)
- **Autonomous Scenarios:**
  - **Scenario A (Cloudburst):** Deploys canopy when rainfall exceeds 25 mm/h.
  - **Scenario B (Gale Wind):** Retracts and locks canopy when wind exceeds 45 km/h to prevent structural air-lift tearing.
  - **Scenario C (Heatwave):** Deploys canopy to 50% shading position for crop cooling.
  - **Scenario D (Nominal Sunshine):** Retracts canopy for full solar photosynthesis.
  - **Scenario E (Sensor Failure):** Triggers fail-safe motor isolation and technician alert.
- **Live Event Timeline & Hardware Diagram:** Documents ESP32 edge microcontroller integration, dual linear actuators, optical limit switches, and battery backup.

---

### 3. 🏪 AgriMarket: Direct Crop Selling & Arbitrage
- **Direct Crop Listing:** Farmers configure crop variety, quantity (kg/quintals), harvest date, quality grade, and minimum price.
- **Explainable Ranking Engine:**
  $$\text{Net Farmer Earnings} = (\text{Sale Price} \times \text{Qty}) - \text{Transport} - \text{Handling/Mandi Fees}$$
- **Farm-to-Home Orders:** Apartment societies (Aparna Sarovar, My Home Bhooja) post recurring bulk produce demands. Features **Order Consolidation** where multiple smallholder farmers combine harvests for shared freight savings.
- **Direct Buyer Directory:** Profiles for neighborhood retailers, hotel kitchens, student mess hostels, and processors with verified status.

---

### 4. 🔬 AI Crop Doctor
- Dual photo upload and preloaded Telangana field test cases (Tomato Early Blight, Chilli Leaf Curl Virus).
- Structured diagnostic reports:
  - Disease/pest identification with confidence meter
  - Observed visual symptoms and differential diagnoses
  - 24-hour immediate field actions
  - Organic & bio-control options (Trichoderma, Pseudomonas, neem extract, butter-milk spray)
  - Strictly label-compliant chemical alternatives (with pre-harvest intervals and mandatory PPE warnings)
  - When to consult Mandal Agricultural Officer (MAO) or KVK scientists.

---

### 5. 💧 Smart Irrigation Planner
- Dynamic water budgeting accounting for crop stage, soil texture (Red chalka vs Black cotton), and irrigation method (Drip, Sprinkler, Furrow, Basin).
- Weather-responsive credit: Automatically accounts for forecasted rain and pauses pumps to prevent root rot and save electricity.

---

### 6. 📅 Seasonal Crop Planner & 🌿 Organic Fertilizer Guide
- **Telangana Crop Calendar:** Sowing windows, duration, pest alerts, and market outlook for Kharif, Rabi, and Summer seasons.
- **Organic Input Estimator:** Calculates exact bag quantities of Vermicompost, Neem Cake, Farmyard Manure, and Bio-fertilizers based on farm acreage.

---

### 7. ⛅ WeatherGuard™ & 🎙️ Multilingual AI Voice Assistant
- Real-time weather telemetry with audio warning bulletins in **Telugu (తెలుగు)** and **English (EN)** using browser Web Speech API.
- Microphone voice input and conversational farming advisory grounded in local agricultural data.

---

## 🛠️ Technology Stack
- **Frontend:** React 19, TypeScript, Vite
- **Styling:** Tailwind CSS (v4)
- **Charts:** Recharts
- **Icons:** Lucide React
- **Voice:** Web Speech API (Synthesis & Recognition)
- **AI Engine:** Google Gemini API integration with offline agronomy rules engine fallback

---

## 💻 Local Setup & Running

```bash
# Clone or navigate to directory
cd d:/farmer

# Install dependencies
npm install

# Start development server
npm run dev
```

Visit: `http://localhost:5173/`

### Optional: Google Gemini API Key
To connect a live Google Gemini API key:
1. Create a `.env` file in the project root:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```
2. Or simply paste your API key in **"My Farm & Settings"** inside the application.
3. *Note:* If no key is provided, AI AGRO AGENT seamlessly runs on its built-in expert agricultural decision engine!
