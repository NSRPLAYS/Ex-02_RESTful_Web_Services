# Ex-04_RESTful_Web_Services
## devoloped by: B.Naveen Sairam
## register no:212224240103
## Aim:

To create, deploy and execute RESTful Web service programs using Server, Client and Client-Side remote invocation
## Procedure:

### Server side:
Step 1: Create a new Java Web Project. Follow Steps 1-5 as in SOAP Based Web Service.
Step 2: Right-click on the project name and select New->RESTful Web Services from Patterns.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/33532201-41bc-428e-bba1-591657675980)

Step 3: A new window will appear. Select “Simple Root Resource” and click Next.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/68935d80-8bcb-4e17-a1af-902ffcbbf2bd)



Step 4: In the next window, give a Resource Package name and choose MIME Type as “text/html”. Click Finish.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/ea96e984-e6ef-40a8-aa61-92b6e3c76f7a)



Step 5: Two editing tabs will appear. Close “ApplicationConfig.java”. You need to write all your required functionalities in GenericResource.java.
Step 6: Alter getHtml() method as shown below.
Step 7: Save your project, clean and build it. Deploy your project.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/ddd95b3e-2fc1-475a-bde4-63e372744e07)

 

 


Step 8: To test your web service, open a new browser window/tab and type the URL as http://localhost:8080/project_name/webresources/generic?params=45&params=35 and hit enter. (This is the easiest way of testing the web service when it makes use of List).



Client-Side:


Step 1: Create a new Java Web Project. Follow steps 1-5 as in section 1.1.
Step 2: Right-click on the project and select New->RESTful Java Client.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/c0be4d54-32a8-4309-a248-e04485c2f016)





Step 3: A new window will appear. In that, give a name to your client, a package name and select “From Project” under the “Select the REST resource:” tab and click Browse. Step 4: Carefully select your RESTful resource (web service) and click OK.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/004b599b-4a60-456c-bf5e-353eae8789a5)

 
 


Step 5: Once everything is filled, the New RESTful Java Client window should look like this. Click Finish.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/b3f19adc-959c-4bcc-932a-c4ac885cce36)



Step 6: An editing tab will open. Alter getHtml() method with the following.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/bd18da6d-4e1b-4bb7-9037-2ecf3386667f)

 
 


Step 7: Right-click on the Libraries folder under your project and select “Add JAR/Folder”.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/e79968f8-13f0-42fa-9139-3c986e2b194a)


Step 8: A new window will appear. Navigate to the folder where you have placed the “javax.ws.rs-api2.0.1.jar” file and select Open.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/76a7ec59-892f-4281-a113-56b01f353395)

 
 


Step 9: Right-click on the Web Pages folder and select JSP. In the new window, give a name to the JSP page and click Finish.
Step 10: A new tab will appear with the default contents of the JSP page. In that, include at the top and type the following code to invoke the client java code.
![image](https://github.com/1808charitha/Ex-04_RESTful_Web_Services/assets/132996838/82a37c50-6d2b-4427-acff-e2849532f3a7)



Step 11: Save the project and build it.
Step 12: Run the JSP file and you should see the output in a new browser window.
 
 


Client-Side Remote Invocation:


Step 1: Follow steps 1-5 as in Section 2.2
Step 2: In the generated NewJerseyClient.java file, Replace BASE_URI from private static final String BASE_URI = "http://localhost:8080/RESTful_Server/webresources"; TO private static final String BASE_URI = "http://192.168.116.62:8080/RESTful_Server/webresources";
Step 3: Follow steps 6-12 as in Section 2.2


## Result:
 Thus, the RESTful web service program has been successfully created and executed.
