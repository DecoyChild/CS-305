Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is an online banking solution looking to add a web application to their portfolio. They require a secure connection to both the customers using the platform, as well as 
securing the data that is stored off premise. Assuring that the information that is gathered between all connections is secure is of the upmost importance. Not only 
does Artemis Financial require secure connections between the host and clients, they are also looking for protection against modern attacks such as DDOS attacks. 

I feel that I was able to refactor the codebsae to make it more secure. Mostly be identifying the vulnerabilities at the manual code review.   

The parts that I found the most challanging was fInding what dependencies to supress in the maven static testing. The suppression logic was easy, it was the act of identifying what vulnerabilities to spuress.

Refactoring the code to include secure functions, like adding input validations for the REST api input parameters, adds a layer of security. Protecting against SQL injections or other harmful 
inpust that could be used.

After refactoring the sample code, running the dependancy check is the best start to assure that you didnt add any new vulnerabliliies. Compare the previous vulnerability report to the new report would be the 
best way to identify any newly introduced vulnerabilities.

In future assignments an tasks, I would find the manual code review most helpful. Refactoing your code is an important skill, and can lead to more efficient and secure programs

I would show future employers the dependency check that was conmpleted on the sample code base. This shows an understanding on where to look for vulnerabilities and how to begin mitigating them
