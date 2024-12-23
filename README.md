# GPT-Enhanced Leave Management Chatbot  

## Background  
You are tasked with developing a leave management chatbot named **Dexter**. You have been provided with a dataset of user queries and corresponding responses. Your challenge is to create an effective chatbot using both traditional NLP techniques and GPT integration.  

---

## Tasks  

### Task 1: Data Analysis (20%)  
1. **Load and preprocess** the provided dataset.  
2. **Identify and list** the top 5 most common query categories.  
3. For each of these top categories, provide **3 example user queries**.  
4. **Calculate and report** the distribution of queries across all categories.  

### Task 2: Traditional NLP Approach (30%)  
1. Implement a **simple classifier** to categorize user queries into the identified categories. Techniques may include keyword matching, TF-IDF, or a basic machine learning classifier.  
2. Create a **function** that takes a user query as input and returns an appropriate response based on the classified category.  
3. **Evaluate** the performance of your classifier on a held-out portion of the dataset.  

### Task 3: GPT Integration (30%)  
1. Design a **prompt engineering strategy** to effectively use GPT for the leave management chatbot.  
2. Implement a **function** that sends queries to a GPT model and processes the responses.  
3. Develop a **method** to verify and correct GPT responses to ensure accuracy of leave-related information.  

### Task 4: Evaluation (20%)  
1. Evaluate your system using a set of **5 diverse test queries**. Report on its performance, highlighting strengths and areas for improvement for both approaches. Include the evaluated test cases in the report.  
2. **Discuss the trade-offs** between the traditional NLP approach and the GPT-enhanced approach in the context of a leave management chatbot.  

---

## Submission Guidelines  
- Submit your work as a **Jupyter notebook (.ipynb)** or a set of Python scripts with accompanying documentation.  
- Include all necessary **code, visualizations (optional), and explanations**.  
- Provide a brief (max. 500 words) **discussion** of your approach, challenges faced, and potential future improvements.  
- If you don't have access to a GPT API, clearly indicate where you've used mock functions and explain how they would work with a real API.  

---

## Evaluation Criteria  
- **Quality** of data analysis and insights derived.  
- **Effectiveness** of the traditional NLP approach.  
- **Creativity** and appropriateness of GPT integration.  
- Clear communication of **ideas, results, and trade-offs**.  
- **Code quality**, including organization and comments.  
