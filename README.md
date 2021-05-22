# Bugs
owns bugs
ID	 	Description	Steps to reproduce	Severity	Priority	Reproducibility	Symptom	Workaround	Attachment	Status
MM-1/0	When opening the login form, the fields moved to the right and left	"When opening the login form, the fields moved to the right and left
Precondition: Open the form of registration like a Trainer.
"	"1. Fill in all required fields valid values. 
2. Click the ""Registered""."	Minor	Low	Always	Cosmetic flaw			
MM-01/01	Small buttons size, text does not fit into the button field in the main page.	"""To Register"" and ""Edit profile"" buttons when localizing into russian have small size therefore text doesn't fit into the the button field.
Precondition: open main page.
Act: "" To Register"" and ""Edit profile"" buttons are small, text doesn't fit into the button field.
Exp: ""To Register"" and ""Edit profile"" buttons are normal, fit into the button field."	1) Open the main page	Minor	Normal	Always				New
MM-1/1	If you enter 1 symbol in the "First Name" field, fill in all required fields, the "Registered" button is access. 	"If you enter 1 symbol in the ""First name"" field, fill in all required fields, the ""Registered"" button is access. 
Precondition: Open the form of registration like a TPrecondition:rainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter 1 symbol the ""First name"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/2	If you enter 1 symbol in the "Last Name" field, fill in all required fields, the "Registered" button is access. 	"The ""Registered"" button is access if you enter 1 symbol in the ""Last Name"" field, fill in all required fields  
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter 1 symbol the ""Last Name"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/3	If you enter 26 symbol in the "First Name" field, fill in all required fields, the "Registered" button is access. 	"If you enter 26 symbol in the ""First Name"" field, fill in all required fields, the ""Registered"" button is access. 
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter 25 symbol the ""First name"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/4	If you enter 51 symbol in the "Last Name" field, fill in all required fields, the "Registered" button is access. 	"If you enter 51 symbol in the ""Last Name"" field, fill in all required fields, the ""Registered"" button is access. 
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter 51 symbol the ""Last name"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/5	If you enter  numbers and speсial symbols in the "First Name" field, fill in all required fields, the "Registered" button is access. 	"The ""Registered"" button is access if you enter numbers and speсial symbols in the ""First name"" field, fill in all required fields. 
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter numbers and speсial symbols the ""First name"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/6	If you enter  numbers and speсial symbols in the "Last Name" field, fill in all required fields, the "Registered" button is access. 	"If you enter numbers and speсial symbols in the ""Last name"" field, fill in all required fields, the ""Registered"" button is access. 
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter numbers and speсial symbols the ""Last name"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/7	If you enter 1 symbol in the "Password" field, fill in all required fields, the "Registered" button is access. 	"If you enter 1 symbol in the ""Password"" field, fill in all required fields, the ""Registered"" button is access. 
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter 1 symbol the ""Password"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-1/8	If you enter 16 symbol in the "Password" field, fill in all required fields, the "Registered" button is access. 	"If you enter 16 symbol in the ""Password"" field, fill in all required fields, the ""Registered"" button is access. 
Precondition: Open the form of registration like a Trainer.
Act: The ""Registered"" button is access. 
Exp: The ""Registered"" button is not access. "	"1) Enter 16 symbol the ""Password"" field. 
2) Fill in all required fields valid values."	Minor	Low	Always	not equivalent value	No		
MM-2/1	In the Trainer's registration form, after filling in the "Last Name" field, you cannot go to the "Email" field using Enter.	"In the Trainer's registration form, after filling in the ""Last Name"" field, you cannot go to the ""Email"" field using Enter.
Precondition: Open the Trainer's registration form.
Act: The register appears in the ""Password"" field
Exp: The register appears in the ""Email"" field"	"1) Fill the ""Last Name"" field.
2) Press Enter on your keyboard."	Minor	Low	Always	unexpected behavior	Click on the Email field 		
MM-2/2	"Log in"  button is accessible if do not fill "Password" fields in Login form.	"""Log in""  button is accessible if do not fill  ""Password"" fields in Login form.
Precondition: Fill the form of registration like Treiner valid values and click the ""Registered"" button. You redirect to Login form.
Act: ""Log in""  button is accessible.
Exp: ""Log in""  button is not accessible.
"	"1) Do not fill ""Password"" fields in Login form.
2) Click the button ""Log in"".
3) The message is appier ""Please enter a password""."	Major	Normal	Always	Non-compliance with requirements			
MM-2/3	"Log in"  button is accessible if do not fill "Email" fields in Login form.	"""Log in""  button is accessible if do not fill  ""Email"" fields in Login form.
Precondition: Fill the form of registration like Treiner valid values and click the ""Registered"" button. You redirect to Login form.
Act: ""Log in""  button is accessible.
Exp: ""Log in""  button is not accessible.
"	"1) Clean ""Email"" fields in Login form.
2) Click the button ""Log in"".
3) The message is appier ""Please include an email""."	Major	Normal	Always	Non-compliance with requirements			
MM-4/1	If you enter 1 character in the field "Name of group" , the form skips and creates a group	"If you enter 1 character in the field ""Name of group"" , the form skips and creates a group, the min number of characters in the field ""Name of group"" is 2
Precondition: As a Trainer create group.
Select the tab "" Create group"", enter the field ""Name of group"" with 1 value, chose type and press ""OK"" button.
Act: the group are created.
Exp: the group are not created."	"1) Select the tab ""Create group"".
2) Fill the field ""Name of group"" with 1 value.
3) Chose type.
4) Press the ""OK"" button."	Minor	Low	Always	not equivalent value	No		
MM-4/2	You can enter only 8 characters in the "Name of group" field.	"You can enter only 8 characters in the ""Name of group"" field when the max number of characters in the field ""Name of group"" is 20.
Precondition: As a Trainer create group.
Select the tab "" Create group"", enter the field ""Name of group"" with 20 value, chose type and press ""OK"" button.
Act: You can enter only 8 characters in the ""Name of group"" field.
Exp: Enter 20 charaters in the ""Name of group"" field and create the group with pressing the ""OK"" button."	"1) Select the tab ""Create group"".
2) Fill the field ""Name of group"" with 20 values."	Major	High	Always	not equivalent value	No		New 
MM-4/3	You can add the same mentee an unlimited number of times	"You can add the same mentee an unlimited number of times in the ""Select mentee"" field at Include Participants
Precondition: As a Trainer to include participants.
Select the tab ""Include Participants"", fill the ""Select mentee"" field with same mentee two or three times
Act: added same mentee unlimited of times
Exp: can't add same mentee"	"1) Select the tab ""Include Participants"".
2) Select group in drop-down list.
3) Select mentee in drop-down list.
4) Press the ""Add to group"" button.
5) The mentee was added.
6) Select the same mentee in drop-down list.
7) The mentee was added again."	Major	High	Always	Incorrect operation	No		New 
MM-4/4	You can enter over than 20 characters in the "Module Name" field.	"You can enter over than 20 characters in the ""Module name"" field when the max number of characters in the field ""Module name"" is 20.
Precondition: As a Trainer add module to group. 
Select the tab "" Add module to group"", enter the field ""Module name"" with >20 value, chose type and press ""OK"" button. 
Act: You can enter more over than 20 characters in the ""Module name"" field. 
Exp: You can enter only 20 characters in the ""Module name"" field"	"1)Select the tab ""Add module to group"".
2) Select group with the drop-down list.
3) Enter in the ""Module name"" field  >20 characters.
4) Press the ""Add module button"".
5) The module was added."	Minor	Low	Always	not equivalent value	No		New 
MM-4/5	You can add the same module an unlimited number of times at one group	"You can add the same module an unlimited number of times at one group in the ""Module name"" at the ""Add module to group"".
Precondition: As a Trainer add module to group. 
Select the tab ""Add module to group"", fill the ""Module name"" field with same module name two or three times
Act: added same module unlimited of times
Exp: can't add same module"	"1) Select the tab ""Add module to group"".
2) Select group in drop-down list.
3) Enter the ""Module name"".
4) Press the ""Add module"" button.
5) The module was added.
6) Select the same module in the ""Module name"" field.
7) The module was added again."	Major	High	Always	Incorrect operation	No		New
MM-4/6	At the "Set mark" the "Select mentee" drop-down list is not available	"At the ""Set mark"" even you fill all required filds the ""Select mentee"" drop-down list is not available but not always
Precondition: As a Trainer set mark.
Select the tab ""Set mark"" chose mentee for seting mark
Act: you can't select mentee, the drop-down list is not available
Exp: you can select mentee, the drop-down list is available"	"1) Select the tab ""Set mark"".
2) Select group.
3) Select mentee."	Major	High	Not always	Incorrect operation	No		New
MM-4/7	At the "Set mark" the "Select Module" drop-down list is not available	"At the ""Set mark"" even you fill all required filds the ""Select Module"" drop-down list is not available
Precondition: As a Trainer set mark.
Select the tab ""Set mark"" select group, select mentee, select module for seting mark
Act: you can't select module, the drop-down list is not available.
Exp: you can select module, the drop-down list is availiable."	"1) Select the tab ""Set mark"".
2) Select group.
3) Select mentee.
4) Select module."	Major	High	Always	Incorrect operation	No		
MM-5/1	When adding a mentee to the group he appears at the bottom left under the "Select mentee" text field.	"When adding a Mentee to the group he appears at the bottom left under the ""Select mentee"" text field.
Precondition: Register as a Trainer, login and create group. Select the tab ""Include Participants"" 
Act: Selected mentee appear at the bottom left under the ""Select mentee"" text field
Exp: Selected mentee was added and redirect to Index page.
RQ: 5/2
"	"1) Select Group to click in drop-down list.
2) Select mentee to click in drop-down list.  
3) Click the "" Add to Group"" button. "	Critical	ASAP	Always	unexpected behavior			New
MM-5/2	The same mentee can be add to the same group few times	"The same mentee can be add to the same group few times
Precondition: Register as a Trainer, login and create group. Select the tab ""Include Participants"" 
Act: The same mentee can be add to the same group few times
Exp: The same mentee can be add to the same group only one time time

"	"1) Select a group by clicking on the ""Select group"" drop-down list.
2) Select a mentee by clicking on the ""Select mentee"" drop-down list. 
3) Click the "" Add to Group"" button 2 times."	Critical	ASAP	Always	Incorrect operation	No		New
MM-6/1	"If you set two or more marks to the same mentee, the name of the 
mentee will be repeated all the time after pressing the button"	"If you set two or more marks to the same mentee, the name 
of the mentee will be repeated all the time after pressing the 
button
Precondition: Register as a Trainer, login and create group. 
Select the tab ""Set mark""
Act: the name of the mentee repeated all the time after 
pressing the button
Exc: the name of mentee don't repeat"	"1) Select a group by clicking on the ""Select group"" drop-down list.
2) Select a mentee by clicking on the ""Select mentee"" drop-down list.  
3) Select a module by clicking on the ""Select module"" drop-down list.
4) Select a mark by clicking on the ""Mark"" drop-down list.
5) Click the button ""Set mark"" 2 times"	Major	High	Always	Incorrect operation	No		New
MM-6/2	If you set marks to different mentees they are all shows in one row	"If you set marks to different mentees they are all shows in one
row.
Precondition: Register as a Trainer, login and create group. 
Select the tab ""Set mark""
Act: all mentees shows in one row
Exc: each mentee shows in a new row"	"1) Select a group by clicking on the ""Select group"" drop-down list.
2) Select a mentee by clicking on the ""Select mentee"" drop-down list. 
3) Select a module by clicking on the ""Select module"" drop-down list.
4) Select a mark by clicking on the ""Mark"" drop-down list.
5) Click the button ""Set mark""
6) Select another mentee by clicking on the drop-down list.
7) Click the button ""Set mark"""	Major	High	Always	Incorrect operation	No		New
MM 7/1	"Before registeration on main page there are 5 modules 
(To register, To Login, Log out, Edit Profile, My Marks)"	"Before registeration on main page there are 5 modules 
(To register, To Login, Log out, Edit Profile, My Marks) instead
of 3 (To register, To Login, Log out)
Actual result:  5 modules 
(To register, To Login, Log out, Edit Profile, My Marks)
Expected result: 3 modules  (To register, To Login, Log out)"	1) Open the main page	Critical	High	Always				
MM 7/2	"Confirm" in "Edit profile" button is not active.	"After editing data in ""Edit profile"", ""Confirm"" button does not 
become active
Actual result:  ""Confirm"" is not active
Expected result: ""Confirm"" is active"	"1) Fill in ""Registration""
2) Fill in ""Log in""
3) Press on ""Edit Profile""
4) Edit data
5) Press ""Confirm"""	Critical	ASAP	Always	Missing feature			
ММ 8/5	"""Registered"" button is accessible when use special symbols in  
""First Name"" field"	"If you use special symbols in ""First Name"" and fill in other 
fields with valid values ""Registered"" button would be accessible
Actual result: ""Registered"" button is accessible
Expected result: ""Registered"" button is not accessible"	"1) Fill in ""First Name"" using special symbols (!@#$%)
2) Fill in other fields with valid values
3) Press ""Registered"" button"	Critical	ASAP	Always	"Incorrect operation
Documentation 
issue"			
MM 8/6	"""Registered"" button is accessible when use special symbols in  
""Last Name"" field"	"If you use special symbols in ""Last Name"" and fill in other 
fields with valid values ""Registered"" button would be accessible
Actual result: ""Registered"" button is accessible
Expected result: ""Registered"" button is not accessible"	"1) Fill in ""Last Name"" using special symbols (!@#$%)
2) Fill in other fields with valid values
3) Press ""Registered"" button"	Critical	ASAP	Always	"Incorrect operation
Documentation 
issue"			
MM 8/7	"""Registered"" button is accessible when indicate phone number 
without prefix"	"If you indicate phone number without prefix (not according to
the gost text) and fill in other fields with valid values 
""Registered"" button would be accessible
Actual result: ""Registered"" button is accessible
Expected result: ""Registered"" button is not accessible"	"1) Fill in ""Phone number"" without indicating prefix
2) Fill in other fields with valid values
3) Press ""Registered"" button"	Critical	ASAP	Always	"Documentation 
issue"			
MM 8/8	"""Registered"" button is accessible when indicate phone number 
using special symbols "	"If use special symbols (!@#$%) in ""Phone number"" and fill in other 
fields with valid values ""Registered"" button would be accessible
Actual result: ""Registered"" button is accessible
Expected result: ""Registered"" button is not accessible"	"1) Fill in ""Phone number"" using special symbols
2) Fill in other fields with valid values
3) Press ""Registered"" button"	Critical	ASAP	Always	"Incorrect operation
Documentation 
issue"			
MM 8/9	"Insert in ""First Name"" more than 25 symbols, ""Registered"" 
button is active"	"If insert more than 25 symbols in ""First Name"" field, the ""Registered"" 
button would be active
Actual result: ""Registered"" button is active
Expected result: ""Registered"" button is not active "	"1) Fill in ""First Name"" using special symbols >25
2) Fill in other fields with valid values 
3) Press ""Registered"" button "	Minor	Low	Always	"Documentation 
issue"			
MM 8/10	"Fill in ""First Name"" use chinese characters, ""Registered"" 
button is active"	"If use chinese characters in  ""First Name"" the ""Registered"" 
button would be active
Actual result: ""Registered"" button is active
Expected result: ""Registered"" button is not active "	"1) Fill in ""First Name"" using chinese characters
2) Fill in other fields with valid values 
3) Press ""Registered"" button "	Major	High	Always	"Incorrect operation
Documentation 
issue"			
MM 8/11	"Fill in ""Last Name"" use chinese characters, ""Registered"" 
button is active"	"If use chinese characters in  ""Last Name"" the ""Registered"" 
button would be active
Actual result: ""Registered"" button is active
Expected result: ""Registered"" button is not active"	"1) Fill in ""Last Name"" using chinese characters
2) Fill in other fields with valid values 
3) Press ""Registered"" button "	Major	High	Always	"Incorrect operation
Documentation 
issue"			
MM-9/1	"При нажатии на кнопку ""Cancel"" с заполненными полями 
пользователь авторизуется"	"Пользователь авторизуется после нажатия на кнопку
""Cancel"" при заполненных полях ""Email"" и ""Password"" 
Precondition: зарегестрироваться
Actual result: Пользватель успешно авторизуется
Expected result: Отмена авторизации"	"1. Ввести valid data in ""Email"" and ""Password"" fields
2. Press the button ""Cancel"""	Major	High	always	Incorrect operation	No		New
