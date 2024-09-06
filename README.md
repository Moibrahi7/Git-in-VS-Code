## Using Git in VS Code
In this guide, I will tell you how you could use git through VS code making your life significantly easier than before. Am I saying you will never have to use the command line? technically as far as VS code is concerned with pushing and pulling from Git Hub. You do not have to use the console except when you would need to roll back after pushing changes, let’s get started.

## What Should You Know
The knowledge that you should still have an idea of how to use Git commands in the command line. While using git in VS code is very convenient, you will eventually need to use the command line when you have to move away from VS Code.

### Step 1
Open VS Code. Locate your local repo or if you have already opened the repo before with or without using a Dev Container you can find it in a list of 5 items below the section labeled recently opened. If you re-opened a Dev Container repo you opened before skip to Step 5.

<img src = "PicsForGuide/1 OpenVSC.png" href = "VS Code Home Page"/>

### Step 2
After opening a repo look in the bottom left of VS code and click on the icon that looks like the image below.

<img src= "PicsForGuide/3 howVSCLookswithnoDevP2.png" href = "Dev Container icon with no container"/>

### Step 3
After clicking the icon, a drop-down menu should open in the top middle of the screen. Once you locate the menu click re-open in Dev Container. (As a side note ensure that  is running in the background. If it's not running the Dev Container will not open.)

<img src= "PicsForGuide/4 reOpenDC.png" href= "Dev Container drop down menu"/>

### Step 4
To ensure the Dev Container is running properly look back at the bottom left corner of VS code where the icon was, and it should look like the picture below.

<img src = "PicsForGuide/5 IfYouAreinDCbottom.png" href = "Dev Container after Connecting" width = 300px />

### Step 5
After checking you are in the Dev Container and locating the file you want to make changes to you can start looking for the Source Control icon as seen below.

<img src = "PicsForGuide/6 IfYouAreinDCOpenSC.png" href = "Source Control icon" width = 300px />

### Step 6
On top of ensuring you locate Source Control, you also need to make sure you are on the correct branch, or if you don't have a branch how you could make one. To tell if you are on the correct branch you can navigate back down to the bottom left of VS code and look right next to the blue Dev container information. If it says main you are in the wrong branch.

<img src = "PicsForGuide/7 CheckBranch.png" href = "Main branch display"/>

#### Below is the image guide with some text for making a new branch
1. Click on where it displays the current branch name in the bottom left. Afterward, another drop-down menu will open and you will click on create a new branch. (If you are looking to just change branches you can select from existing branches from the same drop down.)

<img src= "PicsForGuide/8 MakeNewBranch.png" href = "Drop down for making new branches"/>

2. Next you would put in a branch name and hit enter as shown below.

<img src = "PicsForGuide/9 EnterBranchName.png" href= "Text box for inputting name"/>
<img src = "PicsForGuide/10 BranchNameEntered.png" href = "Text box With branch name">
3. Ensure you are on the correct branch by looking the the bottom left corner again and it should look similar to the image below.

<img src = "PicsForGuide/11 HowItshouldLookonBranch.png" href = "Dev Container with branch name"/>
4. Finally, if you are on the Source Control Tab it should look like the image below. (You can choose to publish the branch now or latter either is fine.)

<img src = "PicsForGuide/12 howSCShouldLook.png" href = "Source Control with new branch" width = 300px />

### Step 7
Start making changes whatever changes you need to make.
### Step 8
After making your changes navigate to the Source Control tab and it will probably look a little like the image below.

<img src = "PicsForGuide/13 afterChanges.png" href = "Source Control with all the changes made since last commt" width = 300px />

Now I know this looks like a lot of stuff. Probably a lot more stuff than what you remember changing. The reason a lot of these files change is due to how the Dev Container works, it constantly modifies the file and changes values for it to work and it is imperative that you only choose the items you want to commit. But first, you have to locate them in this list.

<img src = "PicsForGuide/14 afterChangesp2.png" href = "Source Control with all the changes made since last commt with the files I want to commit highlighted" width = 300px />

Now you are ready for the next step.

### Step 9
Now that you have figured out which files you want to commit it's time to stage them. You can stage an item by hovering over the name of the icon with your mouse and you should be able to see a "+". Once you see that + you can click on it and then it will be staged. With that if you stage an item that you did not mean to stage in the staged items section you hover over the name of the item you want to remove and after that, there should be a "-" sign that on click would unstage your item. Below are images of them being staged, the + sign, and the - sign.

<img src = "PicsForGuide/15 ToStageAChange.png" href = "Source Control with with the Stage changes sign highlighted" width = 300px />

<img src = "PicsForGuide/16 unstageChange.png" href = "Source Control with an item staged that was needs to be removed" width = 300px />

<img src = "PicsForGuide/17 afterStageingChanges.png" href = "Source Control with the items need staged" width = 300px />

### Step 10 
The next step is committing, in the Source Control section you can also commit your changes. First, you have to enter a commit message and then click commit. As shown in the images below. 

<img src = "PicsForGuide/18 enterCommitMessage.png" href = "SC with commit message and commit button" width = 300px />

### Step 11
After commiting there will be a new section that will appear right below the changes section called Outgoing with the name of the branch that is receiving the commits. In the case you commit something that you do not want to commit you can undo the last commit with the three dots at the top of the Source control menu on the right, next to the refresh sign. The image below will show how the new section would look in the Source Control tab.

<img src = "PicsForGuide/19 afterCommiting.png" href = "SC with outgoing changes" width = 300px />

### Step 12
If you have published your branch. The final step you have on making changes to your GitHub repo is to push these changes and to do so you must navigate to the circle with an arrow pointing up when the name of your branch is highlighted under outgoing as shown below.

<img src = "PicsForGuide/20 toPush.png" href = "push sign is displayed" width = 300px />

### Step 13
After you tried to bush you got a message that looks like the image below. 
<img src = "PicsForGuide/21 MessageAfterPushOnNewBranch.png" href = "publishing error"/>

To work around this you will click ok as shown in the image above and a dropdown menu in the top middle with appear to add an origin. Will click on your Forked repo and then it will commit those changes the menu looks like the image below.

<img src = "PicsForGuide/22 addOrginRemote.png" href = "Remote seting pull down on VS code"/>

### Extra Step
In the case that you do not update your git repos often you can update the repo by clicking the sign below to do a pull, fetch, and push.

<img src = "PicsForGuide/23 fetch.png" href = "The sign to sync your changes and fetch changes"/>
	
