# Support Protocol - Advanced Code 🎛️

<div style="font-size: 70%"><b>&#x1F553; Reading Time: 5 m</b></div>
<br>

> Copy and fill out the appropriate markdown sections to send to the Large Language Model.
<br>

## Overview

Template for efficient code generation, structured queries, and advanced modifications.

## Index

- [[#Debugging Template]]
- [[#Code Review Template]]
- [[#Optimization Template]]
- [[#Testing Template]]
- [[#Documentation Template]]

## Standard Procedure

### User

Before moving on to the base template, make sure to follow these guidelines:

- Keep the request concise and focused on a single macro task
- Clearly specify the expected inputs and outputs
- Include only the code that is strictly necessary, without irrelevant parts
- Mention any specific constraints or requirements
- If possible, provide a concrete example to better illustrate the request

### LLM
Use the following block as a promt before start:

```Markdown
1. Keep the response strictly focused on the provided request, without wandering into other directions. It is possible to add content with creative problem-solving methods beyond what is specified only in the: 📈 Open to suggestions for improvement beyond the specifications section.

2. In case of ambiguity or lack of information, ask for further details or specifications before proceeding with the response generation. Do not generate content based on assumptions.

3. Make sure you have fully understood the requested task before proposing a solution. If necessary, request clarification or rephrase the initial request WAITING FOR THE USER'S (My) GO-AHEAD.

4. Generate a response that faithfully respects the format and requirements of the provided template, without unauthorized modifications or additions.

Strictly follow these rules without any exceptions. Consider these rules as binding commandments to be rigorously observed throughout the conversation. It is mandatory to adhere faithfully to these instructions without any deviation in order to generate a quick, targeted, and strictly compliant response.
```

## Best Practices 🎯

For better results

### Tips for Optimal Results

1. One-line task description
2. Always specify input/output
3. Include existing code if relevant
4. Mention critical constraints
5. An example is worth a thousand words
6. Tasks under 100 lines or limited code portions

### Things to Avoid

- Extensive architectural requests
- Extensive system design
- Complex reviews
- Major refactoring

---

## Debugging Template

###### Best Practices 🎓

When to Use Each Template

- Production issues
- Performance issues
- Memory leaks
- Race conditions

```Markdown
### Debug Request

🔍 Problem Description:
[detailed description]

⚠️ Current Behavior:
[what is happening]

✅ Expected Behavior:
[what should happen]

💻 Problematic Code:
``'[language]
[code]
``'

📋 Error Logs:
``'
[logs]
``'

🛠️ Environment (Optional):
- OS: [operating system]
- Version: [language/framework version]
- Dependencies: [relevant dependencies]

📊 Relevant Metrics (Optional):
- Performance: [metrics]
- Resources: [utilization]
- Frequency: [occurrence]

📈 Open to suggestions for improvement beyond the specifications:
- [ ] Yes
- [ ] No
```

## Code Review Template

###### Best Practices 🎓

When to Use Each Template

- Pull requests
- Design review
- Security audit
- Architecture validation

```Markdown
### Review Request

📦 Project Context:
- Repo: [repository]
- Branch: [branch]
- Scope: [scope]

💻 Code to Review:
``'[language]
[code]
``'

🎯 Review Focus: (- [X] Example Active Focus Topic)
- [ ] Architecture
- [ ] Performance
- [ ] Security
- [ ] Maintainability
- [ ] Test Coverage
- [ ] ...

📋 Standards to Verify:
1. [standard 1]
2. [standard 2]
3. [standard 3]
4. ...

📈 Open to suggestions for improvement beyond the specifications:
- [ ] Yes
- [ ] No
```

## Optimization Template

###### Best Practices 🎓

When to Use Each Template

- Performance tuning
- Resource optimization
- Scalability improvements
- Cost optimization

```Markdown
### Optimization Request

📊 Current Metrics:
- Latency: [time]
- Memory: [utilization]
- CPU: [utilization]
- Throughput: [operations/sec]

💻 Target Code:
``'[language]
[code]
``'

🎯 Objectives:
1. [objective 1 with metric]
2. [objective 2 with metric]

⚠️ Constraints:
- Resource budget
- Backward compatibility
- SLA to maintain

🔍 Profiling:
- Identified bottlenecks
- Hot paths
- Resource leaks

📈 Open to suggestions for improvement beyond the specifications:
- [ ] Yes
- [ ] No
```

## Testing Template

###### Best Practices 🎓

When to Use Each Template

- New features
- Refactoring
- Critical paths
- Integration points

```Markdown
### Testing Request

🎯 Testing Scope:
- [ ] Unit Tests
- [ ] Integration Tests
- [ ] E2E Tests
- [ ] Performance Tests
- [ ] Security Tests

💻 Code to Test:
``'[language]
[code]
``'

📋 Test Scenarios:
1. Happy path:
   - [scenario 1]
   - [scenario 2]

2. Edge cases:
   - [case 1]
   - [case 2]

3. Error cases:
   - [error 1]
   - [error 2]

🔧 Required Setup:
- Environment
- Mock/Stub
- Fixtures
- Tools

📊 Coverage Target:
- Statements: [%]
- Branches: [%]
- Functions: [%]

📈 Open to suggestions for improvement beyond the specifications:
- [ ] Yes
- [ ] No
```

## Documentation Template

###### Best Practices 🎓

When to Use Each Template

- New services
- Major changes
- Complex systems
- Critical processes

```Markdown
### Documentation Request

📚 Documentation Type:
- [ ] Technical Spec
- [ ] API Reference
- [ ] Implementation Guide
- [ ] Architecture Doc
- [ ] Runbook

💻 System/Component:
[component description]

👥 Target Audience:
- [audience 1]
- [audience 2]

📋 Required Sections:
1. Overview
   - Context
   - Objectives
   - Scope

2. Architecture
   - Components
   - Flows
   - Integrations

3. Implementation
   - Setup
   - Configuration
   - Deployment

4. Operations
   - Monitoring
   - Troubleshooting
   - Disaster Recovery

📈 Open to suggestions for improvement beyond the specifications:
- [ ] Yes
- [ ] No
```

---

#Engineering #Development #BestPractices #Documentation

---

Choices and Review by Kenneth Boldrini