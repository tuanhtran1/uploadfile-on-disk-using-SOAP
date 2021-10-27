# uploadfile-on-disk-using-SOAP

This tutorial shows how we can send file using SOAP based webservice. The type of the file can be anything, i.e., text, image, pdf, MS doc etc. For this type of application we need to create two applications – one will work as a client application(which sends a file) and other one will work as a server application(which receives a file). So the server application will deploy the service whereas client application will consume the service. In server application we will have logic for what will be done with the file content after receiving the file. Using the client application we will upload the file and send through the SOAP service.

In this example both client and server applications are web based maven application. In client application we will upload the file using JSP, Servlet and send it to the server application which then saves the received file to the specific location on disk.

In this post we will use wsgen and wsimport through maven plugin to generate WSDL and stubs from WSDL, respectively.
