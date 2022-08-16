# CMPG-323-Overview-34855467
Project 1
this is is the intial understang of the semester project scope 
# Project respositories
Project 2 -> Project-2 repo
    <h1>API DEVELOPEMENT</h1>
    <h2>Repository name : API</h2>
    <p>the architectural style of REST will be used to completer this section of the semesters project .An API will seerve sa the communicate of to the seerver and frontend which would be done in project 2 .The API will be used as a data source to manage interaction with the data source</p>
    <h2>General requirements</h2>
    <p>The API should contain at least one get, post, patch and delete method per
resource – aligning to the project's requirements. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database. </p>
Project 3 -> Project-3 repo
    <h1>MVC Web Application</h1>
    <h2>Repository name : MVC Web Application</h2>
    <p>I believe a brief recap of the .Net Core programing language is required and that will aid vastly in the understanding of the preexisting project that we will be given and help advance in</p>
    <h2>General requirements</h2>
    <p>Functional requirements refer to the functionality that a system must have. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database.These non-functional requirements
are deemed as supportive requirements to ensure that the functional requirements are
implemented appropriately and according to good software practices. </p>

this project will have to connected to project 2 

Project 4 -> Project-4 repo
<h1>Robotic Process Automation (RPA)</h1>
    <h2>Repository name : Robotic Process Automation (RPA)</h2>
    <p>this project will be used to automate the functionalty of testing the user experience of the combine product of project 1-2 .This will help better understan to be cappablities and scalablity of the produict be realese into production and fined better ways to archieve the desied task  </p>
    <h2>General requirements</h2>
    <p>
    UiPath Automation Cloud account
    .Functional requirements refer to the functionality that a system must have. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database.These non-functional requirements
are deemed as supportive requirements to ensure that the functional requirements are
implemented appropriately and according to good software practices. </p>
Project 5 -> Project-5 repo
<h1>Power BI</h1>
    <h2>Repository name : Power BI reports </h2>
    <p>IN this phase of the project we willlbe  acquire and practise the necessary skills to create such a report , this will add use into aking more informed decisiions about how to optimize the product  </p>
    <h2>General requirements</h2>
    <p>
    UiPath Automation Cloud account
    .Functional requirements refer to the functionality that a system must have. The RESTful API architecture has several
endpoints called over HTTP, invoking application code to update a database.These non-functional requirements
are deemed as supportive requirements to ensure that the functional requirements are
implemented appropriately and according to good software practices. </p>

# Integration Diagram
<img src = "/diagram.jpg"></img>


# Braching strategy
I have chosen to use the Github Flow 
<img src = "/github-flow-branching-model.jpeg"></img>
<br>
Github Flow focuses on Agile principles and so it is a fast and streamlined branching strategy with short production cycles and frequent releases. 
it will allow for  testing and automating changes to a single branch instead of a development branch, rapid and continuous deployment is possible which will be very useful for the production of this whole . According to my research this branching stategy is suited small teams and web applications and it is ideal when you need to maintain a single production version.

# Purposose of.gitignore
<h1> These files will be .gitignored in alll repos</h1>
<p>. The .gitignore file commands instruct git which files (or patterns) to ignore. It's typically used to prevent committing temporary files from your working directory, including compilation products.</p>

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
# it’s better to unpack these files and commit the raw source
# git has its own built in compression methods
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
<p><link rel="stylesheet" href="https://gist.github.com/indyfromoz/4109296"></p>
<>

# Storage of credentials and sensitve information
<p>In thes projects the storage of information is very important and reuires for the encryption of user credetials so is to prvent user credetials be user by non user or atackes .The database aand API will require high level of encryption this from my researh we will need to utilze the concepts of  authentication,autherization.SO of the indutry trends is using JWT authentication which utilizes token to confirm user sessions on applications.Some libraies such as CryptoStream can be used to encrypt data the general flow of enrtyption should be as seen below</p>
<img src = "/secure data.png" ></img>
<p>Research on technique was done on the website below</p>
<link  href ="https://tudip.com/blog-post/how-to-securely-transfer-web-api-data-in-asp-net-core/">
