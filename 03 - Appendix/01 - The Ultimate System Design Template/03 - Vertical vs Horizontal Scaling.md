# **Vertical vs. Horizontal Scaling**

## **Introduction**

Welcome back, system design enthusiasts\! In our last session, we peeled back a layer and saw how the server fetches data from the data store. Today, we're tackling a new challenge: handling increasing user traffic on our website.

## **The Challenge of Scale**

As more users visit our website, both the server and the database can become overwhelmed. Imagine a busy restaurant during rush hour struggling to keep up with all the orders.

## **Vertical Scaling**

One natural solution is to make our server more powerful by increasing its CPU or RAM. This is called **vertical scaling**. However, this approach has limits. You can only make a single server so powerful.

## **Horizontal Scaling**

When one supercharged server isn't enough, we need more of them. This is called **horizontal scaling**. It's like opening more kitchens to serve more customers simultaneously.

## **Illustrative Example**

Think of vertical scaling as upgrading your car's engine for more power. Horizontal scaling is like adding more cars to the road to handle more traffic.

![03.png](img/03.png)

## **Benefits of Horizontal Scaling**

* **Increased Capacity:** Handle more user requests and traffic.  
* **Improved Fault Tolerance:** If one server fails, others can still handle the load.  
* **Easier Scalability:** Add or remove servers as needed to adjust to demand.

## **Fun Fact**

Did you know that Facebook has over 30,000 servers to handle its user load? That's enough to host an entire digital city of cat videos, memes, and status updates\!

---
## **Next Steps**

In the next session, we'll dive deeper into the techniques and strategies for implementing effective horizontal scaling. Stay tuned\!

---

[back](../README.md)