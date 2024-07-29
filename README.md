# Web Applications :

    Web apps facilitate two-way communication between businesses and their customers. 

# Web Application Functions:
    Mostly the browser-supported languages are used to code the web applications like JavaScript and HTML.
    
    -> Client-side code: This code is localized in the browser that responds to the client’s input(JavaScript,HTML,css,ejs ...)

    -> Server-side code: this code responds to the requests made by the HTTP and is localized in the server.(Node,Java,Python, Ruby, PHP, etc...). 

# Components of Web Application Architecture:
    Web application consists of application components, databases, and middleware systems. The components of a web application architecture comprise of 

    
    1. UI/UX Web Application Components: These components include the activity logs, notifications, statistical data, dashboards, settings, etc. They are mostly used for laying the foundation of the web application and creating visuals. The components are not involved in any operation of the web-based applications.

    2. Structural components: The structural components of a web application include the client-side and the server-side. It includes the database server and the web application server.

    3. Client component: The creation of the client components requires the knowledge of JavaScript, HTML, and CSS. The operating system is not required as the components reside within the user’s web browser. It basically represents the functionality of a web application that the end-user interacts with.

    4. Server Component: Creation of the client components requires the knowledge of Java, .NET, Python, Ruby, PHP, and Node.js.  Two parts of the server components are app logic and database. App logic controls the web application while the database stores all the information.

# The components for building a web application can be chosen from the following models:

    1. One web server and one database: The most simple and the least reliable model of the web application are the one web server and one database.The reliability of such models is low as the web application built on such models goes down as soon as the server goes down. 

    2. Two web servers and one database: Web applications built over such models are quite reliable compared to the above- mentioned one due to the presence of a backup server. There is no storage of data in the webserver. The information received by the web server from a client is processed by the web server and written to the database. This database is managed outside the server. The model is also referred to as stateless architecture.

    3. More than two web servers and databases: One of the most efficient and dependable options for building an application is the model consisting of more than two servers and databases. The presence of more than one component avoids the problems associated with the failure of the web application.

# Scalability :
    Web development can become extremely challenging if you have a huge number of users visiting your site; the more people who visit, the more resources your web application requires. With server-side scripting languages, developers can quickly and efficiently handle complex tasks, such as data processing, database connection, file manipulation, memory storage, etc

# Security :
    A server-side scripting web framework or language offers an extra layer of security. In client-side scripting, it is relatively easy for someone with malicious intent to gain access rights and manipulate the source code since all the scripts are executed on the client’s web browsers. On the other hand, server-side script programming provides security protocols, like input validation and output encoding. Hence, developers hide sensitive information (Like database credentials) to prevent code injection attacks and unauthorized access

# Easy Maintenance :
    Server-side scripts are easy to maintain as they separate the web page and its content from programming functions. In essence, if developers need to make changes or updates to your web application, they do so on the server’s side. It means you do not need to update the client’s side of your application every time you make a change. Needless to say, it is a time- and effort-saver.

# Transaction Management :
    Some server-side scripting languages can handle transactions because they can execute multiple commands at once. Many programmers use this to create advanced database applications. You should consider whether it would be valuable for your site before you choose a particular language.

# Strong Community :
    Last but not least, most server-side languages have strong communities. Apart from the benefits mentioned above, you should find plenty of tutorials and documentation when choosing a language.


# Server-side Service:

  **Server Push**- HTTP/2 Server Push is an optional feature of the HTTP/2 and HTTP/3 network protocols that allows servers to send resources to a client before the client requests them. Server Push is a performance technique aimed at reducing latency by sending resources to a client preemptively before it knows they will be needed.

  **Nginx Service**- NGINX is open-source web server software used for reverse proxy, load balancing, and caching. It provides HTTPS server capabilities and is mainly designed for maximum performance and stability. It also functions as a proxy server for email communications protocols, such as IMAP, POP3, and SMTP.

   **Authentication service**- Server-side authentication takes place when the server provides certificates for authentication to the client.(JWT,oath) 

   **NPM** - npm is a package manager for the JavaScript programming language maintained by npm, Inc.,

   **PM2 serive** - PM2 is a daemon process manager that will help you manage and keep your application online 24/7 

   **Log Service** - Operations engineers and developers use logs for debugging. Product managers and UX designers use logs for planning and design. Marketers want to track the performance of various features that relate to advertising campaigns.

   **Middleware** - Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

   **Notification service** - A push notification (also known as a server push notification) is the delivery of information to a computing device from an application server where the request for the transaction is initiated by the server rather than by an explicit request from the client. While 'push notification' is most often used to refer to notifications on mobile devices, web applications also leverage this technology.

   **Database Service** - A database server is a server which uses a database application that provides database services to other computer programs or to computers, as defined by the client–server model.

   **Mailer Service** - MailerSend is a comprehensive tool for your everyday business: send invoices, delivery updates, and forgotten password links in seconds, without even thinking about it.

# Version control system: 
    Version control helps us to keep track of the changes we made in our code so that if something goes wrong, we can revert back to any previous version that we want. Without VCS it will be a very hectic work to keep track of the changes in our source code where multiple developers are continuously working on the same code.

    Version Control Software(VCS) is also known as Source Code Management(SCM) tools or Revision Control System(RCS) is a great fit for any web development company around the globe. 

# Git :
    Git is a free, cross-platform and open-source distributed version control tools available nowadays which provides strong support for non-linear development and is capable of efficiently handling everything from small to very large projects with speed and efficiency. Local branching, convenient staging areas, and multiple workflows are some important features of git.
    
    1. Super-fast and Cross-platform.
    2. Offline full history tree
    3. Distributed, peer-to-peer model
    4. Easy and clear track of code changes
    5. Cheap branch operations and robust.
    6. Amazing command-line as git bash.
    7. Complex and bigger history log becomes very hectic for single developer
    8. Not optima because it doesn’t support keyword expansion and timestamp preservation
    9. Provides Limited Windows support compared to Linux


# Concurrent Versions System (CVS) :# 
    CVS is another most popular version control system, an important component of Source Configuration Management (SCM) which remains the tool of choice among developers since 80s. You can record the history of sources files, and documents very easily with the help of CVS. It fills a similar role to the free software RCS, PRCS, and Aegis packages and handle conflicts between two programmers by only allowing for the latest version of the code to be worked on and updated.

    1. Matured technology with cross-platform support,
    2. Instant help and support from vast CVS community
    3. Robust and fully-featured powerful command-line
    4. Multiple developers might work on the same project parallel.
    5. Source corruption due to lack of support for atomic check-outs and commits,
    6. No integrity checking for source code,
    7. Poor support for distributed source control
    8. Expensive branch operations as it is not designed for long-term branching

# Apache Subversion (SVN): #
    It is a free and open-source software best-matched successor to the widely used CVS tool and was created as an alternative to CVS after fixing the bugs and cons of CVS system while maintaining high compatibility with it and that’s why Many developers switched to SVN for the best and improved features of CVS. 
    
    1. Supports atomic operations to prevent corruption
    2. Free-form versioned metadata
    3. Supports empty directories and cheaper branch operations
    4. Have better windows support as compared to Git
    5. Wide variety of plug-ins for leading IDE and Agile tools.
    6. Insufficient repository management commands and no support for signed revisions,
    7. Much Slower speed compare to git
    8. contains bugs relating to filename normalization and directories
