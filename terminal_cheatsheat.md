# Ana's Cheat Sheet :ledger:
## A list of useful commands!

![](https://github.com/mushanshitiancai/vscode-paste-image/raw/master/imagePath)


_____________
> see where you are

 pwd
 
##### /Users/yourusername
_____________
> show files in directory

 ls
______________
> show all files including hidden files
>
 ls -al
_____
>list files and folders, owner, last edited

 ls -l
______
> change directory

 cd
#####  cd documents/file.txt
________
 > go back up a level in the path
 
 cd ..
______
> create folder (make directory )

mkdir

#####  mkdir my_directory
##### * Note: folder name cant include:

 - ##### slashes
 - ##### dots
__________
> create files

 touch
#####  Touch my_picture.png
___________
> specify file type

 use [ . ] at the end of file name and then add extension
 
##### Recipe.txt
##### * Note file without extension is created just like notepad kind of file
_____________
>open files

 open
 
##### open my_file.txt
____________
>open file with a specific program

##### open code my_file.txt
____________
> move file

mv

##### * to move you need  [file  name] + [ location ]
##### mv my_picture.png document
_____________
> move to directory (above this one)

##### mv my_picture.png ..
##### * dot at end means  directory above current
____________
> move to (this) directory

##### mv my_picture.png .
##### * dot at end means this directory
____________
>rename file

mv
##### *  mv [file name] +  [new file name ]
#####   mv example.txt file.txt
____________
>copy

cp
##### * to move you need  [file  name] + [ location ] example:
##### profile_picture.png my_directory
 __________
 > copy folder (directory)

 cp -r
 
____________
> delete file

 rm

##### rm profile_picture.png
____________
> delete folder (directory)

 rm -r
 
#####  rm -r my_directory
##### * Dont forget space before dash
____________
-------------------------------------- [        Github        ] -----------------------------
> Check if tracking

git status

> create tracking

git add

>create snapshot

git commit

>check log

git log

 > Extra info:
 
 * yellow cross - means something in there hasnt been commited
 * quit log: + q

-------------------------------
>  :arrow_down: Downloading

1. Grab SSH code from github

   #####  On Git go to code at LHS top of screen  then click green code button
   
2. Clone

   #####  On terminal paste code after
   #####  ➜ ~ git clone
   
3.  Check files

    ##### ls
    
4. Change directory

   #####  ➜ ~ cd bnta_cohort5b
   ##### should see list of files in folder
   
5. Download files

   ##### ➜ bnta_cohort5b git:(main) git pull
    ##### should say done
    
6. Check files are in your folder

   ##### ➜ bnta_cohort5b git:(main) ls
    #####
    ##### should see list of files in folder
   
    * ##### README.md         laptop_setup_instructions.md

