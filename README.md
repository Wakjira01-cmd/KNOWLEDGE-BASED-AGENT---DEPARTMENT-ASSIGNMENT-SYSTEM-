# KNOWLEDGE-BASED-AGENT---DEPARTMENT-ASSIGNMENT-SYSTEM-
Short Description 

What code is this? 
As explained in Chapter 4 of AI Course, this code implements a Knowledge-Based Agent. Based on three criteria—skills, interest, and exam results—the agent suggests a university department to a student.

Concepts Used in: 
 Knowledge Base 
This dictionary contains department requirements. 
• Inference Engine :
Uses rules to assess every department 
• Logical Inference 
Points are determined using IF-THEN principles. •
Making Decisions 
 Chooses the department with the highest score

The Four Rules Implemented
Rule	Description	Points
Rule 1	Each matching skill	+2 per skill
Rule 2	Matching interest	+3
Rule 3	Exam score meets minimum	+5 (else disqualified)
Rule 4	Highest total points	Recommend best

Parts of the Agent
 	Self.departments dictionary in the Knowledge Base
 	Inference Engine → Rules used in the evaluation process
 	Making decisions → Determines the highest points

