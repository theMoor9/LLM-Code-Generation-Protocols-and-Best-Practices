# Support Protocol - Smart Code⚡

<div style="font-size: 70%"><b>&#x1F553; Reading Time: 3 m</b></div> 
<br>

> Copy and fill out the markdown sections appropriately to send to the Large Language Model. 
<br>

## Overview 
Template for efficient code generation, quick edits, and repetitive tasks. 

## Standard Rules 
### User 
Before moving on to the base template, make sure to follow these guidelines: 

- Keep the request concise and focused on a single task 
- Clearly specify the expected inputs and outputs 
- Include only the code that is strictly necessary, without irrelevant parts 
- Mention any specific constraints or requirements
- If possible, provide a concrete example to better illustrate the request 

### LLM 
Use the following block as a promt before start:

```Markdown 
1. Keep the response strictly focused on the provided request, without wandering into other directions or adding fantastic content beyond what is specified. 
2. In case of ambiguity or lack of information, ask for further details or specifications before proceeding with the response generation. Do not generate content based on assumptions. 
3. Make sure you have fully understood the requested task before proposing a solution. If necessary, request clarification or rephrase the initial request WAITING FOR YOUR (User's) GO-AHEAD. 
4. Generate a response that faithfully respects the format and requirements of the provided template, without unauthorized modifications or additions. 

Strictly follow these rules without any exceptions. Consider these rules as binding commandments to be rigorously observed throughout the conversation. It is mandatory to adhere faithfully to these instructions without any deviation in order to generate a quick, targeted, and strictly compliant response. 
``` 

## Best Practices 🎯
For better results

### When to Use Templates

- Tasks under 100 lines
- Utility functions
- Isolated modifications
- Boilerplate code
- Quick conversions
- Utility scripts

### Tips for Optimal Results

1. One-line task description
2. Always specify input/output
3. Include existing code if relevant
4. Mention critical constraints
5. An example is worth a thousand words

### Things to Avoid

- Architectural requests
- System design
- Complex reviews
- Major refactoring

--- 
## Base Template

```Markdown
### Quick Code Request

🎯 Task: [one-line task description]

📝 Specifications:

- Lang: [language]
- Input: [what I have]
- Output: [what I need]

✨ Extra (optional):

- Dependencies: [if any]
- Constraints: [if any]

💻 Current Code (if present):
```[language]
[existing code]
```.

```

## Usage Examples

### 1. Utility Generation
```markdown
### Quick Code Request - Utility Code Block

🎯 Task: Helper function for email validation

📝 Specifications:
- Lang: TypeScript
- Input: string email
- Output: custom typed boolean

✨ Extra:
- Dependencies: zod
- Constraints: RFC 5322 validation

```

### 2. Code Refactoring
```markdown
### Quick Code Request - Code Refactoring

🎯 Task: Add structured logging

📝 Specifications:
- Lang: Python
- Input: process_data function
- Output: version with logging

✨ Extra:
- Dependencies: structlog
- Constraints: mantieni performance

💻 Codice attuale:
```python
def process_data(data):
    return data.transform()
```.

```

### 3. Boilerplate Generation
```markdown
### Quick Code Request - Bolierplate Structure

🎯 Task: CRUD controller REST

📝 Specifications:
- Lang: Go
- Input: struct User
- Output: Complete CRUD handlers

✨ Extra:
- Dependencies: gin-gonic
- Constraints: standard REST
```


--- 

#QuickCode #Development #Template 

--- 
Choices and Review by Kenneth Boldrini