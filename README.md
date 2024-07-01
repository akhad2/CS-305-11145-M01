Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

- Artemis Financial as in it's name is a financial company therefore they require high security for majority if not all of their operation. The issue they wanted to fix was file verification.
I recommended and created hashing the data using SHA-256 bit and the outputted page is is using self signed certificate with the server ran through HTTPS. Multiple security checkpoints, and final SHA-256 hash to prove that
data has not been changed or altered.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

- I did well choosing SHA-256 bit hash. It alone can prove data certaincy since it impossible with current computer to reverse. It is important to code securily as any
  data leakage can cost millions and loss to company reputation. Lack of software security can bankrupt a company because why would a potential client do business if the company's security is lackluster.
  It is crucial that security is taken precedence and industry best standards are applied where applicable.
  
Which part of the vulnerability assessment was challenging or helpful to you?

-I found dependency checking quite difficult as you have to manually go 1 by 1 to verify if it does or not apply to your code.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increaed layer of security such as when I changed application property to run through HTTPS. Dependency check is something I will use to find vulnerabilities as it lays out many vulnerabilities and most of them can
potentially apply.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

- Dependency check and I did not see any specific error that applied to my code. Most were warnings about not having latest updates.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

- Coding practice I use is to frequently test the code, and re-test with multiple outputs or scenarios.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

-Security first practices such as always using encryption when possible and data verification.
