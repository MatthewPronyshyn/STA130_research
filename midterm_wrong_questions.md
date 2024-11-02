The following is a summary of each question where at least one chatbot provided an incorrect answer. For each question, we include the correct answer, the answers provided by the chatbots, and their justifications.

---

### Question 3: "Which of the following best defines inference?"

- Correct Answer: D: Quantifying uncertainty about a parameter
- ChatGPT\_4o\_mini's Answer: A (**Wrong**): Estimating a parameter using data
  - Reasoning: "Inference involves using data to estimate parameters and predict outcomes."
- NBLM's Answer: D (Correct): Quantifying uncertainty about a parameter
  - Reasoning: "Statistical inference uses a sample to estimate and make predictions about a population."
- ChatGPT\_4's Answer: D (Correct): Quantifying uncertainty about a parameter
  - Reasoning: "Inference involves quantifying uncertainty about a parameter using data."

### Question 4: "Which is better and why?"

- Correct Answer: D: A 95% confidence interval because it quantifies uncertainty
- ChatGPT\_4o\_mini's Answer: D (Correct): A 95% confidence interval because it quantifies uncertainty
  - Reasoning: "A 95% confidence interval provides a range of values that likely includes the true value."
- NBLM's Answer: A (**Wrong**): A hypothesis test because it allows you to make decisions about a null hypothesis
  - Reasoning: "A hypothesis test allows you to make a decision based on the available data."
- ChatGPT\_4's Answer: D (Correct): A 95% confidence interval because it quantifies uncertainty
  - Reasoning: "A 95% confidence interval is preferred as it provides more information about potential true values."

### Question 6: "Which of the following gives the calculation for sample variance?"

- Correct Answer: C: ((x - x.mean()) \* (x - x.mean()) / (len(x) - 1)).sum()
- ChatGPT\_4o\_mini's Answer: D (**Wrong**): None of the above
  - Reasoning: "The correct calculation for the sample variance involves summing the squared deviations."
- NBLM's Answer: C (Correct): ((x - x.mean()) \* (x - x.mean()) / (len(x) - 1)).sum()
  - Reasoning: "This formula correctly implements the sample variance with (n-1) correction."
- ChatGPT\_4's Answer: D (**Wrong**): None of the options correctly calculate the sample variance
  - Reasoning: "None of the options correctly calculate the sample variance."

### Question 7: "Which of the following describes the calculation for the sample variance?"

- Correct Answer: D: The sample variance, denoted as s^2, is calculated with n-1 in the denominator
- ChatGPT\_4o\_mini's Answer: D (Correct): The sample variance, denoted as s^2, is calculated with n-1 in the denominator
  - Reasoning: "This option accurately describes the calculation of variance."
- NBLM's Answer: D (Correct): The sample variance, denoted as s^2, is calculated with n-1 in the denominator
  - Reasoning: "The sample variance, denoted as s^2, is calculated with n-1 in the denominator."
- ChatGPT\_4's Answer: B (**Wrong**): The sample variance is calculated as the sum of squared deviations divided by n
  - Reasoning: "The sample variance is calculated as the sum of squared deviations divided by n."

### Question 11: "Given the following code snippets, which one is correct?"

- Correct Answer: C: Code snippet 1 uses the range(5) function which iterates correctly
- ChatGPT\_4o\_mini's Answer: A (**Wrong**): This statement accurately describes the functionality of the code
  - Reasoning: "This statement accurately describes the functionality of the code."
- NBLM's Answer: C (Correct): Code snippet 1 uses the range(5) function which iterates correctly
  - Reasoning: "Code snippet 1 uses the range(5) function which iterates correctly."
- ChatGPT\_4's Answer: C (Correct): Code snippet 1 iterates from 0 to 4, Code snippet 2 iterates using list comprehension
  - Reasoning: "Code snippet 1 iterates from 0 to 4, Code snippet 2 iterates using list comprehension."

### Question 13: "How does a chatbot generate the text that’s given to the user?"

- Correct Answer: D: The text is generated probabilistically based on training data using transformers
- ChatGPT\_4o\_mini's Answer: B (**Wrong**): Drawing from patterns found in large datasets
  - Reasoning: "This method reflects how modern language models operate, drawing from patterns found in large datasets."
- NBLM's Answer: B (**Wrong**): Predicting the next word in a sequence
  - Reasoning: "Chatbots, or Large Language Models (LLMs), generate text by predicting the next word in a sequence, based on training data."
- ChatGPT\_4's Answer: B (**Wrong**): Selecting the most probable next token
  - Reasoning: "Chatbots typically generate text by selecting the most probable next token, using data patterns learned during training."

### Question 22: "What is inference for a sample given by x?"

- Correct Answer: C: Using a sample to draw conclusions about a population
- ChatGPT\_4o\_mini's Answer: A (**Wrong**): Estimating a parameter using data
  - Reasoning: "This option accurately describes inference for a sample given by the data."
