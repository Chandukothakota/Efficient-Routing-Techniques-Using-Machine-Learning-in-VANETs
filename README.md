# 🚘 Efficient Routing Techniques Using Machine Learning in VANETs

## 📖 Overview
This project focuses on designing and implementing a **machine learning-based routing algorithm** for **Vehicular Ad Hoc Networks (VANETs)**.  
The system predicts and selects optimal routing paths under high mobility conditions to improve overall **routing efficiency**, **data transmission performance**, and **network reliability**.

---

## 🧠 Problem Statement
Traditional routing protocols in VANETs such as **AODV**, **DSDV**, and **OLSR** suffer from:
- High packet loss  
- Low routing efficiency  
- Poor adaptability to real-time, high-mobility conditions  

To overcome these limitations, this project introduces a **Reinforcement Learning (Q-Learning)**-based intelligent routing approach that learns optimal paths dynamically.

---

## ⚙️ Features
- ✅ Q-Learning-based adaptive routing algorithm  
- ✅ Improves routing efficiency by up to **89%**  
- ✅ Learns from environment feedback (successful data delivery rewards)  
- ✅ Generates multiple performance graphs for analysis  
- ✅ Fully executable in **Google Colab** or any Python environment

| Metric             | Traditional Routing | ML-Based Routing             |
| ------------------ | ------------------- | ---------------------------- |
| Routing Efficiency | 50–60%              | **Up to 89%**                |
| Packet Loss        | High                | **Reduced**                  |
| Delay              | High                | **Lowered**                  |
| Adaptability       | Low                 | **Dynamic (Learning-Based)** |


---

## 🗂️ Project Structure
- vanet_project/
│
├── configs/vanet.yaml # Configuration file (hyperparameters)
├── models/q_table.npy # Saved model
├── utils.py # Helper functions (mobility simulation, metrics)
├── train_rl.py # Reinforcement Learning training script
├── evaluate.py # Evaluation and performance testing
├── requirements.txt # Dependencies
└── README.md # Project documentation

