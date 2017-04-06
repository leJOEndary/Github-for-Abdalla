# Github-for-Abdalla

I  - First of all, save the code you currently have in another directory.


II - To pull the repo after noura announces do the following :-

	1- Make a new empty folder and open the terminal inside it.

	2- Type : (git init) , 
	   Expect: initialized empty git repo.......

	3- Type : (git remote add origin https://github.com/SEGUC17/abdallah-wl-3-banat.git),
	   Expect : new line

	4- Type : (git pull origin dev), 
	   Expect : github asks you for username and pw.

	5- After entering them successfully, Type : (git branch)     **Confirmation for step 4**
	   Expect : *master "in green" & you should find the new code in your new folder.
	   
	6- Type : (git checkout -b dev)
	   Expect : Switched to a new branch 'dev'


III- Now copy your stuff from the old to the new code.


IV - To push changes to your own github branch do the following :-

	1- Open a terminal in the directory of the new code. 
	2- Type  : (git add .)
	   Expect: new line.

	3- Type  : (git status)     **Confirmation for step 2**
	   Expect: On branch dev, Changes to be committed:  *A bunch of files in green*

	4- Type  : (git commit -m "Any brief description of your tasks inside double quotes")
	   Expect: [dev blablabla] "the description u entered for the commit", 1 file changed.....

	5- Type  : (git checkout -b dev-"your name without the quotes")
	   Expect: Switched to a new branch 'X'

	6- Type  : (git push origin "The value of X without the quotes")
	   Expect: It may or may not ask for your github credentials, then you will see it
             uploading.


V - Wait for a the upload, then refresh the repo and check the changes on your new branch 'X'.


Wasalamo 3alaykom wara7matolah wa barakatoh.
