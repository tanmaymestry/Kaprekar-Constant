# 🔢 Kaprekar's Constant - The Magic of 6174 and 495  

Ever heard of a number trick that **always leads to the same number**? 🤯  
Meet **Kaprekar’s Routine**, a simple math process that magically brings you to **6174** (for 4-digit numbers) or **495** (for 3-digit numbers), no matter where you start!  

This project is a **Jupyter Notebook** that lets you try Kaprekar’s Routine yourself! 🎉  


## 🧑‍🏫 Who Was D. R. Kaprekar?  
Dattaraya Ramchandra Kaprekar (1905–1986) was an Indian mathematician who loved exploring number patterns.  
One of his most famous discoveries is **Kaprekar's Constant**, a cool number that appears when you apply a specific math trick.  


## ✨ How Kaprekar’s Routine Works  

1️⃣ Pick a **4-digit** or **3-digit number** (not all digits the same).  
2️⃣ **Rearrange the digits in descending order** (largest first).  
3️⃣ **Rearrange the digits in ascending order** (smallest first).  
4️⃣ **Subtract the smaller number from the larger one**.  
5️⃣ Repeat until you reach **6174** (for 4-digit numbers) or **495** (for 3-digit numbers).  

This process **always leads to the same final number**! 🚀  


## 🔍 Example: 4-digit number (3435)  
Let’s see what happens when we try this on **3435**:

| Step | Largest Number | Smallest Number | Difference |
|------|---------------|----------------|------------|
| 1    | 5433          | 3345           | 2088       |
| 2    | 8820          | 0288           | 8532       |
| 3    | 8532          | 2358           | **6174** ✅ |

Once **6174 is reached, the process keeps repeating**!  


## 🔍 Example: 3-digit number (352)  
Now, let’s try a **3-digit** number, **352**:

| Step | Largest Number | Smallest Number | Difference |
|------|---------------|----------------|------------|
| 1    | 532          | 235            | 297        |
| 2    | 972          | 279            | 693        |
| 3    | 963          | 369            | 594        |
| 4    | 954          | 459            | **495** ✅ |

Once **495 is reached, it stays there forever**!  


## 🚨 When This Trick **Does NOT Work**  
❌ If all digits are the same (e.g., **1111, 2222, 555**), the difference is always **0**, so the process **stops immediately**.  
❌ If you enter a **2-digit** or **5-digit number**, Kaprekar’s Routine **does not apply**.  
 

## Clone this repository  

git clone: https://github.com/tanmaymestry/Kaprekar-Constant/blob/main/Kaprekar%20Constant.ipynb

## Thank you for checking out this project! 😊
If you found it interesting, give it a star ⭐ on GitHub!
Happy coding! 🚀

