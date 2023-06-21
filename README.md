# CS305--Software-Security

   **Client Summary**
  Artemis Financial serves as a financial consulting company. They assist clients in developing individualized financial plans 
including savings accounts, retirements, investments, and insurance. Artemis Financial's goal is to modernize their online 
operations while incorporating robust security throughout the development and implementation process. Artemis possesses 
significant amounts of personally identifiable information (PII), as well as banking and financial information. Maintaining 
secure communication of client data is therefore a vital piece of the robust security needs of the company, in order to protect 
both client and company data.

  **Done well, importance of security**
  I beleive I did well at identifying security vulnerabilities and providing solutions such as the implementation of hash algorithms
to enhance security. Coding securely throughout the development process helps to ensure that not only is a secure program developed,
but also avoids delays or addition expenses involved with a developer or team having to go back afterward and refactor code to implement 
security as an after-thought. The protection of company and user data in a timely cost effective manner certainly adds to the company's
overall well being. 

  **Challenges**
  The biggest challenge I face with in developing the vulnerability assessment was sifting through the program provided to understand how 
it worked, especially how it interacted with different dependencies. Some dependency vulnerabilities identified applied only to the dependency 
when used in a certain way or configuration. Understanding if the app met that criteria helped to determine which vulnerabilities may be a non-issue.

  **Layers of Security**
  I increased the layers of security by implementing a certificate authentications process, as well as a SHE-256 hash algorithm to protect data. In 
the future I am likely to use the Oracle dependency checker again to assess vulnerabilities. The access to detailed informaton about identified
risks and previous breaches and methods can help to identify potential mitigation methods. 

  **Functional and secure**
  The first step in the process was to conduct a dependency vulnerability check before making any changes to the software. This allows the establishment
of a baseline. Once the code aas refactored to include the security elements added, I used a self signed certificate to ensure that the application 
would run and funtion successfully. Conducting a second vulnerability check after implementation of security provides a new report which is compared 
to the first one to see if anything new or different has emerged. 

  **Resources, tolls, coding practices**\
  I think the most important resources are those provided within the dependency check report. Understanding not only that a risk exists but also why 
it exists and how it works can make it easier to identify mitigation measures. Focusing on security at every stage of the development process is also a 
coding practice that I believe will be helpful in future assignments and tasks. 

  **Future Employers**
  In order to demonstrat my knowledge, skills and experience within this assignment, I would likely show future employers the code section where I implemented 
the SHE-256 cipher along with the successful output of the code. I believe this would demonstrate the understanding of and ability to implement ciphers 
effectively, while also demonstrating an ability to follow secure coding best practices.
