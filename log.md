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

**Today's Progress**: Virtualbox VM cloning, The Unix Shell(<https://swcarpentry.github.io/shell-novice/>).
**Details**: Starting to know some new commands like wc (wordcount) and pipes and redirections.

## Day 3: June 14 2022, Thursday

### The bash console, git, github

**Today's Progress**: Continue with The Unix Shell(<https://swcarpentry.github.io/shell-novice/>).
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

## Day 5: June 16 2022, Saturday

### Introduction to HTML

**Today's Progress**: Some introduction to HTML, CSS and JS

<details>

<summary><b>Knowledge Check</b></summary>

1. What do HTML and CSS stand for?

        CSS = Cascading StyleSheets
        HTML = HyperText Markup Language

2. Between HTML and CSS, which would you use for putting paragraphs of text on a webpage?

        HTML is for content
        CSS is for appearance

3. Between HTML and CSS, which would you use for changing the font and background color of a button?

        As said CSS

4. What is the difference between HTML, CSS and JavaScript?

        All three are complementary on the web, HTML creates the data structure, CSS the appearance and JavaScript the functionality on the client side or via nodejs server applications

5. What is the purpose of the doctype declaration?

        A doctype declaration sets the interpretation of the following code between the document and the browser
        The latest HTML version, HTML5 is declared as follows:
        <!DOCTYPE html>

6. What is the HTML element?

        The <html> element embraces the whole html document
        Is the parent element of the whole document

7. What is the purpose of the head element?

        The <head> element contains all metadata of the document.
        [meta on mdn](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#browser_compatibility)

8. What is the purpose of the body element?

        The body element contains all content that will be displayed on the page

9. How do you create a paragraph in HTML?

        To create a paragraph we use the tags <p></p>

10. How do you create a heading in HTML?

        To create a heading we use the <h1></h1> to <h6></h6> tags

11. How many different levels of headings are there and what is the difference between them?

        There should only be one <h1>, all other headings go down on hyerarchical order of most meaningfull to less meaningfull

12. What element should you use to make text bold and important?

        To give importance to a portion of text we use the tag <strong></strong>.

13. What element should you use to make text italicized to add emphasis to it?

        To emphatize a portion of text the tag <em></em> should be used.

14. What relationship does an element have with any nested elements within it?

        Nested elements have a child relationship to their parents, just as a family tree

15. What relationship do two elements have if they are at the same level of nesting?

        Two elements on the same level of nesting are siblings

16. How do you create HTML comments?

        To create an HTML comment we use the opening <!-- and closing --> tahs

15. What HTML tag is used to create an unordered list?

        Unordered list are placed between <ul></ul> tags

16. What HTML tag is used to create an ordered list?

        Ordered lists are placed between <ol></ol> tags

17. What HTML tag is used to create list items within both unordered and ordered lists?

        List items of any list are surrounded by <li></li>

18. What element is used to create a link?

        <a> is the element anchor used to create a link

19. What is an attribute?

        Atributes are information pieces that go on the opening tag of an element giving more relevant information on it.  
        Like href="" on anchor elements, src="" or alt="" on images



20. What attribute tells links where to go to?

        href="" sets the HyperText Reference, the target of the anchor.
        It can be an absolute URL, a relative URL or an URI Fragment (# followed by the id of the element on the same page)
        it can be also another protocol like email or a call to a script

21. What is the difference between an absolute and relative link?

        Absolute links have the full web address to the target document, while relative, are normally on the same domain, and relative child or parent to the document where they are called from

22. Which element is used to display an image?

        img

23. What two attributes do images always need to have?

        src="" for the image to get displayed
        alt="" with the relevant information about the image for people with some disability or in case image wont load

24. How do you access a parent directory in a filepath?

        with ../

25. What are the four main image formats that you can use for images on the web?

        jpg for photos
        svg for vector images (whenever possible)
        png supports palette and non palette based images, and transparency
        gif for indexed color images and movement


</details>

#### Assignment

[Create a Blog Post](html/assignments/01 blog post/index.html)
[Create a new HTML document and create some lists](html/assignments/02 Lists/index.html)
