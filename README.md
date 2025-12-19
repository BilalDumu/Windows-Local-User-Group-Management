<h1>Windows-Local-User-Group-Management</h1> 
<h2>Description </h2>
<b>In this project, I will demonstrate how to perform administrative tasks like, adding new users, changing their passwords, making them administrators, and removing administrative privileges, and also deleting accounts.

<h2>Operating System:</h2>
- Windows 11

<h3>1. New user </h3>
<img width="396" height="200" alt="new user 2" src="https://github.com/user-attachments/assets/4d4000a6-7a88-4d7d-b7c4-bda5e24cde71" />
To access the run application you must press <code>win + R</code>.<break>
  
once accessed type <code>lusrmgr.msc</code> which stands for "local user and group manager microsoft Snap-in console"</break>

It's a Windows administrative tool used to manage user accounts and groups on a specific conmputer.

<img width="936" height="612" alt="new user 3" src="https://github.com/user-attachments/assets/dad57dc4-b610-4c0c-899d-d457565b6def" />

Now as an Admin I can do a whole host of things, lets create a new user named "Sandra"

<img width="942" height="716" alt="new user 4" src="https://github.com/user-attachments/assets/85d694f2-c905-4f46-aa73-6daf0552bffd" />

as you may see we can disable the account, make it so the users password never expires, and make it so the user cannot change passwords.

we will alow sandra to change password at next logon, which is great for security as it allows for me to provide a temporary password that is later changed by the user.

after ticking the box select <code>OK</code>


<img width="940" height="716" alt="new user 5" src="https://github.com/user-attachments/assets/a2ad7c2f-500a-4552-a23f-1cc6eb65730a" />

As we can see here, Sandra is now a user.


<img width="1036" height="720" alt="new user 6" src="https://github.com/user-attachments/assets/d757a5ff-427c-4bd0-967d-c7d684b2d2ed" />
Now let's make sandra an administrator.

Click on users name and go to "members of" here we see she is a member of the "users" group.

go ahead and click add.

<img width="936" height="706" alt="new user 7" src="https://github.com/user-attachments/assets/58c3e928-23b0-419c-9e88-1734335deb84" />

type "Administrators" and click <code>Check Names</code> to make sure the group actually exists Then click OK.

<img width="941" height="710" alt="new user 8" src="https://github.com/user-attachments/assets/d154dc01-fba6-49c5-ad21-73257f257508" />

here we see sandra in now in "users" group and "administrators" group.

go ahead and remove "users" group.

<img width="670" height="161" alt="new user 9" src="https://github.com/user-attachments/assets/d1ef1ada-906e-45be-ba6d-274d5fd05ec3" />

Now Sandra is an administrator.
To remove her administrator privileges,do the same thing.
<img width="1036" height="715" alt="new user 10" src="https://github.com/user-attachments/assets/390228df-6f60-4c46-ba7b-5eb7b24d8548" />

Make sure to type in 'Users" then press OK.

<img width="938" height="715" alt="new user 11" src="https://github.com/user-attachments/assets/a1ce38be-5ba3-4141-b890-3a7264dbfd25" />

Remove Sandra from being a member of "administrators" group.

<img width="588" height="223" alt="new user 12" src="https://github.com/user-attachments/assets/362bdcbb-3232-4b4e-8508-eb4914f56555" />

And like that,Sanda is a user once again.





