# 📊 ProZorro Procurement Analysis

---

## 🏢 About the Project

This project is based on an analysis of data from **ProZorro**, Ukraine's public procurement system — an open platform operating on the principle "everyone sees everything."

Insights are provided along the following key directions:

- **Procurement dynamics**
- **Spending structure**
- **Regional differences**
- **Efficiency and savings**

The Tableau dashboard can be viewed [here.](https://public.tableau.com/app/profile/volodymyr.mykulanynets/viz/Prozorro_17716876370890/SpendingDashboard)

---

## 🗂 Data Structure

The analysis is based on the `procurements` dataset, which contains:

- **291,468 records (lots)**
- information on:
  - lot value
  - procurement categories
  - regions
  - bidding participants

<p align="center">
  <img width="175" height="278" src="https://github.com/user-attachments/assets/fb201f8f-9a0a-449f-a914-e7dd56e97b75" />
</p>

---

## 📌 Overview

After gradual growth in activity during 2022–2024, the public procurement system shows a sharp decline in key indicators in 2025. Total spending fell by **24%**, and the number of lots dropped by **8.5%**, signaling a shift in market dynamics after a period of recovery.

At the same time, the savings rate remains stable: regardless of changes in spending volume, the share of savings is practically unchanged from previous years.

This indicates that procurement efficiency is shaped not by the scale of spending, but by more persistent factors that hold steady even during downturns.

<p align="center">
  <img width="1342" height="347" src="https://github.com/user-attachments/assets/1bbe137e-f68d-4579-87d5-2059eac98011" />
</p>

---

## 🔍 Deep Dive

### 📊 Procurement Dynamics

After steady growth in 2022–2024, 2025 sees a sharp decline:

- spending: **−24%**
- number of lots: **−8.5%**

This points to a shift in market conditions or budget policy following the recovery period.

---

### 🏗 Spending Structure

The market shows a high concentration in a few categories.

Top 3 categories:

- **Construction work**
- **Petroleum products, fuel, electricity and other energy sources**
- **Supporting and auxiliary transport services**

Together they account for **72% of total spending**, of which:

- **55% comes from construction work**

This means these categories largely determine the overall market dynamics.

<p align="center">
  <img width="637" height="393" src="https://github.com/user-attachments/assets/8aa8924b-0976-4469-8a5f-81bc6182470e" />
</p>

---

## 🗺 Regional Differences

Spending distribution is uneven:

- **Kyiv — ~31% of total spending**

This indicates a high concentration of:

- large projects
- budgets
- procurement activity

<p align="center">
  <img width="653" height="424" src="https://github.com/user-attachments/assets/4c55f8b3-045b-48ca-88a0-a0871d256d4b" />
</p>

---

### 💰 Efficiency and Savings

The system shows a stable level of competition and predictable auction efficiency:

- **median savings: 2.3%**
- **272K participants**
- **3.1 participants per lot (on average)**

This points to established market mechanisms that ensure savings regardless of overall procurement volume.

<p align="center">
  <img width="1332" height="338" src="https://github.com/user-attachments/assets/ccacb122-34ee-474c-862c-ac7c1802e930" />
</p>

---

### ⚔️ Impact of Competition

Competition is a key factor with a direct effect on the level of savings.

With no competition, savings are practically nonexistent (~0.2%). As the number of participants increases, savings grow:

- **2 participants → ~1.1% savings**
- **3+ participants → sharp increase in savings**

At the same time, most of the market still falls in the low-competition zone — most often a lot has only 2 participants.

Competition is shaped by three main factors:

- lot value
- procurement category
- region

In particular, value shows a direct relationship:

- **up to 4 million** → ~60% of lots have ≤2 participants
- **over 4 million** → ~50% of lots have >2 participants

This indicates that more expensive procurements more often attract more competitors and potentially generate greater savings.

<p align="center">
  <img width="429" height="430" src="https://github.com/user-attachments/assets/a3b50dec-5106-46e6-a636-02f21fefdb0a" />
  <img width="442" height="430" src="https://github.com/user-attachments/assets/1ac6893e-bfa3-46a4-a1da-6997aa7b066a" />
</p>

---

### 🧩 Impact of Categories
The level of savings differs significantly across categories, reflecting different market structures and levels of competitive intensity.

The highest efficiency is shown by the category:

- **Petroleum products, fuel and energy resources — ~11.6%**

This is more than 3 times the average level and is explained by:

- high competition
- product standardization

Categories with moderate savings:

- construction materials and related goods — ~3.4%
- transport services — ~3.2%
- construction work — ~3.0%

At the same time, the largest category by volume (**construction work**) shows relatively low savings, which may result from:

- the complexity and uniqueness of projects
- limited competition

The lowest efficiency is observed in:

- medical goods — ~0.8%
- transport equipment — ~0.6%

These categories are characterized by narrow specialization and a smaller number of suppliers.

📌 **Key takeaway:**
savings depend directly on the level of competition and the standardization of the procurement item.

---

### 📍 Regional Efficiency

Procurement efficiency varies significantly across regions and doesn't always correlate with spending volume.

The highest savings are shown by:

- **Volyn Oblast — 7.3%**
- **Zhytomyr Oblast — 5.9%**
- **Ternopil Oblast — 5%**

At the same time, these regions:

- are not spending leaders
- have a similar level of competition (~2.7 participants per lot)
- yet show higher efficiency

For comparison:

- **Kyiv — ~1.7% savings**

A deeper analysis reveals significant variability even within a single category.

For example, in the *construction work* category (1–2 million):

- Zhytomyr Oblast — **11.7% savings (54 lots)**
- Kyiv Oblast — **0.9% savings (833 lots)**

A possible explanation is scale:

- in Kyiv Oblast, ~41% of lots have only one participant
- a large number of procurements can reduce competition

However, this rule isn't universal:

- in Chernihiv Oblast (45 lots), savings are only **1.1%**

📌 **Key takeaway:**
regional efficiency is determined not only by volume, but also by the quality of competition and how procurements are organized.

<p align="center">
  <img width="1519" height="442" src="https://github.com/user-attachments/assets/92ac4153-6268-45d1-8cef-9e671c7c6302" />
  <img width="1503" height="430" src="https://github.com/user-attachments/assets/86c41597-5a9b-492a-a9f7-d25a19eb0ffa" />
</p>


---

## 🚀 Recommendations

Based on the analysis, the following steps can be proposed to improve procurement efficiency:

- Savings increase significantly at 3+ participants per lot → implement practices that raise competition specifically to this threshold.
- The largest category (construction work) has relatively low savings (~3.0%) → optimize lot structure and increase requirement transparency.
- Regions with smaller procurement volumes show higher efficiency than large markets → study and scale their practices nationally.

---

## ⚠️ Assumptions and Caveats

Several assumptions were made during the analysis to correctly interpret the data:

- Some lots with missing or incorrect values (e.g., region or category) were excluded from the analysis to avoid skewing results.
- Savings are calculated as a relative measure between the expected and final lot value, which doesn't account for contract execution quality or long-term efficiency.
- Procurement categories are aggregated, which may hide differences within individual subcategories.
- Data for 2025 may be incomplete or still being updated, which could potentially affect the accuracy of the conclusions.
