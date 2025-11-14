# AI Powered Fraud Detection
## Team: IBM-Codecrafter(Solo)
## Zuhra Totakhail


### Problem Statement and Solution
### Problem
Financial institutions face growing challenges detecting fraud in real time as transaction volumes increase and fraud patterns evolve. Traditional rule-based systems produce too many false positives, wasting investigation time and reducing customer trust. 
### Solution: 
The IBM-codecrafters team created an AI-Powered Fraud Detection System that uses supervised machine learning to classify transactions as “fraud” or “legitimate.” The model leverages XGBoost with SMOTE for handling class imbalance, achieving high recall and precision on real-world-like data. The system is trained and evaluated using IBM watsonx.ai, ensuring reproducibility and efficient hyperparameter tuning. Model governance and transparency are managed through watsonx.governance, where model metrics, lineage, and fairness attributes are logged and monitored. The final deployment uses a FastAPI web service, exposing an endpoint /score that accepts JSON transaction data and returns fraud probabilities. Input validation is enforced through Pydantic schemas. The project delivers a complete AI lifecycle: data preparation → training → governance → deployment, proving how watsonx can make fraud prevention scalable and explainable. 
### Target Users: 
Banking risk analysts, fraud detection teams, and AI governance officers. Impact: Reduces fraud losses, enhances compliance visibility, and demonstrates how IBM watsonx can bring trust and transparency into AI-driven banking operations. 
### Creativity: 
Unlike static rule engines, this system adapts via data-driven learning and includes human-in-the-loop threshold tuning, enabling customizable recall targets based on institutional risk tolerance.

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src="https://www.loom.com/embed/fe7be91fe2374747ad579b9243d6327d" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>


<img width="2240" height="1260" alt="Screenshot 2025-11-13 at 1 06 12 PM" src="https://github.com/user-attachments/assets/779e33ce-9866-4a2a-b218-c25f351d5d91" />
