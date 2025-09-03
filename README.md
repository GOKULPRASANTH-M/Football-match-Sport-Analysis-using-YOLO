# ⚽ Football Match Sport Analysis  

This project focuses on **automatic football (soccer) match analysis** using **Computer Vision and Deep Learning**.  
The system can detect players and the ball, assign ball possession, classify teams based on jersey colors, and transform the match view into a tactical top-view for better analysis.  

---

## 🔹 Features
- **Player & Ball Detection** – YOLO for real-time detection  
- **Ball Possession Assignment** – nearest player to the ball is automatically identified  
- **Team Classification** – K-Means clustering to group players by jersey color  
- **Perspective Transformation** – convert camera view into a top-down field map  
- **Tracking & Distance Analysis** – measure player movements and ball distances  

---

## 🔹 Tech Stack
- **Deep Learning**: YOLO (Ultralytics)  
- **Computer Vision**: OpenCV  
- **Dataset Handling**: Roboflow  
- **Machine Learning**: Scikit-learn (K-Means clustering)  
- **Python Libraries**: NumPy, Pandas, Supervision  

---

## 🔹 Installation
Clone the repository:
```bash
git clone https://github.com/your-username/football-match-analysis.git
cd football-match-analysis
