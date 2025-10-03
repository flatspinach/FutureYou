# FutureYou
An AI-powered career mentor for students, built for a hackathon.

Project Title: FutureYou: An AI-Powered Career Mentor for Students

1. Abstract

"FutureYou" is a user-friendly web application designed to address the common career uncertainty faced by students. By leveraging the power of Google's Gemini AI, the application provides personalized and actionable career guidance. It analyzes a student's technical skills from their resume, their personal passions from a guided questionnaire, and their work style preferences from a personality assessment. Based on this holistic profile, the AI generates tailored career recommendations and a step-by-step learning roadmap, empowering students to make informed decisions about their future.

2. Problem Statement

Students and freshers in today's competitive environment often lack access to personalized career counseling. They struggle to connect their academic achievements, personal interests, and inherent personality traits to suitable job roles. This leads to confusion, uncertainty, and a trial-and-error approach to their early careers. The challenge is to provide an accessible, immediate, and data-driven tool that can offer a clear and personalized direction.

3. Proposed Solution

Our project, "FutureYou", is a single-page web application that acts as a virtual career mentor. The solution is built on a three-pronged data collection approach:

Resume Analysis: The user uploads their resume (PDF/DOCX), from which the application extracts text to understand their existing skills, projects, and educational background.

Interest Profiling: The user answers open-ended questions about their passions and hobbies.

Personality Assessment: A short multiple-choice quiz helps determine the user's preferred work style and environment.

This combined data is sent to the Google Gemini API, which then provides a comprehensive analysis, including top career matches and a simple roadmap for skills development.

4. Key Features

Simple Multi-Step Interface: Guides the user through the process easily.

Resume Parsing: Supports both PDF and DOCX file formats for skill extraction.

Holistic Analysis: Considers skills, interests, and personality for well-rounded advice.

AI-Generated Recommendations: Provides top career matches with reasons for the fit.

Actionable Learning Roadmap: Suggests a simple, step-by-step path for acquiring necessary skills.

5. Technology Stack

Frontend: HTML5, CSS3, Vanilla JavaScript

AI Integration: Google Gemini API (via REST API)

File Processing: PDF.js and Mammoth.js libraries (for reading resume files in the browser)

6. Conclusiong

"FutureYou" successfully demonstrates a practical application of generative AI to solve a real-world problem for students. By providing instant, personalized, and structured career advice, the project serves as a valuable tool to reduce career-related anxiety and help students begin their professional journeys with clarity and confidence.
