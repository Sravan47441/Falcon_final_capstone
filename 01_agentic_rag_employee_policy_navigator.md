# Capstone 1: Agentic RAG Employee Policy and Onboarding Navigator

## Project overview

**Domain:** Employee services and onboarding  
**Coverage:** Concepts learned in Weeks 1-6  
**Suggested duration:** One week approx.  
**Framework:** LangChain, and must use LangGraph or CrewAI  
**Total marks:** 100

---

**Frontend:** Build a user-friendly interface using Streamlit, React, Angular, or any suitable framework.  
**Backend:** Implement a well-structured and modular backend.  
**Integration Layer:** Ensure seamless communication between the frontend and backend.
**RAG:** Include dedicated ingestion and retrieval layers within the RAG architecture.  

---

## Business scenario - New Employee Support System

New employees often need guidance on onboarding formalities, workplace arrangements, equipment, company policies, and business travel. This information may be spread across multiple documents and can vary based on the employee’s role and circumstances.

The proposed New Employee Support System will act as a centralized assistant that understands an employee’s context, retrieves relevant company information, provides personalized guidance, and asks clarifying questions when needed. Its goal is to make the onboarding process simple, efficient, and easy to navigate.

## Your challenge

Design and build an **agentic RAG application** that helps new employees find relevant guidance and understand their next steps during onboarding.

Your solution should go beyond answering isolated questions. Decide how it will understand context, seek clarification, find applicable information, and combine evidence when a request covers more than one topic.

## Expected outcomes

Your application should be able to:

- Understand an employee's question and identify the relevant policy topics.
- Ask for clarification when important employee context is missing.
- Retrieve applicable guidance and explain answers with identifiable sources.
- Handle a request that requires information from more than one document or topic.
- Use conversation context to respond meaningfully to follow-up questions.
- Recognize when the available policies lack the required guidance or contain conflicting instructions, and indicate when human assistance is appropriate.

Use fictional policies and employee profiles. The application should provide guidance without claiming to approve requests, change employee records, or complete tasks on an employee's behalf.

## Illustrative situations

Use these as starting points and develop additional situations of your own:

- A new employee asks what to prepare before joining remotely.
- A question covers both equipment arrangements and business travel.
- The answer depends on information the employee has not provided.
- An employee follows up after completing one of the suggested steps.
- A new employee asks about an allowance that the available policies do not specify.
- Two policy documents appear to give different guidance.

Define the policy scope and employee situations you want to support. Explain how your application determines whether its answer is adequately supported.

## Your design decisions

You own the architecture, agent responsibilities, tools, policy collection, retrieval approach, conversation-memory strategy, and interaction experience. Choose a manageable set of employee-service topics. Use the supplied [mock policy documents](mock_documents/README.md) as a starting point and extend the fictional guidance if needed.

Apply relevant learning from Weeks 1-6 and justify your choices. Explain how the application decides when to clarify, retrieve more information, or refer the employee to a human. You may reuse learning patterns from the weekly exercises, but the final solution should reflect your own design.

## Deliverables

1. **Project proposal:** Problem statement, intended users, scope, and expected value.
2. **Solution design:** Your architecture and the reasoning behind the main design choices.
3. **Working prototype:** Runnable application with fictional policies, sample scenarios, and setup instructions.
4. **Evaluation report:** Your test scenarios, observed results, and analysis of answer quality and limitations. Cover each expected outcome, including separate cases for missing employee context, guidance absent from the policies, and conflicting policy instructions.
5. **Final demonstration:** A walkthrough showing clarification, a multi-topic request, and a contextual follow-up. Use these interactions to explain how the application chooses when to ask for context, retrieve more evidence, or refer the employee to a human.
6. **Working-demo evidence:** Submit a short screen-recorded video or a set of clearly labelled screenshots showing the application running. Include sample user questions, the application's responses, and the supporting sources displayed.
7. **Evidence notes:** Add brief captions or timestamps explaining the scenario demonstrated and the observed outcome. Include evidence of both a case where the policies lack the required guidance and a separate case involving conflicting policy instructions. Ensure credentials and personal information are not visible.

Assessment focuses on the usefulness and reliability of your employee experience and the reasoning behind your design. 
Explain trade-offs and support claims of quality with evidence from your own evaluation.

