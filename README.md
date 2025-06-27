# IISc_internship
## 🔰 Introduction

**ThermoSecure** is a web-based application developed as part of an internship project at the **Indian Institute of Science (IISc)**. The objective of this project is to provide a secure and interactive platform for analyzing and visualizing thermodynamic and transport properties of chemical species using standardized NASA datasets. It enables users to work with both individual species and mixtures, making it valuable for educational, research, and scientific analysis purposes.

---

## 💡 What the Project Does

ThermoSecure provides the following key functionalities:

- 🔐 Secure user registration and login
- 📂 Upload support for **thermodynamic** and **transport** datasets (NASA format)
- 🔬 View, search, and select individual species from uploaded datasets
- 📊 Generate interactive graphs for:
  - Heat Capacity (Cp)
  - Enthalpy (H)
  - Entropy (S)
- 🧪 Select multiple species and input mole fractions to analyze **mixture properties**
- 💾 Save plotted graphs as images (PNG format)
- 📌 Log all user activities (uploads, selections, plots, downloads) to the backend

---

## ⚙️ How It Works (Overview)

1. **Authentication**:  
   Users create an account and log in. Sessions are tracked using browser local storage.

2. **Dataset Upload**:  
   Users upload NASA-formatted thermodynamic or transport datasets. The application parses these files and extracts relevant species data.

3. **Species Selection & Plotting**:  
   Users select any available species and visualize Cp, H, and S properties as a function of temperature using dynamic Chart.js plots.

4. **Mixture Analysis**:  
   Multiple species can be selected for mixture analysis. Users specify mole fractions for each, and the app computes and plots the resulting properties of the mixture.

5. **Activity Logging**:  
   Every user action — from file upload to graph plotting and saving — is logged into a SQLite database for traceability and reporting.

---

## 🎯 Project Outcomes

- ✅ Developed a complete, full-stack web application from scratch
- ✅ Enabled visualization of scientific data with intuitive user interaction
- ✅ Simplified analysis of multi-species mixtures through mole fraction input
- ✅ Implemented secure login and user-specific activity tracking
- ✅ Created a reusable tool for NASA polynomial dataset validation and education

---

## 🧪 Applications

- 🏫 Academic tool for teaching thermodynamic concepts and properties
- 🔍 Research aid for analyzing individual species or mixture behavior
- 🛠 Preprocessing tool for verifying NASA polynomial datasets
- 🔐 Secure and auditable access to scientific visualization in institutional settings

---

## 👩‍💻 Made By

[@Kshithishetty21](https://github.com/Kshithishetty21)  
[@Vaishnavishettyy](https://github.com/Vaishnavishettyy)  
Interns @ IISc | ThermoSecure Project


---
