# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

### Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
1.Identify different prompt styles – Broad, Basic, Refined.

2.Select test scenarios – Automated Test Script Generation, Bug Identification, Performance Test Planning.

3.Apply each prompt type to all scenarios.

4.Record and document AI responses.

5.Evaluate based on clarity, accuracy, depth, and relevance.

6.Compare and analyze which prompting style performs best.

7. Analyze Findings – Identify which prompting style is most effective for each task.
## Output
#### Scenario 1: Automated Test Script Generation

Broad Prompt: “Generate a test script for login.”

Output: Very generic script, only checks login open.

Evaluation: Low clarity, misses edge cases.

Basic Prompt: “Generate an automated test script to verify valid and invalid logins.”

Output: Covers valid/invalid login attempts, but minimal detail.

Evaluation: Moderate clarity and relevance.

Refined Prompt: “Create an automated test script for web login that verifies valid credentials, invalid passwords, error messages for empty inputs, and locked accounts.”

Output: Detailed script covering positive/negative cases and validations.

Evaluation: High clarity, accuracy, and depth.

#### Scenario 2: Bug Identification in Test Cases

Broad Prompt: “Check this test case for bugs.”

Output: General remarks, no depth.

Evaluation: Weak insights.

Basic Prompt: “Analyze the login test case and point out any missing edge cases.”

Output: Identifies some missing conditions like password reset.

Evaluation: Moderate detail.

Refined Prompt: “Review the login test case and identify all potential bugs and edge cases including invalid inputs, SQL injection, timeouts, and concurrent login attempts.”

Output: Comprehensive with specific vulnerabilities.

Evaluation: High-quality and actionable.

#### Scenario 3: Performance Test Planning

Broad Prompt: “Write a performance test plan.”

Output: Generic high-level plan, vague.

Evaluation: Low utility.

Basic Prompt: “Create a performance test plan for a website.”

Output: Includes load testing and response times but lacks detail.

Evaluation: Moderately useful.

Refined Prompt: “Design a detailed performance test plan for an e-commerce website simulating 1000 concurrent users, load distribution, peak traffic times, response goals, and recovery steps.”

Output: Specific plan with metrics, timing, and contingencies.

Evaluation: High clarity, accuracy, and relevance.

### Analysis

Broad prompts → Vague, generic, and shallow results.

Basic prompts → Useful but incomplete; limited detail.

Refined prompts → Superior quality, covering edge cases, validations, and depth.

### Conclusion

This experiment confirms that prompt structure directly affects AI response quality.

Broad prompts = weak results.

Basic prompts = moderately useful.

Refined prompts = the most effective, accurate, and context-aware outputs.
## Result
Thus, a comparative analysis of prompting styles was successfully conducted, and it was observed that refined and well-structured prompts significantly enhance the clarity, accuracy, and depth of AI outputs.
