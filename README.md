# CS-305-Software-Security

### _Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?_
Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for its customers. They wanted to implement and apply the most current and effective software security to protect their client data and financial information.


### _What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?_
I did a lot of research into the most common cybersecurity attacks for fintech companies. This research helped me interpret the client’s needs and address common shortcomings in their industry. It is important to code securely because there are many different ways that code can be written so that the compiler accepts it, but it leaves the application vulnerable to attack. Software security adds to a company’s overall well-being because a data leak could hurt its customers and diminish its reputation.


### _What about the process of working through the vulnerability assessment did you find challenging or helpful?_
I found the vulnerability assessment diagram a bit vague. Since the diagram was used to guide most of our work this term, it would have been nice to add more detail. However, I found it helpful for breaking down the application into separate parts for analysis.


### _How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?_
To increase the layers of security, I ran through the vulnerability diagram and determined the areas of my code that may be vulnerable. In the future, I will validate user input for data type, size, and special characters. I will also apply the principle of least privilege to ensure that no unauthorized users gain access to the data.


### _How did you ensure the code and software application was functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?_
To ensure that the software was functional and secure I would make sure that the code worked as expected when a secure request was made and that the code would not run if an insecure request was made. After refactoring the code, I re-ran the Maven Dependency-Check report to ensure that there were no new vulnerabilities introduced in any of the dependencies. I’d also review the code with the vulnerability assessment diagram and address any level of possible vulnerability that I introduced.


### _What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?_
I really liked the Maven Dependency-Check tool to check for security updates. I also referenced the Java Secure Coding guidelines frequently to make sure that I was taking all security measures possible.


### _Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?_
I’d like to show my mitigation plan. This plan is the result of all of my research, static testing, and manual code reviews. I put a lot of effort into identifying and addressing that all vulnerabilities.
