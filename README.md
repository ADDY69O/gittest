Create a repo name gittest, initalise
Add gitignore file and add all files that ends with .jpg
 
Create 1.txt and 2.txt and 1.jpg into master and write few lines and commit.
Create two branches b1 b2 based on the master.
Create 3.txt into B1 and add some changes into 2.txt 
Add some changes into 2.txt into B2. 
Now move to branch B1 and add one more file 4.txt into B1 without commiting anything.
now come back to B2 and create one more 5.txt
Note: Please ensure changes into 2.txt in both B1 and B2 should contradict each other.
Now revert both 5.txt and 4.txt
Now merge both the branches into master.. Excepted result: Conflict.
Solve the conflict using Kdiff and ensure master is stable and clean.
Now go in master and revert 2.txt after initial checkin and ignore everything.
Now delete branch B2 and B1
Now tell latest shaid of all files.
Do diff on all files.
Git status
