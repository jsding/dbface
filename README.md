DbFace
===========
DbFace is an online software to help you creating chart reports & dashboards applications online. 
With the straightforward interface,users do not need to write PHP, HTML, CSS or other frontend/backend code to generate full featured query applications, operation
applications, and extensive report dashboard applications.

DbFace is a SAAS (Software as a Service) software, you do not need to download any software. Create an account online for free, and choose a subscription plan to use
all its features.

DbFace is coinages from Database + Face composed, meaning that it can be used as a pretty face for SQL database, can also be measing a database CMS program.


Getting Started
===========

Account is the only user credentials to enter DbFace system. The DbFace account is comprised of user name, password and e-mail address. Users can sign in DbFace through username or
e-mail address.

Create an account
---------------

Use the browser to open DbFace website(<a href="http://www.dbface.com">http://www.dbface.com</a>), click on "Create an Account" or "Sign Up" link to enter the account registration page.

<img src = "static/screenshots/english/register.png" />

In this page enter your email address , user name, password and confirm click on the "Create" button to create your DbFace account. Please make sure your email address is correct.
After the account is created, DbFace will send you a welcome message to your email, click the link in the email to activate your DbFace account.

You can also directly use Google or Facebook account to login (without registration and activation).

Account login
------------------

After the account is created, you can login DbFace system using your account. On DbFace website click on the "login" link to enter the login page. (If you choose the "Remember Password"
button, the system will record the encrypted account information in your current machine Cookie, in the next 30 days, open the landing page will automatically enter the system).

<img src = "static/screenshots/english/login.png" />

If you want to use Google or Facebook account to login, click the corresponding social login button without entering account information.

Modify account information
------------------

After entering DbFace, click the "user name" button in the top right corner of Home page, which pops up a small window that displays your current login user name and permissions.

<img src = "static/screenshots/english/loginuser.png" />

If you need to change your account information, click on "Settings" button to enter modify-account page that you can modify your user name, email address and
password.

<img src = "static/screenshots/english/editprofile.png" />

If you don't need to change your password, please leave it empty.

Subscription Plans
------------------

According to the user's needs, DbFace supports four types of subscriptions and up to 30-day trial period. You can upgrade or downgrade your account.
#### Personal (Personal Edition)
Contains one sub-account, create one database connection and up to 20 applications most.
#### Standard (Standard Edition)
Contains five sub-account, create up to three database connections, and 100 applications most.
#### Plus (Extended Edition)
Plus version does not limit the number of sub account, or the number of database connections and applications.
#### Pro (Professional Edition)
On the basis of the Plus version, the user can modify the application Logo and Custom DNS.

Click on "Settings" button in current window, select the "subscription" tab, enter the subscription page. On this page, you can view your current subscription/trial
status and expiration date, you can also renew or modify subscription.

<img src = "static/screenshots/english/editsubscribe.png" />

<strong> Note: This page might be different depending on your region. </strong>

Cancel Account
------------------

If you do not want to use the information to try DbFace service, you can cancel your account, please note that the cancellation account, you saved on the server will be fully DbFace
Deleted and unrecoverable, <strong> please use caution. </strong>

To cancel an account, we invite you to give us feedback so that we can improve our products, and hope to get your favor again.


Sub Account
===========

You can create a subsidiary account for DbFace account. DbFace offers two sub-account privileges: developer account with the user account.
#### Developer Account
Developer account can access all applications under your account, and can create new applications, modify / delete existing applications (himself or someone else created). Developers can not account
Management database links and sub-accounts that require administrator privileges to enable the feature.

#### User accounts
User accounts can only access the application of its open permissions.

Create a sub-account
---------------

To create a sub-account with Administrator account login DbFace. Find the "Sub Account" page in the console area, this area shows a list of the current sub-account under your account.

<img src="static/screenshots/english/subaccountlist.png" />

Click on "Create sub-account" button to enter the sub-account creation page.
<img src = "static/screenshots/english/createsubaccount.png" />

On this page, enter the correct child account information, after the submission page will jump to the sub-account list page, you will find the sub project account you just created. This account can now
To the developer or user login DbFace the system.

Edit sub-account
---------------

Log on as Administrator DbFace systems, home to find the "sub-account" area, click on the Edit button in the list of items to enter the sub-account to edit this page.

Delete Sub Account
---------------

Log on as Administrator DbFace systems, home to find the "sub-account" area, click on the list of items the Delete button to delete this sub-account.

Database Connectivity
===========
DbFace applications need to get data from your database, and then follow the instructions to use the display or operating data, so DbFace need to know the address you need to manage and access the database
Account number.

Create a database connection
---------------
To create a connection to your database, an administrator account login DbFace, find the database connection in the home area, here will show that you have currently created a database connection
List.

<img src = "static/screenshots/english/connectionlist.png" />

Click "Create a database connection" button to create a database connection to enter the page:

<img src = "static/screenshots/english/createconnection.png" />

* Database Type: The type that you want to connect to the target database, the current version supports MySQL
* Name: DbFace used to identify the name of this connection (not the database name)
* Connection address: Your IP address or domain name database, if you do not use the default port, to IP: port to fill the form
The user name used to access the database server: * Username
* Password: The password used to access the database server
The database name to connect to: * Database name

To ensure that all information is complete, click submit, will try to create this database connection.

<strong> Please update your server's firewall to allow DbFace IP connection to your server. Specific settings way, please contact support. </strong>

Edit Database Connection
---------------
An administrator account login, at home to find the "Database Connection" area, click on the Edit button to edit the database connection project, and enter the database connection edit pages.
A description of each reference to create a database connection.

<Strong> Be careful: Do not modify the database name, all applications use this database connection error may occur </strong>!


Cancel a database connection
---------------
An administrator account login, at home to find the "Database Connection" area, click the Delete button to delete a database connection project will confirm to delete the database connection.

<strong> Be careful: Deleting a database connection will delete all applications use this database connection </strong>!

Table of Contents
===========
DbFace apply to all forms of organization within the account directory (ie, the left side of the console under the menu item). Included by default "Application" directory, create an application, if
Directory where the application does not specify, are automatically attributed to the default directory.

Create a directory
---------------
An administrator account login, find the "directory" area in the home, this area displays the current directory listing all accounts

<img src = "static/screenshots/english/folders.png" />

On this page, enter the directory name, and make sure the "Create a new directory" button to create this directory. Directory names are not easy to duplicate.

For convenience, when creating or editing applications, but also provides the option to create a directory. So that you can use when you create, together to create this application for a directory name.


Edited directory name
---------------
In the directory list area, click on the name, directory name will pop up a small window to modify, enter the new directory name, make sure you can modify the directory name.
<img src = "static/screenshots/english/editfoldername.png" />

Delete the directory
---------------
To delete a directory in the directory list area, click the item you want to remove the back of the Delete button. Please be assured, does not remove the directory and delete applications, apply all of this directory
Will automatically move to the default directory (Application) inside.

Application
===========
Application is the core of the concept DbFace. The DbFace application refers DbFace an available execution units, could be a database query / operator, a form reports, summary reports, line graph,
Pie and so on.

Typical applications include a support <strong> user input form (optional), one or more of the execution of the script </strong>. When the user data entry form, click on the form submit button, DbFace will
Script data entered by the user and application execution, submitted to the final database to perform the type of output data and press the corresponding application (such as data tables, summary tables, pie charts,
Linear maps, etc.). Dashboard application is a special type of application, it can be supported by the application DbFace displayed in a page.

DbFace supports the following application types:
Query Application
---------------
Query application that is launched on the target database application type query operation.

Typical applications include a user query DbFace input forms, queries script. Enter the user completes the form, click on the form's "submit" button, DbFace the implementation of the joint
User inputs and generates a query script, made the final query results, according to the output format of the output for the query application form, summary tables, line graphs, pie charts or digital report.

DbFace application provides two ways to create a query: drag mode and script mode.

* Drag Mode: The user can choose to query (connect) to query the table, DbFace will display the available fields, the user will drag it to the corresponding field position corresponding to generate a query applications.
* Script mode: direct user input to retrieve SQL scripts (scripts can use the user form variable), generate a query applications.

#### Table view report
Table view displays the data in rows and columns in the form of a report, which is the easiest way to show the data.

<img src = "static/screenshots/english/queryapp_tabular.png" />

#### Summary View Reports
Summary Report is the same structure, the data of multiple different statements to the corresponding cell's data add up.

<img src = "static/screenshots/english/queryapp_summary.png" />


#### Table Editor
Database table editor provides original form CRUD (create, update, delete), filtered, paging and other functions.

<img src = "static/screenshots/english/queryapp_tableeditor.png" />

DbFace built-in table editor and powerful:

* Data for tabbed browsing
* Press the field (multi-column sorting)
* Delete the line
* Open line editor
* Increased line: the user selects a single row of data, then open the line editor, will be selected row data is automatically copied to the editor, a very convenient
* Filtering data capabilities by field, click the Filter button to open the filter conditions Editor

#### Line chart

<img src = "static/screenshots/english/queryapp_linechart.png" />

#### Pie

<img src = "static/screenshots/english/queryapp_piechart.png" />


Histogram ####

<img src = "static/screenshots/english/queryapp_columnchart.png" />

Lateral histogram ####

<img src = "static/screenshots/english/queryapp_barchart.png" />

#### Bitmap

<img src = "static/screenshots/english/queryapp_scatterplot.png" />


#### Area chart

<img src = "static/screenshots/english/queryapp_areachart.png" />


#### Figures reported

<img src = "static/screenshots/english/queryapp_numberreport.png" />


General application database operations
---------------
DbFace application database operations can be completed action on any SQL database support (requires a database user support). With the help of the form below, you can create a user
Data input data insertion, modification, deletion, for example, you can perform database repair table tablename sort of maintenance operations.

General database applications typically operate by <strong> User input form (optional), to confirm the information, execute script </ strong> components.

DbFace displayed first initialize and display the user input form, the user enters information form submit button clicked, will display a confirmation message (confirmation message can contain input data),
Click on the OK button to confirm the information area, DbFace the script line by line execution of the application, and the final results of the implementation.

DbFace try to perform all transactions in the form of scripts, all scripts are executed only before the final submission of all executed, otherwise it will all be rolled back (need database transaction support).

HTML Reporting Application
---------------
DbFace provides a full-featured HTML editor (CKEditor), users can freely edit the content, and support the insertion of SQL queries to the compilation.

DbFace dynamic query script and display the HTML report content editing.

Dashboard application
---------------
Dashboard application may be the above-mentioned three types of application seamlessly integrated into a single page. DbFace provide complete layout editor that allows users to drag and drop existing applications to the layout.

Application Editor
---------------
DbFace unique understanding of database applications and simplify the process of creating it is very simple and efficient.

### Basic Information

<img src = "static/screenshots/english/appbuilder_name.png" />

* <Strong> Database Connection </strong>
This application database used for data connections. Creating / editing application must first determine a good database connection.

* <strong> Name </strong>
Identify the name of the application, the application displays the user's name in the menu

#### Published

<img src = "static/screenshots/english/appbuilder_publish.png" />

* <Strong> Save Draft: </strong>
The application is saved as a draft, save it as a draft of the application does not appear in the menu bar on the left side.

* <strong> Preview </strong>
Creating / editing application, the actual display preview applications.

* <strong> publish </strong>
Application testing is completed, the application delivery to all users.

### Form Editor
DbFace integrated drag and drop form editor, assisted generate the user interface. Form Editor, there are two types of controls: the layout of the controls and form controls. <strong> all form controls must
Placed in the layout of the controls inside. The first step to create a form that is dragging a layout control to the editor. </strong>
<img src = "static/screenshots/english/appbuilder_formbuilder.png" />

### Display Format
<img src = "static/screenshots/english/appbuilder_listtype.png" />

Select the application you want to create a query data display format.

### Data Sources
<img src = "static/screenshots/english/appbuilder_datasource.png" />

Select the application to use the data table, DbFace allow multiple tables joint inquiry.

### Towed Report Builder

<Img src = "static/screenshots/english/appbuilder_dragdrop.png" />

### Application Properties

<img src = "static/screenshots/english/appbuilder_options.png" />

### Application Catalog

<img src = "static/screenshots/english/appbuilder_folder.png" />

### Application user permissions

<img src = "static/screenshots/english/appbuilder_subaccount.png" />

Application user permissions to display all sub user accounts under your account (developer account has permissions to all applications). Check the user has access.

### Application Script Editor
<img src = "static/screenshots/english/appbuilder_script.png" />

### Application confirmation
<img src = "static/screenshots/english/appbuilder_confirmmessage.png" />

### HTML Report Editor
<img src = "static/screenshots/english/appbuilder_htmlreport.png" />

### Dashboard Editor
<img src = "static/screenshots/english/appbuilder_dashboardbuilder.png" />

Management applications
---------------
Administrator or developer account Login DbFace, first display the list of applications. This list provides functions to edit or delete applications.

Edit #### applications
In the application list, select the application you want to edit, click the "Edit" button to enter the edit page, edit the application is not allowed to modify the data source. Edit mode applied reference
Application Editor.

#### Remove applications
In the application list, select the application you want to delete, click the "delete" button, after application to confirm the deletion.

Forms
===========
DbFace support to the application to specify the form to create a query or operation of the application supports user input. DbFace There are two major types of form controls: control layout and form controls.
<strong> all form controls must be placed on the layout of the controls. </strong>

<img src = "static/screenshots/english/formbuilder_ani.gif" />

Forms project
---------------
* Single line input box (Single Line)

Single line input box allows the user to enter a single line of string data, the user can specify the data type in the property editor. If you specify a data type, before submitting the form, it will check the input items
Whether the specified type, if not, the form will not be submitted.

<img src = "static/screenshots/english/formbuilder_datatype.png" />

* Multi-line input box (Multi Line)

Multi-line input box allows the user to enter multiple lines of text.

* Drop-down box (Drop down)

Drop-down box allows the user to a list of values, select a data. Drop-down box to specify the data source.

* Single box (Radio Group)

Single box displays a list of all the values, and allows you to select one as the form data submitted.

* Checkbox (Checkbox)

Check box displays a list of all the values, and allows users to check multiple data submitted.

* Multi-box (Multi Select)

Check box displays a list of all the values, and allows the user to select multiple values ​​submitted.

* Static Label (Static Label)

Static label display static data can not be edited.

* Text (Text)

The text can be described as a form content. DbFace integrated CKEditor support rich text editing.

### Project Properties
To edit the project properties, click on the Edit button Forms project, open the property editor.

#### Label
Notes that the project in front of the text items that can be used to identify the user of this form projects.

#### Name
Forms project internal name that can be used as variables in the script. Such as: {$ status}

#### Must be entered
This project must be entered before running submission will check whether the value of this project is empty, if allowed to be empty, the form and submit.

#### Disable
This item can not be edited. Users can not edit this item.

#### Data Sources
Only limited value items (such as drop boxes, check boxes, check boxes, etc.) have a data source options. DbFace support direct input value with the specified script are two ways to use the data source (no limit
Generally used for script preview, practical applications are generally not used).

* Direct input values: the user to directly input data source, one per line value. Enter a value to support key: value segmentation format, DbFace if this format is detected automatically:
Value as a form before submitting value, the latter value data as displayed in the form inside. <strong> Do not forget to use the data selector to assist in helping to select the data from the database. </strong>

* Scripts: Users can use a query to set the data source.


#### Project to modify the script
Project modify the query script in the user input is complete, remove the focus is the implementation and results of the implementation-one mapping to the current form control.

Script
===========
DbFace using Smarty template engine to achieve extended SQL script functions to achieve the user can dynamically insert a form based on the input variables and functions in dynamic SQL rewrite the script.
All scripts before submission to the database, it sends the current form of value, replace the contents of the script variables.

<strong> form variable values ​​can be applied to the script. </strong>

Suppose an application form report query script:
```sql
select OrderData, Status, ColumnName from Orders where Status = {$status}
```

Users have a project called status form, the user input (select) the value Shipped, then the final query would be:
```sql
select OrderData, Status, ColumnName from Orders where Status = `Shipped`
```

The final statement may vary depending on the choice of different data sources.

<strong> SQL injection here do not worry, all the items will be filtered value of special characters. </strong>

<strong> script can also be used in the query application dragging mode, the value for the filter condition, can also use {$ status} variable syntax, </strong> for example:

<Img src = "static/screenshots/english/using-form-variable-in-drag-drop.png" />

About advanced usage of the script, please refer to the documentation Smarty template.

Form script
---------------

### Form variables used in the script
Depending on the control, form controls may output two types of data: a single value, a list of values

* <strong> single value: </strong> single line of text, multiline text, drop-down boxes, radio buttons submit only one value

Use single value <strong> $ {project name} </strong> style into the script, consider a name for the status of a single line of text, can be in the form {$ status}
Inserted into the filter condition or application scripts. Such as:

```Sql
select orderDate, status where status = '{$status}'
```
<strong> Please note that in quotes, including this variable, DbFace when parsing script, will not determine the type of the field plus the value of quotes. </strong>

* <strong> multiple values: </strong> checkbox checkbox will submit multiple values

Multi-value filter is used in the control condition, the same single value, meaning that matches one of the conditions is met.

Multi-valued control is used in script mode, there are different, such as the search condition
```sql
... Where status = '{$status}'
```
Will not retrieve the data, because {$status} is an array, will be forced to be converted to a string 'Array', the correct usage should be:
```sql
... Where status in ({$status|join})
```
{$status | join} syntax is automatically launched and this segmentation value.

### Data Source script

Limit values ​​for certain form controls, such as drop-down box (DropDown), checkbox (Multi Select), checkbox (Checkbox), single box (RadioGroup), you can use
Data source scripts to specify its limits when DbFace application execution, data sources dynamically execute a script to get the value of a form control.

Data source scripts can output one or two fields, the remaining fields will be ignored.

If there are two fields: the contents of the first field as submitted values ​​(data applications in the script), the second field as the displayed values ​​(data is only for show).

As
```sql
select value from table where ...
```
Or
```sql
select key, value from table where ...
```
To use the data source scripts, click Forms controls limit the "Edit" button in the pop-up window project edit box, click on the "script", "Data source script," the
Enter the text box, enter the data source script, save it.

<img src = "static/screenshots/english/script_datasource.png" />

<strong> Do not forget to use the data source script generator, click on the "script" generator behind the icon will pop up all the tables and fields of the current link, check the required fields to generate
Query this field. </strong>

### Forms project to modify the script
Forms project after the modification is completed, you can set a query script. When the user input is complete, after the focus away from the edit control, the script will automatically execute and get the final database
Data, will get one mapping field names to the current set of form controls.

To use the program to modify the script, click on the Edit button in the project, the project properties in the edit box that pops up, click on the "Modify scripting", launched in the text box, enter the script is saved
Can be.

<strong> Forms project to modify the script you can use the current variable form. </strong>

<img src = "static/screenshots/english/script_onchangescript.png" />

### Form load script

Users can specify a load script form (query) data is used to initialize the form's controls.

After opening the application, DbFace will detect whether the current load scripts using the form, if so, will automatically execute this query script and query results to-one mapping to the current form. In case
Returns the number of data query script, DbFace provide the Browse button, you can select the data required for use for the value of a form control.

To create a form to load the script, click the Form Editor "Properties" button to bring up the properties of the edit box, enter the script is loaded, you can save.

<img src = "static/screenshots/english/form_loadingscript.png" />

Gadgets
===========
DbFace integrates many gadgets to user-friendly operation, enhance the user experience.

Query Builder script
---------------
Query script generator to help users generate a simple query script that can be used to load the script form, form controls and data source controls to modify the script and other scripts. Users click Search
Script Generator icon will pop up the data fields of the current table and each table is linked.

<img src = "static/screenshots/english/scriptgenerator.png" />

Expand the need to generate data tables, check the fields required to generate unique data script for this field.

<img src = "static/screenshots/english/scriptgeneratorresult.png" />

Data selector
---------------
When users select the data with the help of the data table can be opened directly, select the required data, such as creating a form, select the data source for the field data.

* Click on the Data Selector icon will pop up the data table and field current link

<img src = "static/screenshots/english/dataselector_step1.png" />

* Check all options need to get the field

<img src = "static/screenshots/english/dataselector_step2.png" />

* After confirmation, will return the data copied to the current editor

<img src = "static/screenshots/english/dataselector_step3.png" />

Data filters Editor
---------------
In the application dragging mode and form editor, DbFace integrated data filters easy to use editor to help users generate data filtering criteria.

* Filtering criteria used in the query editor to create the application

<img src = "static/screenshots/english/filtercondition.png" />

* Filter conditions in the form editor application editor

<img src = "static/screenshots/english/filtercondition_tableeditor.png" />


Integrate
===========
By embedding applications, you can embed in a report or application DbFace created on your other sites, without having to log DbFace systems.

Embedded applications
---------------
An administrator or developer account login DbFace, in the area of ​​Home application list, click Apply to project the "Embed" button will pop up wizard to embed this application form:

<Img src = "static/screenshots/english/embed.png" />

#### Gets embedded address
Please copy them directly embedded IFRAME code to your address or third-party web page, and select the "embedded" check box, you can use this embedded address confirmation.
<strong> Be sure to select the "Embed" box, and save, or this address will not take effect. </strong>

#### To cancel the external access
If you want to cancel the function of external access to applications, please use the list in the Home area, click Apply to project the "Embed" button, cancel the "embedded" check box selected,
And save.

Cancel embedded and external display applications can not access the message exists.


Security
===========
Security is especially important for database applications. If you do not need to change the operating data, please create a database connection when using the library read-only account, instead of using
root. DbFace taken some measures to prevent access to your link is invalid.

Whitelist
---------------
If your IP is a fixed or fixed range, it is recommended that you set the IP whitelist. After setting the white list, the non-white list IP addresses access to your account or sub-account will be rejected.
To set or modify the whitelist, please log in as an administrator, the current user information click on the small window in the upper right corner of the "Settings" button to open the "System Settings" tab,
Fill IP whitelist, save the changes take effect.

<img src ="static/screenshots/english/ipwhitelist.png" />

<strong> If you are not careful your IP settings to whitelist outside, please contact support@dbface.com, confirming your identity, it will reset your whitelist information as soon as possible. </strong>


Read-only mode
---------------
If you just create a data query application, please use the permissions for specific library database user name.
  
Frequently Asked Questions
===========

Revision History
===========

Statement
---------------

© 2014-2015, DbFace Co, LTD.

** DbFace ** is authored and maintained by DbFace Co, LTD.

 * [Website] (http://www.dbface.com) (www.dbface.com)
 * [Support] (http://www.dbface.com/support) (www.dbface.com/support)

