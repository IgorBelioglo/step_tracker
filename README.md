# step_tracker
Markdown
# PathStep — Step Tracker & Movement Analytics

**PathStep** is a mobile Flutter application that tracks user walks on a map, applies a **fog-of-war reveal effect**, detects frequently visited places using algorithms (**Stay Point Detection + Clustering**), and analyzes overall movement patterns.

Created as part of the *Algorithms Design and Analysis* course.

---

## 📦 How to Download Full Project / Как скачать полный проект

> ⚠️ **Note:** The complete source repository archive and binary files exceed GitHub's single-file size limits.

To download the full ready-to-run project zip archive:

1. Go to the **[Releases / Tags](https://github.com/IgorBelioglo/step_tracker/releases)** section in this repository.
2. Under the latest version (`v1.0.0`), find the **Assets** section.
3. Click on the `.zip` archive file to download the complete codebase.

---

## ✨ Key Features

- **🗺️ Map & Fog-of-War Effect:** Visualizes real-time walk tracks on an interactive map, gradually clearing the "fog" as you explore new areas.
- **📍 Stay Point Detection:** Automatically identifies locations where the user spends significant time.
- **📊 Cluster Analysis:** Groups frequent stop points to reveal movement patterns and key personal locations.
- **📈 Motion Analytics:** Tracks total steps, distances covered, and route historical statistics.

---

## 🛠️ Tech Stack & Algorithms

- **Framework:** Flutter (Dart)
- **Maps & Location:** Leaflet / Mapbox / OpenStreetMap & Geolocator APIs
- **Algorithms:** 
  - *Stay Point Detection* (Distance & Time threshold filtering)
  - *DBSCAN / K-Means Clustering* for point density grouping

---

## 🚀 Quick Setup & Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/IgorBelioglo/step_tracker.git](https://github.com/IgorBelioglo/step_tracker.git)
   cd step_tracker
Install Flutter dependencies:

Bash
flutter pub get
Run on an emulator or physical device:

Bash
flutter run
