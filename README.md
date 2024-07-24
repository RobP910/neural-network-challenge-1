# neural-network-challenge-1
My attempt at neural-networks. We will see were this goes!

## Starting with Colab & the .ipynb Starter file.

Using help from ChatGPT, I was able to create a neural-network and successfully test it to see if it can identify students that would successfully repay their loans.

# Discuss creating a recommendation system for student loans
Briefly answer the following questions in the space provided:

### Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.
To build a recommendation system for student loan options, I would collect the following data:

Student Demographics: Age, Gender, Nationality, Educational level (e.g., undergraduate, graduate), Field of study

Relevance: Demographic data helps in understanding the background of the student, which can influence loan options and terms. For instance, some loan providers may offer specialized loans for certain demographics.
Academic Information: Current GPA or academic performance, University/college name, Enrollment status (full-time/part-time)

Relevance: Academic performance and institution can affect eligibility for certain loans and interest rates. For example, students with higher GPAs might have access to better loan terms.
Financial Information: Annual family income, Personal income (if applicable), Financial aid already received (scholarships, grants, etc.), Credit score (if applicable)

Relevance: Financial data is crucial in assessing the ability to repay loans and determining the most suitable loan options in terms of interest rates and repayment schedules.
Loan Preferences: Desired loan amount, Preferred repayment period, Willingness to consider income-driven repayment plans, Preference for fixed vs. variable interest rates

Relevance: Understanding preferences helps tailor recommendations to individual needs and expectations.
Historical Loan Data (if available): Previous loan amounts and terms, Repayment history

Relevance: Historical data can provide insights into the student's borrowing habits and reliability, allowing for more personalized and appropriate loan recommendations.

### Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.
The model would primarily use content-based filtering.

Justification: Content-based filtering relies on the attributes of items (in this case, loan options) and the user profile to make recommendations.

The detailed demographic, academic, financial, and preference data collected allows the system to match student profiles with loan attributes (interest rates, repayment terms, eligibility criteria, etc.).

Each loan option can be described using features that align with the collected student data. For instance, specific loans might be better suited for students in certain income brackets or those with particular credit scores.

This method is appropriate because it uses the rich set of features collected to make personalized recommendations based on the student’s unique profile, rather than relying on the behavior of other users.

### Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.
Data Privacy and Security:

Concern: Handling sensitive personal and financial information about students poses significant privacy and security risks.

Explanation: Students’ financial data, credit scores, and personal identifiers must be protected to prevent data breaches and misuse. Ensuring compliance with data protection regulations (like GDPR or FERPA) is essential to build trust and avoid legal consequences.

Fairness and Bias:

Concern: Ensuring that the recommendation system does not inadvertently perpetuate or amplify biases.

Explanation: Historical biases in loan approval and financial systems can lead to discriminatory practices. For example, if certain demographics have been underserved historically, the model might continue to recommend less favorable loan options to these groups. It’s crucial to implement checks to identify and mitigate any biases to ensure fair and equitable loan recommendations.

  By addressing these challenges, the recommendation system can provide reliable, secure, and fair loan options, fostering trust and better financial support for students.
