# File_Management-System

## Defining the Problem Statement:
Data on every Operating System is stored in a hierarchical file system constituted of directories and subdirectories beneath them. A file management system is the program used to arrange these files, move them, and create / delete them. This take care of how the files are organized rather than how they are stored.

The key features are to:

> Create, modify, move, copy, delete and other file operations.

> Add or edit basic metadata.

## Selecting the Data Structure

Trees would be the best suited data structure to implement this because nodes and leaves of the tree resemble the directories and sub-directories containing files in them.

A binary tree cannot do the job here as it restricts to only having two children. N-ary Tree should be implemented solve this. Since we do not know what will be the value of n, each node cannot have a fixed child links.

![image1](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/24119642-827d-4443-b565-c7ba4040fb81)

There is also a need to traverse upwards to its root. This can be solved by creating another link with the parent directory. Although this technically becomes a Graph, but implementation will be like a binary tree in a broad level and like linked list in a directory level.

![image3](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/98eab116-1f8e-4cf2-b4e0-d20253504e2e)

## Execution of Solution:

The execution is very much inspired from Linux shell. The program resembles the shell which contains the present working directory on left and prompt at end. The user can use following commands just like in the Linux shell. Some key commands are:

cd - to navigate through directories

ls - to list the files and sub-directories in a directory

tree – to view a tree structure of what is inside a directory until the last file

mkdir – to create a new directory

touch – to create a new file

edit – to edit the file contents

rm / rmdir – to remove a file / directory respectively

cp / mv – to copy / move a file or directory respectively

find – to find files or directories

## IMPLEMENTATION AND OUTPUTS:

### help command:

   prints the information about all the commands available.
   
   ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/2e907632-c9fa-4814-94a5-3f4e970b7a21)

### tree:
   This algorithm prints all node names from root in a form of tree

   ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/5d72a62e-f5f1-4dfb-8296-9b5ed6ebfbfe)

### ls:
  This algorithm prints all node name in a directory
  
  ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/5e65d5fa-d7ec-4b45-b933-bf98906a4702)

### pwd:
  This command returns the complete path of a node with respect to root.

  ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/7cc9ac76-1a8c-4d6d-b306-1170f515409e)

### cd:
   This command is used to change the present working directory.

   ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/0dc2733d-d80a-41f7-ba5f-2e7f4aabd9a7)

### mkdir:
  This command is used to create a new Directory

  ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/e6a10bea-3101-4250-9cba-483434b7964b)

### rmdir:
  This command is used to delete a directory.

  ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/ffd84949-94f1-42d7-8fdc-084cc9317734)

### touch:
  This command is used to create a new file.

  ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/600824bb-53f2-47cc-99a1-76b60388e636)
### edit:
  This command is used to make changes/edits in a file(similar to a command vi in linux).

  ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/7150b7b0-98ae-41d1-a6e7-e74b076ce6de)

### rm:
   To remove/delete the file.

   ![image](https://github.com/kowshikbattalapalli/File_Management-System/assets/78654213/c21e3ccf-7477-4cf6-9b54-3562c981a1ce)



  









   




