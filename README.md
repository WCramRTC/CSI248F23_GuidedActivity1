# Renton Technical College CSI-248
<br />    

<div align="center">  
    <img src="logo.jpg" alt="Logo">
    <h3 align="center">Guided Activity 1</h3>
</div>

This repository is a part of CSI-248 at Renton Technical College.

## Guided Activity Part 1 Using the Command Line
We will complete this assignment together in class. If you are having problems with this assignment please refer to the lecture recording.

1. Clone the repository to your local machine. (Do not use OneDrive for assignments in this course!)
2. Make note of the folder where you cloned the repository
3. After you have cloned this repository navigate to your local repository using the cd command
4. Open the repository in Visual Studio Code by typing code .
5. Open the terminal in Visual Studio Code by hitting ctrl + \` or cmd + \` on mac
6. Create a new folder called ScreenShots ![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/1a57771e-4ed9-4e5d-8a7b-cad1d8139b2f)

7. Take a screenshot of your Visual Studio Code and Terminal Window and save in it your Screenshots folder
8. Type new-item hello.txt (Mac: touch hello.txt) to create a new file
9. You will see this file inside of Visual Studio code
10. Inside of the file type your name and save the file
11. Go back to the terminal and type cat hello.txt ![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity1/assets/90283966/21175413-3067-4a5d-8e6e-4b6c1d8975e1)

12. Take a screenshot of the output and save the file inside of the screenshots folder.
13. Type git add . to stage all updated files
14. Type git commit -m "Part 1 Complete"
15. Type git push to push the changes to GitHub

## Guided Activity Part 2 Node NVM and Node

1. Install NVM for your operating system. Windows users (https://github.com/coreybutler/nvm-windows/releases/download/1.1.11/nvm-setup.exe) Mac Users: https://dev.to/ajeetraina/how-to-install-and-configure-nvm-on-mac-os-5fgi
2. Once NVM is installed type nvm at your terminal. You should see a list of commands
3. Type nvm install latest - This will install the latest version of NodeJS on your machine
4. Type nvm use latest, take a screenshot of the output and add to the screenshots folder
5. With the latest version of NodeJS added you should now be able to run Nodel commands from the terminal
6. Type node --version, take a screenshot of the output and add to the screenshots folder
7. With node installed, lets try it out. Type touch hellworld.js to create a new file
8. Inside of that file in Visual Studio Code add console.log("Hello World"); to the file and save it
9. Now from the terminal run node helloworld.js, Take a screenshot of the output and save to the screenshots folder.
10. Type git add . to stage all updated files
11. Type git commit -m "Part 2 Complete"
12. Type git push to push the changes to GitHub

## Guided Activity Part 2 NPM
1. From the terminal type npm init (this creates a new node project)
2. Name the package firstnodeproject
3. You can simply hit enter for all of the additional options
4. Notice that a package.json file is created
5. package.json defines the entry point of the application as well as an dependencies the project may have
6. Notice that index.js is defined as main, or the entry point
7. Lets create an index.js file
8. Type touch index.js (windows: new-item index.js)
9. Open index.js in Visual Studio code and add console.log("Node project running"); and save the file
10. Now let's tell Node to run index.js when we start the project
11. Open package.json and replace the entry under scripts "test": "echo \"Error: no test specified\" && exit 1" with "start" : "node index.js"
12. Save the file
13. Now run npm start from the terminal. You should see Node Project Running printed to the console.
14. Take a screenshot of the output and add to the screenshots folder.
15. Type git add . to stage all updated files
16. Type git commit -m "Guided Acticity 1 Complete"
17. Type git push

If you have any questions about this assignment please reach out to myself or our TA for this course. 



Feel free to message your instructor or the TA on Canvas if you have any questions.
