# #100DaysOfCode

## Day 0: July 11 2022, Monday

### Starting The Odin Project (Again)

**Today's Progress**: Started over again on [TOP](https://www.theodinproject.com/).


## Day 1: July 12 2022, Tuesday

### Installing [VirtualBox](https://download.virtualbox.org/virtualbox/6.1.34/VirtualBox-6.1.34a-150636-Win.exe) and [Xubuntu](https://cdimages.ubuntu.com/xubuntu/releases/22.04/release/xubuntu-22.04-desktop-amd64.iso)

**Today's Progress**: Installed Virtualbox and Xubuntu with VSCode and Chrome.
**Progreso Diario**: Instalé Virtualbox y Xubuntu con VSCode y Chrome.

**Details**: Repaired full size lightdm login window following [this article](https://www.nakivo.com/blog/make-virtualbox-full-screen/) and [this article](https://askubuntu.com/questions/1092699/how-to-adjust-display-settings-for-lightdm-greeter-on-18-04).
**Detalles**: Reparé la disposición de la ventana de inicio de sesión de lightdm siguiendo [este artículo](https://www.nakivo.com/blog/make-virtualbox-full-screen/) y [este otro artículo](https://askubuntu.com/questions/1092699/how-to-adjust-display-settings-for-lightdm-greeter-on-18-04).


## Day 2: June 13 2022, Wednesday
### The bash console

**Today's Progress**: Virtualbox VM cloning, The Unix Shell(https://swcarpentry.github.io/shell-novice/).
**Details**: Starting to know some new commands like wc (wordcount) and pipes and redirections.

## Day 3: June 14 2022, Thursday
### The bash console, git, github

**Today's Progress**: Continue with The Unix Shell(https://swcarpentry.github.io/shell-novice/).
**Details**: Continuying to get known with some new commands from the bash. Installed and configured git, some videos on it

## Day 4: June 15 2022, Friday
### Basic git commands on TOP

**Today's Progress**: Done with installing gh, setting up a test repository and basic functionality

<details>
<summary><b>Knowledge Check</b></summary>

1. How do you create a new repository on GitHub?  
    Option 1: Via website, create new repository  
    Option 2: From a local repository  

        git init  (create local repository)
        gh repo create  (create remote repository)

2. How do you copy a repository onto your local machine from GitHub?

        git clone + ssh link or https link

3. What is the default name of your remote connection?

        origin

4. Explain what origin is in git push origin main.

        origin is the remote target branch

5. Explain what main is in git push origin main.

        main is the local source branch to be pushed to origin

6. Explain the two-stage system that Git uses to save files.

        first files can be commited to stage
        after succesfull commitment, they can be pushed to remote git repo

7. How do you check the status of your current repository?

        git status on selected branch folder

8. How do you add files to the staging area in git?

        git commit $filename -m "message"

9. How do you commit the files in the staging area and add a descriptive message?

        git commit $filename -m "message"

10. How do you push your changes to your repository on GitHub?

        git push origin main

11. How do you look at the history of your previous commits?

        git status

</details>
