# Design for Usability: iOS App for ICSR 2025 & K-Means Recommendation System

Bachelor's Thesis Project developed by **Simone Palladino**.  
**Advisor:** Prof.ssa Mariacarla Staffa | **University:** Università degli Studi di Napoli Parthenope

---

## 📌 Overview
This project presents an iOS mobile application developed for the **ICSR 2025** conference event, designed around Human-Computer Interaction (HCI) and User-Centered Design (UCD) principles. The system combines mobile UX/UI optimization—evaluated against Jakob Nielsen's 10 Usability Heuristics—with an integrated Machine Learning Recommendation System powered by K-Means clustering.

---

## 🎯 Key Objectives
* **Usability-Driven Design:** Maximize effectiveness, efficiency, and user satisfaction across mobile interactions.
* **Conference Ecosystem:** Streamline navigation, schedule exploration, interactive maps, and social engagement for ICSR 2025 attendees.
* **Smart Recommendation Engine:** Implement an unsupervised machine learning model to group and suggest relevant points of interest (POIs) and venues.

---

## 🤖 K-Means Recommendation System
The application incorporates a K-Means clustering algorithm to partition points of interest based on multi-dimensional attributes:

* **Algorithm Workflow:**
  1. Cluster count ($K$) selection
  2. Centroid initialization
  3. Point-to-cluster assignment
  4. Iterative centroid updating until convergence
* **Dataset Features:** Name, Description, Category, Tags, Neighborhood, Latitude, Longitude.

---

## 🧪 User Testing & Usability Evaluation
System usability was validated through real user testing across key interactive tasks:
* App Navigation & Event Exploration
* Venue & Location Search
* Interactive Map Operations
* Social Interactions & Questionnaire Completion

---

## 🚀 Future Roadmap
* **Advanced Hybrid Recommendation:** Integration of collaborative filtering alongside content-based clustering.
* **Authentication:** User profile creation and persistent preference synchronization.
* **Push Notifications:** Real-time conference alerts and schedule updates.

---

## 🛠️ Tech Stack & Methods
* **Mobile Development:** iOS, Swift / SwiftUI, Apple Maps Framework
* **Machine Learning:** K-Means Clustering, Unsupervised Learning
* **UX/UI Design:** User Experience (UX), User Interface (UI), Jakob Nielsen's 10 Usability Heuristics
