
# SUNWISE  
Sunwise is a web application that predicts the average solar energy received in a given area and visualizes it through interactive graphics. By inputting an address, available rooftop area, and monthly electricity bill, users can understand their solar potential and sustainability impact—helping them make informed decisions toward a greener future. 

## Installation

📦 Backend (Flask + ML Models)
Clone the repository:

```bash
git clone https://github.com/AtharvPat/Scarlet_Hawks_Hackathon_2025.git
```
```bash
cd Scarlet_Hawks_Hackathon_2025
```
Install Python dependencies:
```bash
pip install flask flask_cors torch scikit-learn==1.2.2
```


## Deployment

To deploy this project run. 

Navigate to the backend directory
```bash
  python app.py
```
Navigate to the frontend directory:

```bash
cd src
```

Install frontend dependencies:
```bash
npm install
```
Run the development server:
```bash
npm run dev
```

The application will be live on local host


## Features

- Monthly Solar Energy Estimation for buildings in Chicago.
- Visual Analytics including:
    - Annual Energy Output
    - Carbon Offset
    - Tree Equivalent of savings
    - Monthly Cost Savings
    - Roof Qualification
- Sunroof Detection from satellite imagery
- User-friendly Interface for exploring your solar savings


## Sustainability Impact

By simulating real-world savings and environmental impact, SolarSight empowers homeowners and urban planners to:

- Maximize solar efficiency

- Offset carbon emissions

- Understand ROI on solar panel installations

- Visualize eco-conscious decisions
## Tech Stack

**Client:** React, Vite

**Server:** NodeJS

**Machine learning:** Scikit-learning, Pytorch

## Contributing

**Avneet Singh:** Machine Learning & Data Collection
    Built a Random Forest regression model using solar potential data from NASA for various coordinates across Chicago.

**Manthan Surjuse and Atharv Patil:** Sunroof Detection
    Developed a deep learning model using PyTorch and transfer learning to identify sunroof areas via image recognition.

**Nishant Khandhar and Atharv Patil:** Web Development
    Created a fully responsive React.js interface integrated with Flask and Node.js for real-time visualization and input processing.


## Data Sources
- NASA’s Solar Energy Data through Power API

- Google Maps Imagery for rooftop analysis