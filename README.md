# 🦈 Advanced Shark Telemetry Dashboard

This repository hosts the **front-end visualization interface (Dashboard)** for the **Advanced Shark Monitoring Chip**, our innovative hardware project focused on deep-sea marine biotelemetry.

The core mission of this dashboard is to transform complex, raw data collected by underwater sensors (like heart rate, pH levels, and acceleration) into a simple, accessible, and actionable format for researchers, conservationists, and wildlife managers. It serves as the user's **simple screen** to interpret the shark's "marine black box."

## 🚀 Key Features and Functionality

The dashboard provides a clear window into the shark's secret life, displaying key information in an intuitive layout:

* **Physiological Monitoring:** Displays **real-time or historical heart rate** data, allowing researchers to analyze stress levels, energetic costs of behavior (like migration), and overall health.
* **Behavioral Ecology Mapping:** Uses **accelerometer** data (motion) and GPS regions to visually map and highlight specific **feeding events** and swimming patterns over geographic regions.
* **Environmental Analysis:** Presents continuous readings of **water pH** and **temperature** in aggregation areas, providing crucial insight into how the immediate environment affects the animal's physiology.
* **Simple Visualization:** Data is presented via clean, responsive charts, interactive maps, and easy-to-read gauges, eliminating the need for manual data processing by the user.

## 🛠️ Technology Stack (Front-end)

This dashboard is designed for speed, responsiveness, and clear data presentation.

| Category | Technology (Suggested) | Purpose |
| :--- | :--- | :--- |
| **Language** | JavaScript (or TypeScript) | Core logic and functionality. |
| **Framework** | **React / Vue / Angular** | Building the single-page application and component structure. |
| **Data Viz** | **D3.js / Chart.js / Plotly** | Generating responsive physiological and environmental charts. |
| **Mapping** | **Mapbox GL JS / Leaflet** | Displaying shark location and migration paths on an interactive map. |
| **Styling** | **Tailwind CSS / Styled Components** | Ensuring a clean, modern, and user-friendly interface. |

## ⚙️ Setup and Installation

Follow these steps to get the visualization dashboard running on your local machine.

### Prerequisites
* Node.js and npm (or yarn) installed.

### Installation Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/GabrielRegel/NASA2025.git](https://github.com/GabrielRegel/NASA2025.git)
    cd NASA2025
    ```
2.  **Install Dependencies:**
    ```bash
    npm install
    # or yarn install
    ```
3.  **Run the Development Server:**
    ```bash
    npm start
    # or yarn dev
    ```
    The application will typically open in your browser at `http://localhost:3000`.

## 🤝 Contribution

We welcome contributions! If you have suggestions for new visualizations, bug fixes, or performance improvements, please feel free to open an Issue or submit a Pull Request.
