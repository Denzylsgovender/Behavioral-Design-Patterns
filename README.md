# 🚆 Smart Transportation Fare System (Strategy Pattern)  

Welcome to the **Smart Transportation Fare System!** 🎉  
This hands-on activity will help you understand and apply the **Strategy Pattern** in **C#** by building a **dynamic fare calculation system** for different transportation types.  

---

## 📌 **Project Overview**  
Your city is launching a **smart public transport system** where users can travel using:  
✅ **Buses** (Fixed fare)  
✅ **Taxis** (Distance-based fare)  
✅ **Trains** (Peak hour pricing applied)  

Each mode of transport has a **different fare calculation strategy**, and we will use the **Strategy Pattern** to switch between them dynamically.  

---

## 🎯 **Learning Outcomes**  
By completing this challenge, you will:  
✔ Understand and implement the **Strategy Pattern** in C#.  
✔ Learn how to **decouple business logic** and make it **scalable**.  
✔ Gain hands-on experience with **object-oriented programming**.  

---

## 🛠 **Step-by-Step Instructions**  

### **1️⃣ Step 1: Define the Strategy Interface (Fare Calculation)**
📌 **Your Task:**  
1. Create an **interface `IFareStrategy`** that defines a method for calculating fares.  

   ```csharp
   public interface IFareStrategy  
   {  
       decimal CalculateFare(decimal distance, bool isPeakHour);  
   }
