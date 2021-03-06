#Databases

NIST CPE Information: It is a database in which CPE information is stored.



Open Source Database: A database in which all the information about the project is stored.

Policy DB: Database that holds all policy information relevant to the project.

#Processes

National Vulnerability Database: A U.S. government repository for vulnerability data of software that enables risk, compliance and vulnerability managements.

Corporate Developer: An important stakeholder in the system who is responsible for managing code information by obtaining CPE 
information, CVE information and license information

Manage Code Information: Used to mange code information for license information.

License Scanner: Used to scan projects and files for licenses

Manage CPE Information: Process in which a file/packageis sent through to receive relevant CPE Information from the National Vulnerability Database.

Version Control/Build System: Process to allow the Corporate Developer to check in code.

Corporate Manager: One of the most important stakeholders in the system who is responsible for managing project information.

Manage Project Information: Process that allows the Corporate Manager to request Project file/package info.

Manage Policy Information: Allows the Corporate Manager to request relevant policy information about file/package

Online Repository: Website to post open source code back to. Could be a website such as github or Sourceforge.

Build Zip: Stores the Packages or files into a zip, for better organization.

Send Code to Website: Process that allows the Corporate Developer to post website to Online Repository.

#Data Flows

Document: Contains multiple packages 

File: A single file containing open source code

Package: Contains multiple files

License Info: Information about the licenses contained in a file/package.

Package Name: Name of the package that the Corporate Developer has submitted

CPE Info: File/package that contains all relevant CPE Info from the National Vulnerability Database.

CVE Info: Vulnerability info about the relevant CPE package.

File SHA1 Request: A request to generate a hash for a file/package.

File SHA1 Response: A response that is generated to confirm the presence of file that the developer is searching in the Open Source Database

Project File/Info Request/Response: Request sent by the Corporate Manager through the Manage Project Info process to allow the Manager to receive relevant Project Info.

Policy Info: Policy information requested by the Corporate Manager.

