# **Storage Estimation**

This section estimates the storage requirements for the news feed system, considering the different types of posts and their sizes.


![15.png](img/15.png)

---

## **Data to Store**

* **Posts**  
  * This includes text, images, and videos shared by users.

---

## **Assumptions**

![16.png](img/16.png)

* **Average Post Size**

  * Text Post: 100 KB  
  * Image Post: 0.5 MB  
  * Video Post: 20 MB  


* **Post Type Percentage**

  * Text Posts: 20%  
  * Image Posts: 60%  
  * Video Posts: 20%

---

## **Storage Calculation**

![17.png](img/17.png)

* **Daily Storage**

  * Text: 0.2 × 50 million posts × 100 KB \= 1 TB  
  * Image: 0.6 × 50 million posts × 0.5 MB \= 15 TB  
  * Video: 0.2 × 50 million posts × 20 MB \= 200 TB  
  * **Total Daily Storage**: 1 TB \+ 15 TB \+ 200 TB \= 216 TB  


* **Storage for 10 Years**

  * **Total Storage**: 216 TB/day × 365 days/year × 10 years \= 750 PB

---
### 🔙 [Back](../README.md)