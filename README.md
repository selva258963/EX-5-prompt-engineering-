

# EXP 5: Comparative Analysis of Naïve Prompting versus Basic Prompting Using ChatGPT Across Various Test Scenarios
 # Aim: 
 To test how ChatGPT responds to naïve prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios, analyzing the quality, accuracy, and depth of the generated responses.
## REG NO: 212222040151
# Algorithm: 
Define the Two Prompt Types:
Naïve Prompts: Broad, vague, or open-ended prompts with little specificity.
Basic Prompts: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.
To conduct an experiment comparing how different pattern models (such as broad vs. basic prompts) respond to varying scenarios, we will:

## Define the variables:

Pattern Models: These can be broad or unstructured prompts (more open-ended or exploratory) vs. basic prompts (more precise and structured).

Metrics: Quality, accuracy, and depth of responses.

Scenarios: We'll test both broad and refined prompts across the following types of customer support scenarios:

Product troubleshooting

Order tracking

General inquiry

Hypothesis: Broad prompts will provide more expansive but potentially less focused responses, while basic prompts will yield more accurate and actionable answers but may be less conversational.

## Experiment Setup
1. Broad vs. Basic Prompts
Broad Prompts (Unstructured): These ask for general or open-ended responses without guiding the model too specifically.

Example: "Can you help me with my product issue?"

Scenario: The user might be seeking troubleshooting help, but the prompt is general and could apply to any product.

Basic Prompts (Refined): These are clear, specific prompts that guide the AI towards a narrower scope or task.

Example: "My coffee machine is not turning on, how can I fix it?"

Scenario: This prompt provides specific context that allows the AI to provide precise troubleshooting steps.

2. Test Scenarios
We'll evaluate both types of prompts across three common customer support scenarios:

Scenario 1: Product troubleshooting

Scenario 2: Order tracking

Scenario 3: General inquiry (e.g., returns or policies)

Experiment Procedure
Step 1: Broad vs. Basic Prompt for Product Troubleshooting
Broad Prompt:
“Can you help me with my product issue?”

Expected response: The model may provide general advice on contacting support or offer basic troubleshooting without specific details.

Basic Prompt:
“My blender stopped working. It’s not turning on. What should I check?”

Expected response: The model will offer specific troubleshooting steps (e.g., check the power cord, reset the appliance, etc.).

Step 2: Broad vs. Basic Prompt for Order Tracking
Broad Prompt:
“Can you track my order?”

Expected response: The model may ask for further clarification or details such as order number or delivery information.

Basic Prompt:
“Can you provide the current status of my order #A456?”

Expected response: The model directly responds with order tracking details if integrated with the necessary system, or asks for further verification (email, order number).

Step 3: Broad vs. Basic Prompt for General Inquiry
Broad Prompt:
“What’s your return policy?”

Expected response: The model may provide a summary of the return policy, but it could be vague and lack specifics (e.g., time limits, conditions).

Basic Prompt:
“Can I return a product that I bought two weeks ago? What’s the process?”

Expected response: The model gives a more detailed response, explaining return timelines, conditions, and process steps.

## Analysis Criteria
We will compare the responses based on three key metrics:

Quality:

Broad Prompt: Responses will likely be less specific but cover a wider range of possibilities.

Basic Prompt: Responses should be highly focused, relevant, and actionable.

Accuracy:

Broad Prompt: Accuracy could suffer due to vagueness, as the AI must infer more about the user’s exact problem.

Basic Prompt: Responses will likely be more accurate due to clearer context, leading to more precise answers.

Depth:

Broad Prompt: Responses may be more general and might lack depth, especially if the model interprets the input ambiguously.

Basic Prompt: The model can provide a more detailed and informative response, as the user has already specified the issue.

# Experiment: Broad vs. Basic Prompts for AI Chatbot Responses

## 1. Experiment Setup

| **Scenario**                     | **Broad Prompt (Unstructured)**                              | **Basic Prompt (Refined)**                              |
|-----------------------------------|--------------------------------------------------------------|--------------------------------------------------------|
| **Product Troubleshooting**       | “Can you help me with my product issue?”                    | “My blender stopped working. It’s not turning on. What should I check?” |
| **Order Tracking**                | “Can you track my order?”                                  | “Can you provide the current status of my order #A456?” |
| **General Inquiry (Return)**     | “What’s your return policy?”                                | “Can I return a product that I bought two weeks ago? What’s the process?” |

---

## 2. Analysis Criteria

| **Metric**       | **Broad Prompt**                                                                 | **Basic Prompt**                                                                |
|------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| **Quality**      | Less specific, more general responses, possibly vague and covering a wider range | Specific, highly focused, actionable responses                                   |
| **Accuracy**     | Likely lower, as the model needs to infer details and context                    | High, as the model has clearer context and user input                           |
| **Depth**        | Low to moderate, lacks in-depth solutions, general advice                        | High, responses are tailored to the exact user issue with details               |

---

## 3. Test Scenario Responses

| **Scenario**               | **Broad Prompt Response**                     | **Basic Prompt Response**                      | **Quality**  | **Accuracy** | **Depth**     |
|----------------------------|-----------------------------------------------|------------------------------------------------|--------------|--------------|---------------|
| **Product Troubleshooting** | General advice on troubleshooting (e.g., "Check the power cord") | Specific steps for resolving the issue (e.g., “Make sure the blender is properly plugged in”) | Moderate     | Low          | Low           |
| **Order Tracking**          | General query about tracking orders (e.g., “Let me check the status”) | Specific order status update (e.g., “Your order is out for delivery, expected arrival tomorrow”) | Moderate     | High         | High          |
| **General Inquiry (Return)**| Vague return policy summary (e.g., “You can return within 30 days”) | Clear steps and conditions for returns (e.g., “You can return within 30 days as long as the product is unopened”) | Low          | High         | High          |

---

## 4. Conclusion

| **Prompts**               | **Strengths**                                            | **Weaknesses**                                      |
|---------------------------|----------------------------------------------------------|-----------------------------------------------------|
| **Broad Prompts**          | Flexible, good for initial inquiries, explores multiple avenues | Less specific, low accuracy, shallow responses      |
| **Basic Prompts**          | Accurate, specific, and actionable, tailored to the user’s need | Limited flexibility, less room for exploratory responses |

---


# RESULT: 
The prompt for the above said problem executed successfully
