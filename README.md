Technical Summary

This is the second time I have used MuleSoft to design an Integration project, but this time I was more confident about the technology. I have used the tool to best of my knowledge, but there are still so much to learn and improvise in the code that I wrote.

Challenges faced during my journey.

1. Mule EE version 4.2.0 got deployed as default but had to downgrade it to 4.1.4 to run the Munit test cases.
2. Webservice endpoint provided by default was unavailable to had to use the docker image that got supplied with the exercise.
3. GetWeather response file had some extra CDATA element so had to fix that in the file to make it work.

Future version opportunities.

1. Implement the rest of the HTTP status code.
2. Write a comprehensive Munit test cases to test the code thoroughly.
3. Implement this service as a standalone one(easy to maintain) and remove the dependency of the SOAP webservice.

Setup Instruction:

Please follow the setup instruction section from the attached Technical requirement specification doc.
