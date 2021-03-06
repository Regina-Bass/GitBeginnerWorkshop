# Git Beginner Workshop

Check if you have git by doing 
`git --version` in your terminal or command line

If you get an error, then you do not have git installed locally. Visit: https://git-scm.com/downloads

If you run into any problems, let one of the hosts know on Discord so that they can assist you!


<br>

## Exercise 0

<details>
  <summary>Clone this repository</summary>
  
  ```git
    git clone <url>
  ```
  <img src="/findURL.png" alt="image of GitHub Interface" width=800><br>
</details>
<details>
  <summary>Access README.md </summary> 
  <p>
  <ol>
    <li> Change directory into the repository you just finished cloning into
      
  ```unix
    cd GitBeginnerWorkshop
  ```
   </li>
      <li> Look at the list of files and folders in your current directory / path
      <ul>
        <li> Mac:
  
  ```unix
    ls
  ```
  </li>
        <li> Windows: 
  
  ```unix
    dir
  ```
</li>
    </ul>
  </li>
   <li> Access the README file
      <ul>
        <li> Mac:
  
  ```unix
    open README.md
  ```
  </li>
        <li> Windows: 
  
  ```unix
    start README.md
  ```
</li>
    </ul>
  </li>
   <li> Finally, leave the repository
  
  ```unix
    cd ../
  ```
  </li>
  </ol>

  </p>
</details>

<br>

## Exercise 1
<details>  <summary>Create a directory</summary>
 
  ```unix
    mkdir <name>
  ```
</details>

<details><summary>Initialize the directory as a git repository</summary> <br>
<ol>
    <li> Change Directory into the new directory you just created
      
  ```unix
    cd <name>
  ```
   </li>
       <li> Initialize the repository
      
  ```git
    git init
  ```
   </li>
 <ol>
</details>
<details><summary>Create a simple text file</summary> <br>
<ol>
    <li> Create the file (example: test.txt or myFile.txt)
      
  ```unix
    nano <name>.txt
  ```
   </li>
       <li> It should have opened a GUI. Write something in it, such as your name.</li>
       <li> When you're satisfied, Exit with Ctrl + X, save the file with Y, then click Enter. 
  
   <p>**You can test the file by opening it with open <filename> or start <filename></p>
   </li>
 <ol>
</details>
  <details>  <summary>Stage or Add this file</summary>
 
  ```git
    git add <filename>
  ```
  OR
  ```git
    git add .
  ```
  the period (you can also use -a) stands for all
</details>
  <details>  <summary>Commit</summary>
 
  ```git
    git commmit -m "Put your message here"
  ```
</details>

<br>


<details>  <summary>Create a GitHub Account</summary>
    Go to https://github.com/join
</details>

  <details>  <summary>Push your commit to the repository</summary>
 
  ```git
    git push
  ```
  
 ** You may run into some configuration problems since this is your first time authenticating.
</details>

<br>

## Exercise 2

<details>
  <summary>Create a branch and "Check Out"</summary>
  
  ```git
    git branch <name>
  ```
  OR
  ```git
    git checkout -b <name>
  ```
  The latter will create the branch and then checkout for you, whereas if you do the first version you are only creating the branch and will need to run `git checkout <branchName>` afterwords.
  
</details>
<details>
  <summary>Try It Out!</summary>
  Try <b>Adding</b>, <b>Commiting</b>, then <b>Pushing</b> something onto this branch!
  
  When you're done, go to your github profile to see those changes!
</details>


### Config
`$ git config --global user.name "John Doe"`

`$ git config --global user.email johndoe@example.com`
