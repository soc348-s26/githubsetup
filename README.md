# Github setup
Instructions


Basic set up for the class. 

Assuming you are on rstudioServer setting your github PAT (Personal Access Token) has extra steps.

First open up the r environment file. 

```
usethis::edit_r_environ()

```

Write
```
GITHUB_PAT=
```
in the file.

Now create your token 
In the Console type 
```
usethis::create_github_token()
```

Assuming you are logged into github, this will take you to a page to create a token.  
Give it a name like "token_348"  and set it to expire June 15  (this is a custom date).

Create the token.

Copy the token. In your environment file, paste it after GITHUM_PAT=

```
GITHUB_PAT=longstringofrandomlettersandnumbers
```

Save your file and restart R from your session menu.

With luck this will work until June 15.

