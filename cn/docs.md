Codinator Documentation
=======================

Codinator is your one-stop web-coding app for iPad, iPhone and iPod Touch. With many features including syntax highlighting, projects, playground, themes, GitHub-integration and a great markup language we made called [Neuron](#neuron), you won't be using Notes.app to code anymore. This Documentation is here to guide you through the immaculately small learning curve and to show you everything that you'll be using in Codinator. Do note that this is an extensive Documentation and so, it can be found inside `Settings` so that you can exhaust it even more.

## <a name="contents">Contents</a>
- [Contents](#contents)
- [Start Screen](#start)
- [Projects](#projects)
- [Playground](#playgrounds)
- [Neuron](#neuron)

## <a name="start">Start Screen</a>

When you enter into Codinator, you are met with the Start Screen. On the left, you see a list of projects (there probably isn't any just yet but that will be covered in the [next section](#projects). You can hold down on a project or playground to rename or delete it. At the top of the left hand side, you can switch between the files for [Projects ](#projects) and the files for [Playgrounds](#playground).

Moving on, you will see in the middle of the screen the Codinator logo. Underneath this, you will see the version or release number. You can use this to know if you are up to date with Codinator. To the right of the logo, you will see the "Settings" button. We'll let you comb through this and fully customise your experience with Codinator (make sure to check it out).

Underneath the logo that we saw before are three buttons. Each one of these has a role in getting you started with Codinator. Our most favourite button is the last when where you can import from GitHub and from zip files on the World Wide Web.

## <a name="projects">Projects</a>

Projects are Codinator's specified workspaces. They are where you do the hard grunt work, where you edit the bulk of your code and from where you export your code to various places.

To create a project, you click the "Create New Project" button on the start screen. ![Image of Start Screen](http://VWAS.ml/Codinator/docs/img/start-screen.png) This will trigger a pop up or modal with options to optimise your project. Firstly, name your project. Then, choose when you want to hold a copyright for the project (**NOTE:** most countries allow automatic copyrighting of works. Consult with a lawyer if you are unsure if copyrights will apply to you). Now, you will see that you can choose to optimise your project for JavaScript, CSS and FTP. Make sure that everything you want optimised has been slid to the right (indicating they are turned on). Now press "Next" to start your project.

Now, you will see project view.

On the left hand side is "File View" where all your files and folders are shown. Like with projects in the "Start Screen", you can hold down on files or folders to get more options. Upon doing so, you will see options to Preview, Print, Delete and Move the file or folder.

On the right is a set of controls and shortcuts for the file you are currently working on. This consists of the name and extension of your file (top right), the path of the file (tap on this to copy the path to your clipboard), the source control and version number of your file (we use our very own Polaris) and "Shortcuts and Snippets" (there's even a color picker there). To use any of the shortcuts or snippets, press them and they will either be copied to you clipboard or a modal will pop up with settings that help you.

In the middle is where you will be spending most of your time. The top is the editing console where you edit files, debug and the sort. The bottom is the immediate preview. This is where you see what you're editing ad what changes your edits are making. To go into a bigger preview, you can press the side-ways triangle (HINT: it's a "play" button) above the editing console. From there you can also change the screen ratio to test for responsiveness by clicking on the button on the top-right.

If you look to the bottom-left, you will see a range of options. First of all, there is a sideways triangle to let you navigate between folders. To the right of this, there is "+" (a plus button). Pressing this will allow you to create new files or folders or import them from other places like GitHub or Zips. To the right of this, you will see "Product" button. Clicking this will let you Run, Archive (version controlling), see History (version controlling), Export (to GitHub, Email, iCloud Drive, other apps and FTP), Upload (to GitHub) and set up a Local Server (to test, use as WebDAV and to upload to the project from other computers).

## <a name="playgrounds">Playgrounds</a>

Playgrounds are a place for you to experiment.

# Playgrounds Guide

## What are Playgrounds?
Playgrounds are just what you would think they are - Playgrounds.
But not just that, Playgrounds have fully functioning code editors which are perfect for quickly prototyping a concept.

## How to use Playgrounds
Playgrounds have four sections:
HTML, CSS, JS and Preview. In the HTML area, you type in your HTML. In the CSS area you doodle with your CSS and, in the JS aea, you program cool features for your concept. In the Preview area, you can see a live preview of what you have entered into the other areas. 

## <a name="neuron">Neuron</a>
Playgrounds have a few cool tricks backed in like our new syntax for the HTML area called Neuron. Down below you can see an example of PlayTack and how it's rendered as HTML:

```
START
   HEAD
      TITLE he yo /TITLE
   /HEAD
BODY
   H1 Yo dawg! /H1
/BODY
END
```

is rendered as

```
<!doctype html>
<html>
   <head>
   <title>he yo</h1>
   </head>
<body>
   <h1>Yo dawg!</h1>
</body>
</html>
```