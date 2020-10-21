# ClaimCatcher: Automated Medical Insurance Fraud Detection
Insight Data Science Project

Introduction
Fraudulent insurance claims cost over 100 billion dollars in lost revenue globally. In the continent of Africa, fraud detection is largely manual, delaying claims processing and adding more costs to the insurance companies.ClaimCatcher automates the fraud detection process in medical insurance claims and conducts cost adjustment for claims that are legal and need adjustment. This was a consulting project for Curacel, a claims and fraud detection platform in Africa.

Methods Used
I used Curacel’s data base that includes over 60K instances of claims and over 330 thousand individual claims. It also includes 49 features such as the care that was provided by a hospital to a patient, quantity of that care, amount claimed by the hospital for that care, and pre-agreed amount between the hospital and and the provider. The data was labeled—either the claim was accepted if it was a legal claim and rejected if it was fraudulent, which meant I was tackling a supervised learning problem, which I divided into two parts—classification (to separate claims to accept and claims to reject), and regression to do the cost adjustment. For classification, I used the random forest classifier. For the cost adjustment, I used multiple linear regression, where the goal was to predict the amount adjusted for those claims where the approved amount was different than the claim amount.
