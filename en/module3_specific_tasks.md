# Module 3: Prompting for Specific Software Engineering Tasks

## Module Objective
Apply prompt engineering techniques to concrete and daily software engineering tasks, optimizing interaction with LLMs to maximize their utility in development workflows.

## Lessons

### Lesson 3.1: Code Generation and Optimization
**Description:** Specific techniques for obtaining high-quality, maintainable, and efficient code from LLMs.

**Content:**
- Precise specification of functional and non-functional requirements
- Techniques for requesting different alternative implementations
- Prompts for performance, security, and readability optimization
- Strategies for language-specific code generation

**Practical Exercise:** 
Develop a series of progressive prompts to generate a complete REST API, from initial specification to optimized implementation. Use OpenAI API with different temperature parameters to compare the quality and creativity of generated code.

### Lesson 3.2: Explanation and Understanding of Complex Code
**Description:** Methods for using LLMs as tools for understanding and documenting existing code.

**Content:**
- Structuring prompts for component-based code analysis
- Techniques for requesting explanations at different abstraction levels
- Prompts for identifying design patterns and architecture
- Methods for generating documentation from code

**Practical Exercise:** 
Select a complex code fragment (e.g., a machine learning algorithm) and design prompts that generate explanations at three levels: overview, detailed logical flow, and line-by-line analysis. Implement in Claude and evaluate the accuracy and clarity of explanations.

### Lesson 3.3: Code Translation Between Languages
**Description:** Techniques for obtaining accurate and idiomatic code translations between different programming languages.

**Content:**
- Specification of conventions and style of target language
- Handling fundamental differences between programming paradigms
- Preservation of comments and documentation during translation
- Verification of functional equivalence

**Practical Exercise:** 
Create prompts to translate a Java class with complex design patterns to Python, maintaining functionality and adapting to Python conventions. Implement in Gemini and evaluate translation quality according to predefined criteria.

### Lesson 3.4: Unit and Integration Test Generation
**Description:** Methodologies for using LLMs in creating complete and robust test suites.

**Content:**
- Specification of coverage and desired test types
- Prompts for generating comprehensive test cases
- Techniques for edge case testing and error handling
- Integration with specific testing frameworks

**Practical Exercise:** 
Design prompts to generate complete unit tests for an authentication module, including happy cases, edge cases, and error handling. Implement in ChatGPT and evaluate the coverage and robustness of generated tests.

### Lesson 3.5: Technical Documentation and Diagram Creation
**Description:** Techniques for generating clear, complete, and useful documentation for different technical audiences.

**Content:**
- Prompts for different types of documentation (API, architecture, user)
- Specification of detail level and target audience
- Generation of descriptions for technical diagrams
- Structuring complex technical documentation

**Practical Exercise:** 
Create prompts to generate complete documentation for a REST API, including endpoint descriptions, parameters, responses, and usage examples. Use OpenAI API to generate documentation in Markdown format and evaluate its clarity and completeness.

### Lesson 3.6: AI-Assisted Debugging
**Description:** Methodologies for leveraging LLMs in bug identification, analysis, and resolution.

**Content:**
- Structuring error information for effective analysis
- Step-by-step reasoning techniques for debugging
- Prompts for hypothesis generation and test plans
- Verification and validation of proposed solutions

**Practical Exercise:** 
Develop a prompting methodology to analyze a stack trace and related code, identify possible error causes, and propose verifiable solutions. Implement in Claude and document the reasoning and resolution process.

### Lesson 3.7: Log Analysis and Information Extraction
**Description:** Techniques for using LLMs in interpreting and analyzing system and application logs.

**Content:**
- Prompts for identifying patterns in extensive logs
- Event summarization and categorization techniques
- Event correlation and anomaly detection
- Extraction of metrics and KPIs from logs

**Practical Exercise:** 
Design prompts to analyze a web server log file, identify abnormal traffic patterns and possible intrusion attempts. Use Gemini API with Python code to process and visualize analysis results.

### Lesson 3.8: Architecture and Solution Brainstorming
**Description:** Methods for using LLMs as collaborators in designing architectures and technical solutions.

**Content:**
- Techniques for specifying requirements and constraints
- Prompts for generating multiple architectural approaches
- Comparative evaluation of design alternatives
- Iterative refinement of proposed solutions

**Practical Exercise:** 
Create a detailed prompt to design the architecture of a real-time data processing system, specifying scalability, latency, and availability requirements. Implement on multiple platforms (ChatGPT, Claude, and Gemini) and compare proposed solutions.
