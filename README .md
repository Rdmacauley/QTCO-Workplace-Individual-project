# Workplace Individual Project-ExploreAI
# Insurance Fruad in Africa

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)

## 1. Project Overview <a class="anchor" id="project-description"></a>
Insurance Fruad in Africa

Despite being home to approximately 17% of the global population, Africa's insurance industry remains underrepresented in the global market. In 2017, the continent's total insurance premiums were estimated at $45 billion, a modest figure when compared to other regions. More strikingly, Africa accounted for just over 1% of global insured catastrophe losses, underscoring a significant gap in coverage and resilience.

This disparity highlights several structural challenges: low insurance penetration, limited consumer awareness, regulatory fragmentation, and economic constraints. Many African countries still rely heavily on informal risk-sharing mechanisms, and access to formal insurance products is often limited to urban or wealthier populations

This project seeks to identify critical challenges in the African insurance industry, particularly fruad and the impact it has on the industry. Fraudulent claims increase costs and reduce trust, making fraud detection a high-impact area for data-driven solutions. Building a reliable model to detect fraudulent insurance claims by using customer, vehicle, and incident-related data will assist in addressing some of these challenge unique to the African insurance industry

## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset contains insurance claims details in Africa and indicates if fraudulent or not.

**Key Dataset Features:**
- policy_bind_date: Starting date of the insurance policy.
- policy_csl: Combined Single Limits - This is the maximum value of the insurer will pay out per incident.
- policy_annual_premium: The total dollar amount for the yearly premium.
- umbrella_limit: Extra insurance that provides protection beyond existing limits and coverages of other policies.
- auto_make: Vehicle brand.
- auto_model: Vehicle model.
- insured_education_level: Highest qualification of the insurer.
- policy_deductable: Excess payment before a payout or service is conducted.
- insured_occupation: The profession in which the insurer works.
- Fraud_reported: Y - a fraudelent or false claim, N - a legit and valid claim.



## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.


```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```
