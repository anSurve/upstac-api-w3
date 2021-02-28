<h2> UPSTAC </h2>

This repository contains the backend java code of the UPSTAC application.

<h3> What is UPSTAC app? </h3>
<p>UPSTAC is a web based app which facilitates users by allowing them to order various tests. These tests are performed by the govt. authorised testers.
After tests are done govt. authorised doctors provide consultation remarks on the tests performed by the testers. The most most important thing of all this is,
the entire process does not include any physical contact of any of these people(doctors, testes and patient).</p>
<p>The test samples are collected by lab executives. They visit the patients and gather the test samples in sealed containers and hand them over to the testers.
Tester then perform the tests and update the results into the UPSTAC portal.</p>
<p>Doctors come into picture after this. Doctors can see the test results. They can pick the test results for themselves and update the consultation remarks for the 
various tests.</p>
<p>Meanwhile patient can see the progress of his test request and after doctor and tester update their remarks, patient knows the test result.</p>
<p>Govt. authorities are also granted the login to this portal. They are authorised to see all test results. This is very crucial in the current scenario such 
as COVID19. Where govt. needs to know the exact number of affected people and accordinly it can enforce the lockdown in that particular are based on the spread of
the virus/bacteria.</p>
<br>
<h3> Prerequisites </h3>
<p>This app is using mysql in the backend. You need to install mysql.</p>
<p>After mysql installation create user and set the password. After that create a database - upgradpg</p>
<p>After all the above things are done, you need to edit <b>application.properties</b> residing in <b>/src/main/resources</b> <br>
Edit this file so as to provide your datasource username, datasource password and datasource url.</p>
