# Airline Customer Value Analysis with K-means Clustering

## **Introduction**
This project uses K-means clustering to analyze airline customer data with the goal of improving customer relationship management (CRM) by identifying and understanding different customer segments. The analysis includes data preprocessing, feature selection, clustering, and evaluation, focusing on key metrics such as total mileage, number of flights, average fare discount, and accumulated loyalty points. The results reveal four distinct customer clusters: high-value frequent travelers, moderate discount frequent travelers, high discount infrequent travelers, and low-value infrequent travelers. These insights enable targeted marketing strategies and personalized services that increase customer satisfaction and loyalty. By integrating these insights into the airline's CRM system, airlines can dynamically tailor their marketing efforts and service offerings, resulting in improved customer satisfaction, loyalty, and profitability. This data-driven approach underscores the potential of machine learning to optimize CRM strategies in the airline industry.

### **Objectives**
1.	Segment airline customers and analyze the characteristics of different customer categories.
2.	Compare customer values across segments.
3.	Provide personalized services to each customer category based on their value.
4.	Formulate appropriate marketing strategies for each customer segment.

## **Dataset Description**
The dataset consists of various details about 62,988 customers of airline 'X'. The details are:  
•	member_no: Member ID  
•	ffp_date: Frequent Flyer Program Join Date  
•	first_flight_date: First Flight Date  
•	gender: Gender  
•	ffp_tier: Tier of the Frequent Flyer Program  
•	work_city: City of origin  
•	work_province: Province of origin  
•	work_country: Country of origin  
•	age: Customer's age  
•	load_time: Date the data was taken  
•	flight_count: Number of flights taken by the customer  
•	bp_sum: Travel itinerary  
•	sum_yr_1: Fare revenue  
•	sum_yr_2: Votes prices  
•	seg_km_sum: Total distance (km) flown  
•	last_flight_date: Date of the last flight  
•	last_to_end: Time span from the last flight to the latest booking  
•	avg_interval: Average time interval  
•	max_interval: Maximum time interval  
•	exchange_count: Number of exchanges  
•	avg_discount: Average discount received by the customer  
•	points_sum: Total points earned by the customer  
•	point_notflight: Points not used by the member  

## **Methodology**
The methodology section outlines the detailed steps taken to perform the K-means clustering analysis on the airline customer data. This process involves several stages: data collection, data preprocessing, feature selection, applying K-means clustering, and evaluating the clustering results. Each stage is critical to ensure accurate and meaningful customer segmentation. 

## **Data Collection**
The first step in the analysis is data collection. The dataset used in this analysis contains various attributes of airline customers, such as membership numbers, flight dates, gender, tier status, and travel details, etc. 


## **Conclusion**
This study demonstrates the effectiveness of using K-means clustering to analyze airline customer data, enabling valuable insights into customer segmentation and tailored marketing strategies. By examining factors like flight kilometers, flight frequency, average discounts, and loyalty points, four distinct customer groups were identified: high-value frequent travelers, frequent travelers with moderate discounts, infrequent travelers with high discounts, and low-value infrequent travelers. Each segment offers unique opportunities for targeted customer relationship management (CRM). High-value frequent travelers require personalized services and exclusive benefits to maintain their loyalty, while frequent travelers with moderate discounts can be incentivized with upgrades and promotions. Infrequent travelers with high discounts can be encouraged to travel more through loyalty campaigns, and low-value infrequent travelers represent potential growth through introductory offers and personalized marketing.

Integrating these insights into CRM systems allows airlines to dynamically adjust strategies to address evolving customer behaviors and market conditions, ensuring relevant and effective marketing efforts. This study underscores the transformative potential of data-driven decision-making, with K-means clustering providing powerful tools for understanding and enhancing customer relationships. Future research could refine the model by incorporating additional data sources like social media activity and customer feedback, along with predictive analytics to anticipate future customer needs. These advancements would further optimize CRM strategies, highlighting the critical role of advanced analytics in driving customer satisfaction, loyalty, and profitability within the airline industry.

## **Usage Instructions**
1. **Environment Setup**:
   - Install required libraries: `scikit-learn`, `pandas`, `matplotlib`, etc.
   - Ensure Python 3.x is installed.
2. **Execution**:
   - Run the preprocessing script to clean and prepare the data.
   - Execute the K-means clustering model script to perform segmentation.
   - Visualize results using the provided plotting scripts.

## 
 <a href="https://github.com/thenomaniqbal/K-MeansClustering-AirlineCustomerValueAnalysis/">
    <img src="Images/image1.PNG" width="100%" height="100%"> 
    <img src="Images/image2.PNG" width="100%" height="100%"> 
    <img src="Images/image3.PNG" width="100%" height="100%"> 
  </a>

---

## P.S.  
If you need the rest of the documentation or the complete paper, please feel free to email me at [thenomaniqbal@gmail.com](mailto:thenomaniqbal@gmail.com).  

This project is part of my GitHub directory. Contributions and feedback are always welcome!

---
