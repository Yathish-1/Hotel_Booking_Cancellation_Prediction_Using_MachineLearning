## **🏨 Hotel Booking Cancellation Prediction**  

### **📌 Project Overview**  
This project aims to predict whether a **hotel booking will be canceled**, helping hotels optimize **revenue management, room allocation, and customer experience**. The dataset includes **customer details, booking information, and stay details**, with key features like **lead time, deposit type, and special requests**.  

By leveraging **Machine Learning**, we analyze the most significant factors affecting cancellations and build a predictive model to help hotels take proactive measures.  

---

## **🧩 Problem Statement**  
Hotel cancellations lead to:  
❌ **Revenue loss** due to last-minute cancellations.  
❌ **Inefficient room allocation**, causing overbooking or empty rooms.  
❌ **Poor customer experience** due to last-minute changes.  

This project **analyzes key booking features** and **trains ML models** to predict cancellations and provide actionable insights.  

---

## **📊 Business Insights & Strategies**  

📌 **Understanding Booking Cancellations**  
- High cancellation rates cause revenue losses and operational inefficiencies.  
- Predicting cancellations in advance helps hotels **take proactive actions**.  

📌 **Key Factors Affecting Cancellations**  
- **Lead Time**: Longer lead time → Higher cancellation probability.  
- **Deposit Type**: No upfront payment → Higher cancellation risk.  
- **Special Requests**: More requests → Higher uncertainty in booking.  
- **Previous Cancellations**: Customers with past cancellations are more likely to cancel again.  

📌 **Data-Driven Strategies to Reduce Cancellations**  
✔️ **Flexible Pricing**: Offer discounts for non-refundable bookings.  
✔️ **Optimized Deposit Policies**: Require partial deposits for high-risk bookings.  
✔️ **Improved Customer Communication**: Send reminders & exclusive offers to reduce cancellations.  

---

## **📂 Dataset Information**  
- **Source**: Kaggle (Open-source dataset)( https://www.kaggle.com/code/farzadnekouei/hotel-booking-cancellation-prediction )
- **Features**: Numerical & categorical data related to hotel bookings.  
- **Target Variable**: `is_canceled` (1 = Canceled, 0 = Not Canceled).  

### **Key Features in the Dataset**  
📌 `lead_time`: Days between booking and arrival.  
📌 `deposit_type`: Type of deposit made (No deposit, Non-refundable, Refundable).  
📌 `special_requests`: Number of special requests made by the guest.  
📌 `previous_cancellations`: Number of previous cancellations by the guest.  

---

## **🔍 Approach Used**  

### **1️⃣ Data Exploration & Preprocessing**  
✅ Investigated dataset structure & summary statistics.  
✅ Handled **missing values** and **outliers**.  
✅ **Feature engineering** and **encoding categorical variables**.  

### **2️⃣ Machine Learning Model Building**  
🚀 Implemented and tuned **classification models**:  
- Decision Trees 🌲  
- Random Forest 🌳  
- XGBoost ⚡  

🎯 **Goal**: Achieve high **F1-score** for class 1 (cancellations), ensuring accurate prediction.  

### **3️⃣ Model Evaluation & Feature Importance**  
✅ Used **accuracy, precision, recall, F1-score, and AUC** for evaluation.  
✅ Analyzed feature importance to determine key cancellation drivers.  

---

## **📈 Results & Conclusions**  
✔️ **Accurate predictions** using ML models.  
✔️ **Lead time, deposit type, and past cancellations** are the most important factors.  
✔️ **Hotels can reduce cancellations** by optimizing pricing, deposits, and customer engagement.  
✔️ **Better inventory management** helps reduce last-minute vacancies and improves revenue.  

---



## **🚀 How to Run the Project**  
1️⃣ Download the **Jupyter Notebook (`.ipynb`)** file.  
2️⃣ Install required dependencies:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

3️⃣ Open the notebook and run all cells.  
4️⃣ Analyze the **feature importance and model performance**.  

---

## **👤 Author**  
- **Yathish G S**  (https://github.com/Yathish-1/Hotel_Booking_Cancellation_Prediction_Using_MachineLearning)
---

## **⚖️ License**  
This project is licensed under the **MIT License**.  

