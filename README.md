# Emotion-Aware Content Recommendation System

## Overview
This project demonstrates an emotion-aware content recommendation system that adapts content suggestions based on a user's current mental state and cognitive time availability. The system is designed to provide relevant and responsible personalization **without collecting historical user data or sensitive information**.

## Project Track
Responsible AI / Recommender Systems

## Problem Statement
Users often want content that matches their current mood and time availability, but traditional recommender systems rely heavily on historical data. This project aims to create a **lightweight, privacy-preserving recommendation system** that uses **synthetic data** and **real-time emotion detection** to provide context-aware content.

## Real-World Relevance & Motivation
- Users may feel stressed, sad, neutral, or happy and want content that suits their emotional state.  
- For example:
  - Stressed users may prefer short, uplifting content.
  - Happy users may want longer, engaging content.  
- Modeling implicit user context improves relevance, reduces cognitive overload, and provides ethical personalization without long-term tracking.

## Key Features
- **Emotion Detection:** Detects user mood (happy, neutral, sad, stressed) from text input.  
- **Adaptive Content Recommendation:** Suggests content aligned with detected emotion and desired duration.  
- **Cognitive Load Awareness:** Adjusts content length based on inferred attention availability or explicit user cues.  
- **Engagement Modeling:** Small randomness to emulate session engagement.  
- **Ethical Design:** Prioritizes user well-being, no sensitive data, no long-term tracking.  
- **Synthetic Dataset:** Balanced dataset of >500 items covering emotions and durations.

## Repository Structure
- `Emotion_Aware_Content_Recommendation_System.ipynb` — Main notebook (primary evaluation artifact)  
- `README.md` — Project overview and instructions

## How to Run
1. Clone or download the repository.  
2. Open `Emotion_Aware_Content_Recommendation_System.ipynb` in Jupyter Notebook.  
3. Run all cells sequentially from top to bottom.  
4. For demo, type your mood/context when prompted to see emotion-aware content recommendations.

## Ethical Considerations & Responsible AI
- No personal or sensitive user data is used.  
- No long-term user tracking is implemented.  
- Recommendations are transparent and explainable with explicit reasoning.  
- Dataset is balanced across emotional categories and content durations to reduce bias.  
- The system prioritizes user well-being over engagement maximization.

## Conclusion
This project demonstrates how lightweight AI techniques can provide **emotionally intelligent content recommendations** without historical data. Users receive relevant content tailored to their current emotional state and cognitive capacity, all while maintaining privacy and ethical considerations.

## Future Scope
- Transformer-based emotion classification for better context understanding.  
- Integration of real user feedback for adaptive learning.  
- Multi-session engagement modeling with privacy-preserving approaches.  
- Domain-specific personalization for learning, wellness, and entertainment platforms.
