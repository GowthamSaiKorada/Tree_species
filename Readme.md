# 🌳 Tree Intelligence Assistant

The **Tree Intelligence Assistant** is an interactive web app that recommends tree species based on location, size, and environmental attributes. It leverages machine learning to suggest suitable trees for planting and soon will support image classification through a CNN model.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Upcoming Features](#upcoming-features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

---

## 📖 About the Project

This project is a web-based assistant built with Streamlit that uses machine learning to recommend trees based on:
- Geographic location (Latitude, Longitude)
- Tree diameter
- Native/Non-native status
- City-level climate adaptation

---

## ✨ Features

- 🌍 **Recommend Trees by Location**  
- 📍 **Find Suitable Locations for a Tree**  
- 🧠 **(Coming Soon)** Tree Species Identification using CNN-based image classification  
- 🎛️ User-friendly interface to input tree attributes  
- 🌱 Native species prioritization for better ecological fit

---

## 📷 Screenshots

![App Screenshot](screenshot.png) <!-- Replace with the actual screenshot path if committed -->

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/GowthamSaiKorada/Tree_species.git
   cd Tree_species
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run streamlit_integrated.py
   ```

---

## 🛠️ Technologies Used

- **Streamlit** – Web app interface
- **Scikit-learn** – ML model for tree recommendation
- **Pandas, NumPy** – Data processing
- **Joblib** – Model and scaler persistence
- **Matplotlib** – Visualizations (optional)
- **Jupyter Notebook** – Model development and EDA

---

## 📁 Project Structure

```bash
Tree_species/
│
├── streamlit_integrated.py       # Main Streamlit application
├── nn_model.joblib               # Trained ML model
├── scaler.joblib                 # Feature scaler
├── tree_data.pkl                 # Processed dataset
├── create_demo_images.py         # Generates sample data
├── tree_CNN.ipynb                # CNN training notebook (in progress)
├── 5M_trees.ipynb                # Data analysis
├── requirements.txt              # Python dependencies
├── Procfile                      # Deployment setup (Heroku)
├── LICENSE
└── README.md                     # Project documentation
```

---

## 🔮 Upcoming Features

- ✅ Deployment to Hugging Face or Heroku
- ✅ City-based recommendation using more advanced climatic datasets
- 🔄 Real-time map integration (e.g., Leaflet or Folium)
- 🖼️ Image-based tree species classification using CNN
- 📊 Dashboard with insights and tree planting suggestions

---

## 🤝 Contributing

Contributions are welcome!  
To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push and open a pull request

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 📫 Contact

**Author**: Gowtham Sai Korada  
🌐 GitHub: [GowthamSaiKorada](https://github.com/GowthamSaiKorada)

---

## 🙏 Acknowledgements

- Open-source datasets from [Tree Census](https://www.nycgovparks.org/trees/treescount)
- Streamlit for the simple and elegant interface
- Scikit-learn community
- CNN architecture inspiration from TensorFlow tutorials

---