- NBLM's Answer: C (Correct): Using a sample to draw conclusions about a population
  - Reasoning: "Inference uses a sample to draw conclusions about the larger population."
- ChatGPT\_4's Answer: A (**Wrong**): Using statistics from a sample
  - Reasoning: "Inference typically involves using statistics from a sample."

### Question 34: "Why do we use replace=False for bootstrapping?"

- Correct Answer: D: To ensure that each bootstrap sample is unique
- ChatGPT\_4o\_mini's Answer: C (**Wrong**): To ensure each observation is only sampled once
  - Reasoning: "Using replace=False in bootstrapping allows us to ensure each observation is only sampled once."
- NBLM's Answer: D (Correct): To ensure that each bootstrap sample is unique
  - Reasoning: "Using replace=False would mean that every bootstrap sample is unique, which is not the typical approach for bootstrapping."
- ChatGPT\_4's Answer: D (Correct): To ensure that each bootstrap sample is unique
  - Reasoning: "We use replace=True for bootstrapping to allow repeated sampling from the dataset."

### Question 36: "Which of the following can be used to do boolean indexing?"

- Correct Answer: B: Logical conditionals on a DataFrame
- ChatGPT\_4o\_mini's Answer: B (Correct): Logical conditionals on a DataFrame
  - Reasoning: "Boolean selection is done using logical conditionals on a DataFrame."
- NBLM's Answer: D (**Wrong**): Logical conditionals that match the criteria
  - Reasoning: "Boolean selection is done using logical conditionals that match the criteria."
- ChatGPT\_4's Answer: D (**Wrong**): Logical conditionals to select rows
  - Reasoning: "Boolean selection with logical conditionals can be used to select rows based on specific conditions."

### Question 46: "The area under the curve function estimates what?"

- Correct Answer: A: The area under the histogram which represents the density must equal 1
- ChatGPT\_4o\_mini's Answer: B (**Wrong**): The bins of the histogram must be width 1 to ensure the total area equals 1
  - Reasoning: "The bins of the histogram must be width 1 to ensure the total area equals 1."
- NBLM's Answer: A (Correct): The area under the histogram which represents the density must equal 1
  - Reasoning: "The area under the histogram, which represents the density, must equal 1 for a probability density function."
- ChatGPT\_4's Answer: A (Correct): The area under the histogram which represents the density must equal 1
  - Reasoning: "For the area under the histogram to be 1, each bin must represent a proportion of the total dataset."

### Question 54: "Which option reflects the sampling distribution of a proportion?"

- Correct Answer: C: The sampling distribution of the proportion of successes follows a normal distribution
- ChatGPT\_4o\_mini's Answer: B (**Wrong**): Reflects the sampling distribution
  - Reasoning: "This option accurately reflects the sampling distribution."
- NBLM's Answer: C (Correct): The sampling distribution of the proportion of successes follows a normal distribution
  - Reasoning: "The sampling distribution of the proportion of successes follows a normal distribution for large enough samples."
- ChatGPT\_4's Answer: B (**Wrong**): Approximates a normal distribution when sample size is large
  - Reasoning: "The sampling distribution of the proportion of successes approximates a normal distribution when sample size is large."

### Question 58: "Suppose for a null hypothesis that the 'What is the p-value?'"

- Correct Answer: B: Falls within the range of 0.01 to 0.05
- ChatGPT\_4o\_mini's Answer: C (**Wrong**): Since the p-value is less than 0.05, we reject the null hypothesis
  - Reasoning: "(given p-value table along with the question) Since the p-value is less than 0.05, we reject the null hypothesis."
- NBLM's Answer: B (Correct): Falls within the range of 0.01 to 0.05
  - Reasoning: "A p-value of 0.03 falls within the range of 0.01 to 0.05, indicating moderate evidence against the null hypothesis."
- ChatGPT\_4's Answer: B (Correct): Falls within the range of 0.01 to 0.05
  - Reasoning: "(given the p-value evidence table before the question) The p-value indicates that the null hypothesis is rejected at a 5% significance level."

### Question 59: "How do we provide evidence in favor of the null hypothesis?"

- Correct Answer: D: We do not provide evidence in favor, only assess evidence against
- ChatGPT\_4o\_mini's Answer: B (**Wrong**): Failing to reject the null hypothesis
  - Reasoning: "Failing to reject the null hypothesis suggests that we do not have sufficient evidence against it."
- NBLM's Answer: D (Correct): We do not provide evidence in favor, only assess evidence against
  - Reasoning: "Hypothesis testing focuses on providing evidence against the null hypothesis, not in favor of it."
- ChatGPT\_4's Answer: D (Correct): We do not provide evidence in favor, only assess evidence against
  - Reasoning: "We do not provide evidence in favor of the null hypothesis, only assess the evidence against it."

