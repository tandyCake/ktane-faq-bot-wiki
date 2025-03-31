# General 
## What is this
This bot's purpose is to answer frequently asked questions about modding KTANE. Its goal is to alleviate answering duplicate questions in [discord mod creation channel](https://discord.com/channels/160061833166716928/201105291830493193) and [discord repo discussion channel](https://discord.com/channels/160061833166716928/640557658482540564). Please try to see if your question(s) are answered here before asking there. Navigate through the categories below to see which section your question falls under. Please report any bugs or suggestions to the developers.
## I have a question that is not answered here. What should I do?
First, verify that your question has truly not been answered here. Sometimes, we gloss things over at a first glance. If the question still hasn’t been answered, ask it in [discord mod creation channel](https://discord.com/channels/160061833166716928/201105291830493193), but be specific as it makes other people help you quicker.
# Getting Started
## How do I get into modding?
1. Download the [KTANE Modkit](<https://github.com/Qkrisi/ktanemodkit>)
    - Assuming you have a github account (see [What is GitHub? Is it necessary to get into modding?](https://github.com/BlckHawker/test/edit/main/README.md#what-is-github-is-it-necessary-to-get-into-modding) for more details), you can create your own repository using the modkit. Press `Use this template` -> `Create new repository`. Add a name and press `Create repository`. Clone your project to your device.
    - If you don't have a github account, you can get the project by pressing `Code` -> `Download zip`. Extract the project. It is recommended that you change the name of the folder to be whatever the name of your mod is: "The Simpleton" for example.
2. Download [Unity Hub](<https://unity.com/download>) (optional for Windows)

Unity Hub is a tool that allows you to see all of your Unity projects in one place. It's optional, but highly recommended if you plan to make multiple Unity projects. **If you're a Mac/Linux user, this is not optional** for reasons explained in the next step. You can add a Unity project by selecting `Open` and selecting the folder of your project. It should be the one that contains `Assets` inside of it.

3. Install [Unity version 2017.4.22f1](<https://unity.com/releases/editor/whats-new/2017.4.22>)

This is the Unity version that the game was created on. Although you could theoretically use a different version of Unity to create mods, it's not recommended as there could be several game breaking bugs. If you installed Unity Hub, the application will ask you if you want to add any modules. **Mac and Linux users should add the \"Windows Build Support\" module** as it's required for the build of the mod to be created. If you missed this step, you can still add it by going to Unity Hub -> `Installs` -> press the gear next to the `2017.4.22f1` editor -> `Add modules` -> select `Windows Build Support` -> select `Continue`. Wait for said module to install. Close Unity Hub and any Unity projects you have open in order to verify it installed successfully. Before you open your project, make sure your editor version is set to `2017.4.22f1`.

4. Install an IDE

An IDE (Integrated Development Environment) is a tool that makes writing code **much** easier. It allows you to see what is wrong with your code without needing to constantly check Unity. It also color codes your words and has autocompletion which will make writing code quicker. Although you can write scripts by just using Notepad, it is not recommended. The most common IDEs for Windows are Visual Studio (VS) and Visual Studio Code (VS Code). Here are the [installations to both](<https://visualstudio.microsoft.com/downloads/>). Mac and Linux users should use [Rider](<https://www.jetbrains.com/rider/>). All require some setup to get working with Unity. Here are the steps to do so (Ignore the steps about installing packages as that is not supported in the Unity version for KTANE):
    - [VS Code](<https://code.visualstudio.com/docs/other/unity>)
    - [VS](<https://learn.microsoft.com/en-us/visualstudio/gamedev/unity/get-started/getting-started-with-visual-studio-tools-for-unity?pivots=windows>)
    - [Rider](<https://www.jetbrains.com/help/rider/Unity.html#start-using-rider-with-your-unity-project>)
5. Add a plugin template (Optional)
There are several pre-made templates that streamline the process of creating mods. Although optional, they are very useful for beginners. They can be found by pressing `KeepTalking ModKit` -> `Plugins` at the top of the Unity editor. Which one you use is up to personal preference.
These are the steps to set up your project for modding. See other [Getting Started](https://github.com/BlckHawker/test/edit/main/README.md#getting-started) commands if you require assistance with how to start modding.
## I don’t know how to start learning C#/Unity. How do I know when I learned enough to start modding?
* C# resources:
    - [Video Tutorials](<https://www.youtube.com/playlist?list=PL82C6-O4XrHcblXkHA4dLcnb_ipVkKHch>)
    * [C# documentation](<https://learn.microsoft.com/en-us/dotnet/csharp/>)
    * [Codewars](https://www.codewars.com): Website that allows people to solve a variety of coding problems in various ranges of difficulty. Good to practice C# (or any other language) skills
* Unity Resources:
    * [Unity Tutorial](<https://www.youtube.com/watch?v=XtQMytORBmM>)
    * [Unity Workshop](<https://youtu.be/XcK0Y_PVyu8>):  very similar to the first video teaching-wise, but you can try figuring out how to do both projects on your own for more practice
    * [Unity Documentation](<https://docs.unity.com>)
There isn’t a real answer to what is “enough” to start modding. You will learn new things as you continue using the tools. If you need to ask a question on how to do something, try googling it to see if someone else has asked the question before. If not, or you don’t understand the answer, you can try following what other people did in their mods (look at [I want my mod to do [X] like the mod [Y] does. How do I do that?](https://github.com/BlckHawker/test/edit/main/README.md#i-want-my-mod-to-do-x-like-the-mod-y-does-how-do-i-do-that) for more details). If you need more assistance, ask your question in [discord mod creation channel](https://discord.com/channels/160061833166716928/201105291830493193).
## Are there any modding tutorials I can follow?
Yes! There are several tutorials, though some of the information is outdated, the general steps are the same. Be sure to look at the [modkit wiki](<https://github.com/Qkrisi/ktanemodkit/wiki>) to see if something has been updated. It is also a good resource for understanding some methods/classes the modkit provides.
### Regular Mods
* [Deaf's video](<https://youtu.be/YobuGSBl3i0>) is very condensed and possibly best if for people who are proficient in C#/Unity.
* [Royal_Flu$h's series](<https://www.youtube.com/watch?v=Uwmm9iqAlV4&list=PL-1P5EmkkFxrwWW6z0uZ5nBdRImsReOQ0&index=6>) takes a slower pace. Explaining the different aspects of module creation in more detail. Better for beginners.
### Needy Mods
* [Deaf's needy video](<https://youtu.be/jnqxzVZYPHg>) assume that you have watched his regular modding tutorial first
### Boss Modules
* At the time of writing this (October 12th, 2024), there aren’t any noticeable tutorials for bosses. As for now, it’s recommended to look at the most simple form of a boss (Forget It Not)’s [source code](<https://github.com/VFlyer/FlyersOtherModules/blob/master/Assets/ForgetItNot/ForgetItNotHandler.cs>) as a reference.
## I don’t have time to look through tutorials/documentations that are this long. Is there a faster way to get started?
Short answer is no. If you want to get into a position of making your modules on your own, you will need to put in the effort of learning. It’s okay if you don’t get it right away as everyone learns at their own pace, but there isn’t a shortcut.\nIf you feel intimidated by the learning process, start small and grow from there. Try making a basic mod; recreate The Simpleton for example, and use what you learned in order to make your “dream” module. If you don’t like a certain aspect of mod creating: scripting, modeling, manual making, etc., you can ping the appropriate roles in [discord mod creation channel](https://discord.com/channels/160061833166716928/201105291830493193) to see if anyone wants to collaborate.
* Proofreader: People who can read your manual to verify it makes sense grammatically and logically
* 3D Creator: People who know how to model
* Mod Creator: Everyone else. Mainly people who can implement the entire mod, or just TP 
## What is GitHub? Is it necessary to get into modding?
GitHub is a website that holds your code. Think of it like Google Drive. Although GitHub is not required, it is definitely recommended as it allows you to work on your project on different devices and lets other people see and collaborate with your work. Here are the steps to set up git/Github.

1. Create a GitHub account
2. Install git. Follow this tutorial for installing it on [windows](<https://www.youtube.com/watch?v=8HhEupU4iGU>). Other OS tutorials can be found easily
3. Figure out which application you want to use in order to use git. There are several applications that have git controls inside of them. For basic purposes, you will need to know how to:
    * create a new **repository** (project on github)
    * **clone** (download a project that is on Github)
    * **commit** (save your changes)
    * **push** (“upload” your commits/changes)
    * **pull** (“download” your commits/changes)
     
Here are some tutorials explaining some of the git terminology including how to publish an existing Unity project to Github. Before you are about to publish your code to GitHub, verify you have a .gitignore file that looks something like [this](<https://github.com/github/gitignore/blob/main/Unity.gitignore>) in your root directory (should be on the same level of your “Assets” folder). This forbids unwanted bloated files being sent to GitHub. If it is not there, download it and replace it in the correct folder.
* [Visual Studio Code](<https://youtu.be/i_23KUAEtUM>)
* [Github Desktop](<https://www.youtube.com/watch?v=pn1YgU81GUY>)
* [Command line](<https://education.github.com/git-cheat-sheet-education.pdf>)
## I want my mod to do [X] like the mod [Y] does. How do I do that?
Most mods have their source code publicly available on github. You can find it by going to the [Repository of Manual Pages](<https://ktane.timwi.de>) and clicking the Unity Icon to the left of the mod. You will be taken to the repository of the mod. There you can either navigate the project in the browser itself, or download the project and modify it.
**ADD IMAGE HERE**
## How do I create my manual?
Download and extract the [manual template](<https://ktane.timwi.de/More/Template%20Manual.zip>). This can be found on the [Repository of Manual Pages](<https://ktane.timwi.de>) under `More` > `Template Manual`. It’s recommended to **always** download the template that is on the Repository of Manual Pages as it will always have the up-to-date version.
1. **Rename the folder** `Template Manual` to the name of your mod.
2. **Write the manual**: Inside the `HTML` folder, you will find a `HTML` file called `Module Name`. Rename that to your module name. Open that file in a text editor, (Visual Studio Code is preferred, but not required). This is where you write your manual with HTML.
    * It's recommended to read `Tutorial (delete when done).html` in your browser as it will show you how to use some HTML.
    * More tutorials
        * [HTML](<https://youtu.be/HD13eq_Pmp8>)
        * [CSS](<https://www.youtube.com/watch?v=wRNinF7YQqQ>)
        * [Javascript](<https://www.youtube.com/watch?v=Ihy0QziLDf0&list=PLZPZq0r_RZOO1zkgO4bIdfuLpizCeHYKv>) (will rarely be used for basic manuals)
    * [Video demonstration](<https://youtu.be/YobuGSBl3i0?t=10097>)
3. **Verify your pages don't exceed the page boundaries.** This can be done by pressing Alt + P in the browser to enable developer mode. If you see red on at the top/bottom of your page, you are exceeding the boundaries, and should move your content to a new page. It's okay if there is a little red, but there shouldn't be any over the words/pictures.

**Good**

![image](https://github.com/user-attachments/assets/1a5ca5e3-51ff-41b1-90b5-72d70476dfce)

 **Bad**
 
![image](https://github.com/user-attachments/assets/f680e656-1103-46a4-93b8-9e208be5f985)


4. **Make your SVG (image in the top right of the manual)**: A module svg's can be made in [inkscape](<https://inkscape.org>). A template of the svg can be found in the `HTML\img\Component` folder. Rename `Module Name.svg` to the name of the mod. Be sure to change the appropriate HTML in your manual to have this name change as well. Otherwise it will not show up in the manual.
    * [Inkscape tutorial](<https://www.youtube.com/watch?v=fzk-suGcqrc&ab_channel=LogosByNick>)
5. **Make the JSON**. This should only be done once the mod is fully finished and published to steam.\n  * Go to the [Repository of Manual Pages](<https://ktane.timwi.de>) -> `Tools` -> `Create new module`. Fill out the information and press `Generate JSON`. Please verify that no other mod shares any of the following information:
    * Name
    * Module ID
    * Sort key
    * Steam ID
* Copy the information to your clipboard
* In the manual template, open the `JSON` folder. Open `Module Name.json` in your text editor and paste the content you copied
* Rename `Module Name.json` to your actual module name.
* [Video demonstration](<https://youtu.be/YobuGSBl3i0?t=11850>)
6. **Lint your manual**: Zip the entire manual folder (what was originally called `Template Manual`), and send it to Logbot with the message `!lint` via a dm. The bot will check if there is anything wrong with your manual (including any images and the JSON). If you see any warnings, fix them, and lint the new version of the manual. Continue to do this until the bot reacts with :thumbsup:. See [How do I add my manual to the repository of manuals?](https://github.com/BlckHawker/test/edit/main/README.md#how-do-i-add-my-manual-to-the-repository-of-manuals) to see how you can upload your manual to the repository of manuals.
## How do I add my manual to the repository of manuals?
Note: This answer also applies if you are making edits to a manual existing on the repo

1. **Verify your manual is linted**. Run [How do I create my manual?](https://github.com/BlckHawker/test/edit/main/README.md#how-do-i-create-my-manual) for more details.
2. **Make your manual public for a repo contributor to see**. People who have the repo maintainer role have direct push access to the [Ktane Content repository](<https://github.com/Timwi/KtaneContent>). They (or another repo contributor) will look at your manual, make any necessary edits and upload it to the repository. There are two ways to give a maintainer your manual:
    * **Send it to [discord repo request channel](https://discord.com/channels/160061833166716928/612414629179817985)**
        * If it's a new manual, upload the zip to [discord repo request channel](https://discord.com/channels/160061833166716928/612414629179817985) with a message saying it's a new module.
        * If you're updating the manual, and only the HTML file changed, only that file needs to be sent to [discord repo request channel](https://discord.com/channels/160061833166716928/612414629179817985). If it's more than one file, send the entire zip with a message saying which files have changed.
    * **Make a Pull Request**
        * If you are familiar with git, you can clone the [Ktane Content repository](<https://github.com/Timwi/KtaneContent>), and make a pull request with your added manual. You can read through the [Repo Maintainer Responsibilities](<https://docs.google.com/document/d/10rabFJES6avb8ime3Cw5LCd9p0663PbqVqzUrfehYac/edit?usp=sharing>) checklist in order to verify that your manual is valid. Since not many maintainers look at pull requests on GitHub, it's recommended you link your PR into [discord repo request channel](https://discord.com/channels/160061833166716928/612414629179817985) along with a message briefly explaining what the PR is. It is expected that you do not touch the PR after it is published. If you need to make a change, close the PR, make the change, and make a new one. Here is a [repo contributor video tutorial](<https://youtu.be/2Lxl7OAafIg>) that demonstrates these steps.
3. **Wait for a maintainer to upload it to the repository.**
    * You will know if your module is being worked on if it has the reaction :bip:. Please do not delete the request if it has that reaction. If there is something that you missed that you want added to the manual, make a thread to the original request with a message describing the new changes.
    * Be patient as being a maintainer is a volunteer position. See [How long does it take for a request to be fulfilled? Can I speed up the process in any way?](https://github.com/BlckHawker/test/edit/main/README.md#how-long-does-it-take-for-a-request-to-be-fulfilled-can-i-speed-up-the-process-in-any-way) on how to make requests be handled faster. See [How do I become a maintainer?](https://github.com/BlckHawker/test/edit/main/README.md#how-do-i-become-a-maintainer) on how to become a maintainer.
## I would like to make changes on my manual that is already on the Repository of Manuals.
There are two ways:
1. **Make a request in** [discord repo request channel](https://discord.com/channels/160061833166716928/612414629179817985) of what you want changed. Be specific so repo contributors can handle the request without needing to know the manual
    * Example: `Simpleton: Add the following sentence after the first one: "This module cannot strike you"`
2. **Modify the manual yourself**.
    1. **Get the up-to-date version of the manual.** It can be found on the [Ktane Content repository](<https://github.com/Timwi/KtaneContent>). It's possible that a maintainer cleaned up your manual before publishing it to the repo. Always update your manual before making changes even if you don't think any changes have been made.
        1. Open the [Ktane Content repository](<https://github.com/Timwi/KtaneContent>) in your browser and navigate to the [HTML folder](<https://github.com/Timwi/KtaneContent/tree/master/HTML>).
        2. Type in the name of the manual followed by `.html` and select the correct option. Example gif trying to find `Not Colored Squares.html`
           ![gitSearch](https://github.com/user-attachments/assets/dc1ec06f-db96-499f-95a3-b38985c6d405)
        3. Press the download button in the top right of the file and replace the old version of the mod
        ![image](https://github.com/user-attachments/assets/6198734f-2126-46c9-8d2a-39d5033883f9)
    2. **Make your changes**
    3. **Lint your manual** the same way you did while creating the manual.
    4. **Publish your changes for review**. These are the same steps as uploading a new manual. Run [How do I add my manual to the repository of manuals?](https://github.com/BlckHawker/test/edit/main/README.md#how-do-i-add-my-manual-to-the-repository-of-manuals) and look at step two for more details.
## How long does it take for a request to be fulfilled? Can I speed up the process in any way?
Being a contributor the repository is an unpaid voluntary position. They are not obligated to get requests done within a certain amount of time. Although you cannot make a contributor get to a request faster, you can make the process of reviewing the request faster by following the [Repo Maintainer Responsibilities](<https://docs.google.com/document/d/10rabFJES6avb8ime3Cw5LCd9p0663PbqVqzUrfehYac/edit?usp=sharing>) checklist. It's not necessary to follow all of the steps, but the more that are done correctly, the faster the request will be handled.
## How do I become a maintainer?
To become a maintainer, you must show that you have experience with git and handling requests competently. So you must become a contributor first.

As a contributor, It's recommended having a fork of the [Ktane Content repository](<https://github.com/Timwi/KtaneContent>) so you can easily make PRs. You can then make PRs of requests in [discord repo request channel](https://discord.com/channels/160061833166716928/612414629179817985) (see [How do I add my manual to the repository of manuals?](https://github.com/BlckHawker/test/edit/main/README.md#how-do-i-add-my-manual-to-the-repository-of-manuals) and [I would like to make changes on my manual that is already on the Repository of Manuals.](https://github.com/BlckHawker/test/edit/main/README.md#i-would-like-to-make-changes-on-my-manual-that-is-already-on-the-repository-of-manuals)). Be sure to bip (react to the request with :bip:) in order to notify other contributors that you are working on the request. Once you make your PR for a request, react to the request with :solved: in order to notify others that you have completed the request. Once you have handled enough requests that you feel comfortable doing it, you can then message a maintainer, and they will have a discussion with others if you would be a good candidate. The more requests you handle correctly, the higher your chances are of becoming a maintainer.

## Common Errors
### My text is going through the back of the bomb
* [Text Version of answer](<https://discord.com/channels/160061833166716928/726791283007291474/726794741168996443>)
* [Video Version of answer](<https://www.youtube.com/watch?v=YobuGSBl3i0&t=1554s>)
### My logs aren't appearing in the Log File Analyzer
If you want the following to be shown in the LFA:

- Hello World
 
Verify that your print statement looks like this:
```cs
Debug.Log("[{InsertModNameHere} #{InsertModuleIdHere}] Hello World");
```
OR
```cs
Debug.LogFormat("[{0} #{1}] Hello World", InsertModNameHere, InsertModuleIdHere);
```
The `[{InsertModNameHere} #{InsertModuleIdHere}]` format is what the LFA looks for in order to parse the information into the correct section.

It's highly recommend making your own log function, so you don't have to spell the mod name and id every single time:
```cs
public void Log(string message)
{
    Debug.Log($"[InsertModNameHere #{InsertModuleIdHere}] {message}");
}
```
Of course replace `InsertModNameHere` with the name of your module and `InsertModuleIdHere` with the actual variable name that holds your mod id

## My mod works fine in Unity, but doesn’t in the game.
Open the log in the [Logfile Analyzer](<https://ktane.timwi.de/More/Logfile%20Analyzer.html>) and check if there is a button in the top left called “View Exceptions”. If there is, clicking on said button will show you an exception that was thrown while the mod was running. Fixing the exception will most likely make the mod work in the game.
Some common exception(s):
- **Exception: NullReferenceException: Object reference not set to an instance of an object at: SelectableManager.HandleInteract()**
    - Verify that none of your buttons (objects that have the KMSelectable component, excluding the mod itself) have any children in the inspector. The children variable should have a size of 0. The only time your buttons should have a size greater than 0 is if their OnInteract delegate returns true. See [Why do I have to return true or false while adding a delegate to KMSelectable.OnInteract?](https://github.com/BlckHawker/test/edit/main/README.md#why-do-i-have-to-return-true-or-false-while-adding-a-delegate-to-kmselectableoninteract) for more info.

**Good**

![image](https://github.com/user-attachments/assets/0aca56eb-8550-4c61-9963-8a70c888d9db)


**Bad**

![image](https://github.com/user-attachments/assets/64e5c1e9-db4c-4d9e-9090-49ae8b39f706)






Once you fix the issue(s), update the prefab and rebuild your mod and retest. If you don’t see anything wrong with your project in Unity, update the prefab and rebuild anyway. It’s possible that you changed something without building again. If you are still having issues, ask for help in [discord mod creation channel](https://discord.com/channels/160061833166716928/201105291830493193).
## Failed to build AssetBundle: No assets have been tagged for inclusion in the mod.bundle AssetBundle
Select your prefab in the project window. In the bottom right corner, you will see a dropdown with the name `AssetBundle`, verify the selected option is `mod.bundle`. If you do not see it, make it. You should not see the error building again.
![image](https://github.com/user-attachments/assets/af0b1d11-4e56-4359-b9bc-b1598863a02e)

## I can’t hear my sound effects
* **If you can’t hear it in the Unity, but can in the game**, open the TestHarness’ inspector, and drag/drop your clips inside the variable that says “Audio Clips”

![image](https://github.com/user-attachments/assets/b9a1494f-a765-4780-8c1b-67ad182b40f0)

* **If you can’t hear it in the game, but can in Unity,** verify that the sound effects are added in `mod.bundle` The steps to do so are the same as adding the prefab to `mod.bundle`. See [Failed to build AssetBundle: No assets have been tagged for inclusion in the mod.bundle AssetBundle](https://github.com/BlckHawker/test/edit/main/README.md#failed-to-build-assetbundle-no-assets-have-been-tagged-for-inclusion-in-the-modbundle-assetbundle) for more information.
# Misc
## What is colorblind support, and how do I add it to my mod?
Colorblind support allows players with different types of color vision to play the game without visual impairments hindering their experience. While it's not required for a mod to have colorblind support, it's recommended as not having it will limit its visibility.

To add support, you must add a component called `KMColorblindMode` to the game object that has your mod script. You will be able to access a boolean called `ColorblindModeActive`. This boolean tells if the colorblind mode is enabled. You can then use it to make checks if certain game object (such as text) should appear. Example:
```cs
//assume objects has been assigned through the inspector
[SerializeField]
TextMesh colorBlindText;

[SerializeField]
KMColorblindMode colorblindScript;

void Awake()
{
    //shows the text if it's true, hides it if it's false
    colorBlindText.SetActive(colorblindScript.ColorblindModeActive);
}
```
### How do I get my logging to be "fancy" to have images and dropdowns?
The [Logfile Analyzer](<https://ktane.timwi.de/More/Logfile%20Analyzer.html>) (\"LFA\" for short) is a section on the [Repository of Manual Pages](<https://ktane.timwi.de>) that parses the `output_log.txt` file. The txt file is commonly called the "log" as it pertains all of the log printed statements from each mod. By default it will take each log line and make them their own bullet point. See [My logs aren't appearing in the Log File Analyzer](https://github.com/BlckHawker/test/edit/main/README.md#my-logs-arent-appearing-in-the-log-file-analyzer) for more info. For example, the following debug lines:
```cs
Debug.Log("[The Simpleton #1] a");
Debug.Log("[The Simpleton #1] b");
Debug.Log("[The Simpleton #1] c");
```
Will be shown as the following in the LFA:
- a
- b
- c

Anything else you see in a log is done by the LFA parser and needs to be added through the [Ktane Content repository](<https://github.com/Timwi/KtaneContent>), specifically [Logfile Analyzer Data.js](<https://github.com/Timwi/KtaneContent/blob/master/More/Logfile%20Analyzer%20Data.js>) and [Logfile Analyzer Styling Data.css](<https://github.com/Timwi/KtaneContent/blob/master/More/Logfile%20Analyzer%20Styling%20Data.css>)

**Note**: Although LFA support is a neat feature that improves digestion of information, it should not be relied on as an alternative of good logging. If your mod does not provide the necessary information (e.g calculation numbers, when someone strikes/solves), it cannot be added though LFA. Rule of thumb: Your logs should be easily readable and understandable by anyone who knows the mod without LFA 
- **Bad**
  ![image](https://github.com/user-attachments/assets/e880e109-86a2-41fc-b446-e5306a1e7bdf)

- **Good**
  ![image](https://github.com/user-attachments/assets/c235b9d6-e1ff-4553-a2d2-8f550bb15c89)

- **Good (/w LFA)**
  ![image](https://github.com/user-attachments/assets/95934f38-3cc6-46f5-bf13-cd3afb640790)

### If you would like to request a mod to have LFA support
- Go to the [discord LFA thread](https://discord.com/channels/160061833166716928/1018575584009400350)
- Write the name of the module you want LFA support added to. Bonus points if you provide any of the following as that makes the contributor's job easier:
    - Explanation of what you want to lfa to look like
    - Sketches of the lfa
    - Any logs files (txts). Preferably of all the variations of what can happen (including strikes and resets)
- Do note that LFA is a niche portion of contribution, so do expect long wait times before your request gets done
### If you would like to implement LFA support to a mod
-  Adding LFA support counts as being a repo contributor (see [How do I become a maintainer?](https://github.com/BlckHawker/test/edit/main/README.md#how-do-i-become-a-maintainer) for more details), so you will claim the request in [discord LFA thread](https://discord.com/channels/160061833166716928/1018575584009400350).
-  Open [Logfile Analyzer Data.js](<https://github.com/Timwi/KtaneContent/blob/master/More/Logfile%20Analyzer%20Data.js>) in your IDE and find where the mod will go **based on the module name** in alphabetical order (excluding the word `The` in the title).
-  Once you find where the module goes create an object like so:
    - `moduleID` is the id of the mod
    - `loggingTag` is the the name of the module in the square brackets. In the `Debug.Log` example above, the logging tag would be `The Simpleton`.
    - There is an optional property called `displayName` which can be seen for the mods `ASCII Art` and `Binary Cipher`. This should be only added to the object if the preferred display name is different than the `loggingTag`
```
{
    moduleID: "insertModIdHere",
    loggingTag: "insertLoggingTagHere",
    matches: [
        {
            regex: /.+/,
            handler: function (matches, module)
            {
                module.push("test");
                return true;
            }
        },
        { regex: /.+/ },
    ]
}
```
- Running a log including the targeted module should show all of it's content as a bullet point with the word `test`.
    - The variable `regex` is a sequence of characters that defines a search pattern, primarily used for string matching and manipulation. If something is captured in that regex it will be held in the `matches` variable as an array. The first element will be the entire string while subsequent elements will be the separated matches. If nothing is caught, it will be undefined.
        - [Regex tutorial](<https://www.youtube.com/watch?v=rhzKDrUiJVk>)
        - [regex 101](<https://regex101.com>): Site used to test regex. Highly recommended to paste the content of the log in the bottom textbox, and test what regex targets what you're looking for
    - The regex object in `matches` will work in order of top to bottom. The `return true` statement at the end will make sure that none of the other regex objects are ran through (so no duplicate lines are repeated). It's recommended to **always have `return true` at the end of each handler method**
    - The `{ regex: /.+/ }` object is a catch all so the the line appears as a bullet point just like the default. So pretty much doing the same as the first regex object. You should keep this if there are some logs that you want to be just bullet points, and replace the first object with a different regex statement.
- There are many things you can do for LFA, but the main ones are adding dropdowns and making svgs. It's recommended you ctrl + f and look at other examples in order to figure out what you want to do. Here are some examples to get you started:
    - Add dropdowns: `Directional Button`
    - Add nested drop down: `Character Slots`
    - Add grid of squares in a svg: `Directional Button`
    - Editing a dropdown that has already been pushed: `Forget Us Not`
### Why do I have to return true or false while adding a delegate to KMSelectable.OnInteract?
The [wiki](<https://github.com/Qkrisi/ktanemodkit/wiki/KMSelectable>) states the return value of the delegate specifies “whether it should drill into children”. If you think of the module as a [tree](<https://en.wikipedia.org/wiki/Tree_(abstract_data_type)#:~:text=In%20computer%20science%2C%20a%20tree,a%20set%20of%20connected%20nodes.>), with the module being the root node, you can move to and from other children. A good example of this is the mod [Quadruple Simpleton Squared](<https://github.com/KTANE-MODS/Quadruple-Simpleton-Squared>). The root node is the mod itself, but if we select the top left section of the mod, that will be the current node since the delegate returns true. If we select the top left button, the interaction will occur but the current node will still be the top left section since the delegate of the button returns false. When we right click, the current node becomes the module again.\nIf you do not want any sections of your mod, all your buttons work as standard buttons, then you should have all of your KMSelectable OnInteract delegates return false and have no children. You can read a discussion about this [here](<https://discord.com/channels/160061833166716928/201105291830493193/1289045915117551637>).
![image](https://github.com/user-attachments/assets/41d7c990-6be7-401f-a759-845070fcab78)

