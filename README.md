# Docs-for-Developers-Notes

understanding your Audience
When you write code you are cursed with the curse of knowledge → you assume everybody has the same knowledge as you
→ Need to empathize with the user to understand their needs

Questions to outline the user:
What are their goals?
What is my expected audience?
What are their basic needs?
	→ What is this product?
	→ What features are available?

Validate these assumptions from existing data sources like support tickets or the sales team or collect new data in interviews or developer surveys

Based on this information create fictional characters (a persona), user stories, friction logs and summarize your findings.


Planning your documentation
Content types:
What kind of content can I create for the users?
Code comments | describing what the code does in code
READMEs | A file containing basic installation like a description, and how to install, troubleshooting steps and basic examples P27
Getting started documentation | A quick guide to get up and running
Conceptual documentation | Explains ideas and concepts behind the service
Procedural documentation | A step-by-step guide that helps accomplishing a certain task as quickly as possible 
Tutorials | Teach the user how to do a specific task.
How to guide | Shows how a user can solve a business problem my performing a step-by-step guide
API reference | A reference describing API resources and endpoints. Optionally with plenty of examples
Glossary | A collection of terms with unclear meanings that are often used within your service or documentation
Troubleshooting documentation | A document that shows workarounds around well known problems
Change documentation | A changelog documents all the changes you made to the documentation or your API. This can easily be done with Github
Planning the documentation
A plan describing how a user accesses the documentation.
Drafting documentation
Choosing your writing tools
Choose a tool to write the documentation. Options are Markdown HTML or a special wiki software.
Define the title and goal of the document
The title summarizes the goal of the document
“The title should be the shortest clearest rephrasing of the documents' purpose from the users' perspective”


Text outline | All the steps a user has to go through to reach a goal. All of these outline can become a Header.

Documentation consists of Headers Paragraphs Procedures Lists and Callouts


Header | A header should be a brief description 
Paragraphs | Sentences that give context purpose and extra details
Procedures | A set of actions to perform to achieve a goal 
Lists | Lists group 
Callouts | Something you have to know like ! Warning ! Caution
Writing for skimming
A reader wants to get as much information as possible in very little time. Readers view the content in an F pattern.
State the most important content first
Break up large blocks of text
A long paragraph is difficult to skim. Most people will just skip it
Break up long documents
A single document cant server all readers. Break up one document into many
Write out of sequence
You dont have to write the first thing first. if you get stuck work on the second thing. 
Strive for simplicity and clarity
A short concise documentation is easier to read than a long block of text
Highlight missing content | Put a TODO in places where there is still documentation to come
Templates | Create templates with pre-filled titles code blocks and other commonly used for writing documentation
Editing documentation
On each pass of editing documentation focus on different thing:
technical accuracy | create a checklist: Are the results as promised / expected from the reader ; Is there any technical jargon left in the document ; Does all the code function correctly
completeness | verify that the documentation has all the content neccesary. There are no gaps and no TODOS left
structure | having a proper structure is like a sign post for the reader. What the document is about should be clear from the titel
clarity and brevity | review the document line by line ; remove awkward phrases ; remove duplicates
Someone else should look at your documentation. For this request a peer or a technical review from someone more experience on the specific topic.
Feedback is important: “You may only criticize an idea if you also add a constructive suggestion”
