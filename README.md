# CMPG-323-Overview-34855467
Project 1
This is the initial understang of all the semester projects and the scope they require. 
# Project respositories
Project 2 -> Project-2 repo
    <h1 style  =  "color:green">API DEVELOPEMENT</h1>
    <h2>Repository name : API</h2>
    <p>The architectural style of REST will be used to complete this section of the semester project . An API will serve to communicate between the server and frontend, which would be done in project 2 . The API will be used as a data source to manage interaction with the data source.</p>
    <h2>General requirements</h2>
    <p>The API should contain at least one get, post, patch and delete method per
resource – aligning to the project's requirements. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database.Entity frame work will be require for the creation of the API and reqired to use  .NET Core 3.1 </p>
Project 3 -> Project-3 repo
    <h1>MVC Web Application</h1>
    <h2>Repository name : MVC Web Application</h2>
    <p>I believe a brief recap of the.Net Core programming language is required and that will aid vastly in the understanding of the preexisting project that we will be given and help advance it. </p>
    <h2>General requirements</h2>
    <p>Functional requirements refer to the functionality that a system must have.  </p>

this project will have to connected to project 2 

Project 4 -> Project-4 repo
<h1>Robotic Process Automation (RPA)</h1>
    <h2>Repository name : Robotic Process Automation (RPA)</h2>
    <p>This project will be used to automate the functional testing of the user experience of the combined product of projects 1-2 . This will help better understand the capabilities and scalablity of the product being put into production and find better ways to achieve the desired task.</p>
    <h2>General requirements</h2>
    <p>
    UiPath Automation Cloud account
     </p>
Project 5 -> Project-5 repo
<h1>Power BI</h1>
    <h2>Repository name : Power BI reports </h2>
    <p>In this phase of the project, we will acquire and practice the necessary skills to create such a report. This will be useful in making more informed decisions about how to optimize the product.</p>
    <h2>General requirements</h2>
   
# Integration Diagram
<img src = "/diagram.jpg"></img>


# Braching strategy
I have chosen to use the Github Flow 
<img src = "/github-flow-branching-model.jpeg"></img>
<br>
Github Flow focuses on Agile principles and so it is a fast and streamlined branching strategy with short production cycles and frequent releases. 
it will allow for  testing and automating changes to a single branch instead of a development branch, rapid and continuous deployment is possible which will be very useful for the production of this whole . According to my research this branching stategy is suited small teams and web applications and it is ideal when you need to maintain a single production version.

# Purposose of.gitignore
<h1> These files will be .gitignored in all repos</h1>
<p>. The .gitignore file commands instruct git which files (or patterns) to ignore. It's typically used to prevent committing temporary files from your working directory, including compilation products.</p>

# File extentions
*.com
*.class
*.dll
*.exe
*.pdb
*.dll.config
*.cache
*.suo
# Include dlls if they’re in the NuGet packages directory
!/packages/*/lib/*.dll
!/packages/*/lib/*/*.dll
# Include dlls if they're in the CommonReferences directory
!*CommonReferences/*.dll
####################
# VS Upgrade stuff #
####################
UpgradeLog.XML
_UpgradeReport_Files/
###############
# Directories #
###############
bin/
obj/
TestResults/
###################
# Web publish log #
###################
*.Publish.xml
#############
# Resharper #
#############
/_ReSharper.*
*.ReSharper.*
############
# Packages #
############
*.7z
*.dmg
*.gz
*.iso
*.jar
*.rar
*.tar
*.zip
######################
# Logs and databases #
######################
*.log
*.sqlite
# OS generated files #
######################
.DS_Store?
ehthumbs.db
Icon?
Thumbs.db
[Bb]in
[Oo]bj
[Tt]est[Rr]esults
*.suo
*.user
*.[Cc]ache
*[Rr]esharper*
packages
NuGet.exe
_[Ss]cripts
*.exe
*.dll
*.nupkg
*.ncrunchsolution
*.dot[Cc]over
<p> Reaserch source found at  https://gist.github.com/indyfromoz/4109296
</p>

# Storage of credentials and sensitve information
<p>In these projects, information storage is critical, and encryption of user credentials is required to prevent user credentials from being used by non-users or attackers. From my research, the database and API will require a high level of encryption. From my research, we will need to utilize the concepts of authentication,autherization.One of the industry trends is using JWT authentication, which utilizes tokens to confirm user sessions on applications. Some libraries, such as CryptoStream, can be used to encrypt data. The general flow of encryption should be as seen below.</p>
<img src = "/secure data.png" ></img>
<p>Research on technique can be found at https://tudip.com/blog-post/how-to-securely-transfer-web-api-data-in-asp-net-core/</p>
href ="">
<br>
<br>
<h1>The burndown chat is located in the .xlsx file int this repository</h1>
