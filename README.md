<h1>Stes to Create a New Repo </h1>

Create a new repo call name newrepo at git hub.
mkdir a newrepo directory at visual studio cmd terminal
cd to newrepo direcoty
echo " readmefile" >> README.md
git init
git add README.md
git add file1.txt
git add file2.txt
git commit -m " commit"
git branch -M man 
git remote add origin git@github.com:jasonlow34/newrepo.git
git push -u origin main 

<!-- Steps to Generate SSH key  -->
At command prompt type below command to generate ssh key. use default directory and key in your passphase accordingly. 
ssh-keygen -t rsa
Get the content of C:\Users\llow/.ssh/id_rsa.pub
insert it into github settings SSH config. 
