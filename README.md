## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

The client, Artemis Financial, is a company that helps their clients with financial planning, such as retirement, investing, insurance, etc. The client wanted to expand their online presence, and requested guidance for securely developing their RESTful API.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

After finding the client’s software security vulnerabilities, I effectively documented the findings in a security report. This report not only provided the client a summary of the vulnerabilities, but a way to mitigate those vulnerabilities as well.

Coding securely, especially during the entirety of a project, will help mitigate most known software vulnerabilities from being deeply integrated into the project. This helps to speed up project development since there will be less time needed for fixing software vulnerabilities after the project has been launched.

A company's reputation with their clients will increase when the company places more focus in software security in their projects. Not only this, but the company's own data, code, and even hardware will be safer from being lost, stolen, or manipulated since attackers will have a much higher difficulty breaking in to their systems. 

## Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was determining false positives. Although not perfect, I believe I have strengthened my skill deciding if a vulnerability is a real issue or just a false positive. Through more research and practice, my ability to identify false positives will greatly improve.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Adding layers of security began by gathering and studying what the client needed. When these needs were identified, solutions were brainstormed, researched, and refactored so to be valuable to the client and correctly secured when implemented. After each solution was implemented, the code was statically analyzed, using the OWASP Dependency-Check tool, for any new vulnerabilities from libraries. The code was also manually analyzed for verifying that all user input is cleaned and validated, any queries are parameterized, all access points have authorization and authentication rules, etc.

In the future, I would continue to use a static analysis tool for analyzing library vulnerabilities. I would also use a dynammic analysis tool for discovering runtime vulnerabilities. These tools, plus a manual code review, would thoroughly inform me which mitigation techniques to use.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?


## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?


## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
