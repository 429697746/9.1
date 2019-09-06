# 9.1
1.	How to use 
Firstly open fount-end in the terminal				cd week5
														npm install
														ng s -o
then open back-end									cd week5
														cd src/server/
														node server.js
I got 3 account from week3 ,which is abc@com.au 123
										 abd@com.au	123
										 abe@com.au	123
 


2.	Git
I upload my work in the github, https://github.com/429697746/9.1.git
Git, at its core, simply stores key-value pairs. It allows the insertion of any type of content and returns a key value through which the content can be retrieved at any time.
Git stores data content in a way that generates a file for each content, gets the SHA-1 checksum of the content and header information, creates a subdirectory named after the checksum and the first two characters, and names the file with the remaining 38 characters (saved to the subdirectory).
 
3.	data structures
user: -user name (user have a defined name)
-user id(user have a id)
-user list(user have a list)
-user age(user have a age)
-user group number(user have a group number)
-user age(user have a age)
Group: -group id((group have a id))
-group belonging(group belong to)
Superuser: -superuser name(superuser have a name)
-superuser email(superuser have a email)
CICS supports two types of SCA applications: channel-based and XML-based, which can be invoked through EXEC CICS INVOKE SERVICE commands.

Interestingly, the Application Program Reference Manual (APRM) points out that programmers should use the INVOKE SERVICE command instead of INVOKE WEBSERVICE, which seems to be a signal that an XML-based service may be a superset or generalization of Web services. In fact, APG talks about binding Web services with Web services. Web Service Description Language (WSDL), which means that in SCA, when the domain is cross-platform, Web services fall into a special case of conventional services.

Channel-based services are very simple. SCDL defines what a container or COMMAREA looks like. Component implementation is the target program name. The caller uses the INVOKE SERVICE command to specify channels including input data, service URL, and service operation. After identifying services, CICS only needs simple links. To procedure.

XML-based services are more likely to act as Web services we have used. When callers call services, CICS passes information to requester and provider pipelines. If there is no defined pipeline for services, CICS temporarily assigns one. All information is transmitted along the pipeline. Common message processing programs control it as before. Finally, CICS calls the target program to perform business functions.

Memory Architecture: It mainly decides how the server uses memory to ensure that there is as little memory leak as possible, and maximize the use of server-side memory to increase load and reduce service latency.



Scheduling Architecture: Designing how to use processes, threads, and coroutines for CPU scheduling. Choose different programming models such as synchronization and asynchrony to improve the stability and load of the server. At the same time, we should consider the complexity of development. The emerging virtualization technologies, such as virtual machines, dockers, cloud servers, provide more choices for scheduling architecture.



Communication mode: Decide how to communicate. Network communication includes the choice of transport layer, such as TCP/UDP; the choice of expression layer, such as defining protocol; and the interface design of application layer, such as message queue, event distribution, remote call, etc.

Running methods and systems for display-based computer applications, which include multiple application segments, in which computing is allocated between servers and clients. The method includes the following steps: providing a general client engine to a client computer, which includes an application manager, one or more display managers, and one or more load managers; providing a set of definitions for each application subset related to one of the application segments; and When a continuous application subset definition file is received from the server, the client transforms recursively to provide the corresponding application segment. The invention is widely used in various display-based computer applications, especially in wireless applications.

In the context of a server-side web application, a routing system is the part of the web application that maps an HTTP request to a request handler (function/method). An HTTP request consists of a header and optionally a body. The header contains information about the request for example the method, path and host. Some methods like GET, HEAD, and OPTIONS do not make use of the request body while others like POST, PUT, and PATCH use it to pass data from a client to a server.



# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
