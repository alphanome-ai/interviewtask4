# Speech-to-Speech RAG Assignment: SEC Filings Summarization

## Overview
This is a screening assignment for our developer position. The task involves building a web application that enables voice-based interaction with SEC filing summary data using RAG (Retrieval Augmented Generation) and speech-to-speech conversion.

## Background
Financial professionals often need quick, hands-free access to SEC filing information while multitasking or on the move. This assignment focuses on building a practical application that combines speech RAG and speech-to-speech technologies to provide natural voice-based interactions with SEC filing data.

## Task Description
Build a web application using [Reflex.dev](https://reflex.dev/) that allows users to query SEC filing information using voice input and receive spoken response. The application should utilize RAG to retrieve relevant information from the provided database of SEC filing summaries and generate concise, contextually relevant responses.

The app should work similar to [https://www.turtlee.in/voice](https://www.turtlee.in/voice)
![image](https://github.com/user-attachments/assets/0b29a9c3-af33-44eb-ac50-0ca07c1a0bf7)



## Technical Requirements

### Core Features
- Implement speech-to-speech conversion for user queries
- Create a RAG system using the provided SEC filing summaries database
- Generate natural language responses using an LLM
- Maintain conversation history and context
- Provide visual feedback during voice interaction

### Technical Specifications
- Use Reflex.dev as the primary framework
- Build speech-to-speech processing engine
- Create RAG pipeline from the provided summary database
- Integrate with an LLM API for response generation
- Include a fallback text interface
- App should work for 1 user flawlessly

### Quality Standards
- Write clean, well-documented code
- Include comprehensive type hints
- Follow Python PEP 8 style guidelines
- Implement proper logging and monitoring
- Document RAG implementation details

## Evaluation Criteria 

### Technical Implementation (35%)
- Code quality and organization
- Speech processing accuracy
- RAG system effectiveness
- Error handling and edge cases
- Database query optimization

### Voice Interface Quality (25%)
- Speech recognition accuracy
- Voice response naturalness
- Conversation flow
- Handling of ambient noise and accents
- Fallback mechanisms

### Information Retrieval Quality (25%)
- Accuracy of retrieved information
- Relevance of responses
- Response conciseness
- Context maintenance
- Citation accuracy

### Performance and Scalability (15%)
- Response time optimization
- Resource usage efficiency
- Query optimization
- API usage optimization

## Submission Guidelines

### Required Files
Your submission should be a ZIP file containing:
- Complete source code of the application
- README.md with:
  - Setup instructions
  - API configuration steps
  - Voice interaction examples
  - Database connection guide
  - Performance considerations
- Requirements.txt or similar dependency file
- Testing scripts and documentation

### Submission Process
Send your submission as a compressed ZIP file to info@alphanome.ai

## Important Notes
- Implement appropriate rate limiting for all APIs
- Include error handling for speech recognition failures
- Document any assumptions about the summary data format
- Consider implementing a caching mechanism

## Time Expectation
- The assignment should take approximately **5-10 days** to complete
- **Focus on core functionality first**, then add improvements if time permits

## Questions?
If you have any questions about the assignment, please email info@alphanome.ai
