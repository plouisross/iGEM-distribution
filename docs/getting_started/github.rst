Riding Herd on "Git"Hub - A view from the Saddle
================================================

These days a cowboy’s in a tough spot.
Farms are getting bought out, rodeos are going bust, and all these new-fangled robots are taking our jobs.
So what’s a cowboy to do?

“Get off the ranch and go into coding”.
That’s what the counselors at the Cowboy Retraining Center in Travis City told me.

.. sidebar::

    .. image:: /_static/cowboy.png

But I wasn’t ready to get off the ranch just yet.
Anyhow, where would I go? 
Then one of them told me I could code from the ranch, “remote working”, she called it.
Now, I’ve been working “remote” my whole life.
It’s what being a cowboy is all about.
The idea that I could continue to work ‘remote’ appealed to me.
So I decided to give it a shot.

Now, I’ll level with you, that first day of coding training was tough. 
Variables, Functions, Loops.
None of that stuff made much sense to me.
And Python, as any cowboy knows, is a critter you need to dispatch - and quick – when you spot one on the trail!
But then just when I was about to throw in the towel and ride off into the sunset, the instructor tells us that the next lesson is going to be on something called “GitHub”.
I almost fell out of my saddle and, believe me, that’s not something a cowboy does very often. “This is one thing I do know something about,” I said to myself.

Seems “GitHub was invented by a guy named ‘Torvalds’, Swedish fella.
Now I’ve met some Swedish farmers around these parts, but in my experience they don’t make for very good cowboys.
So I’m already a tad suspicious.
Anyway, ‘Git”, according to this Swedish fella, means “Goddamn Idiotic Truckload of Sh*t”.
Now if there’s one thing I can’t abide it’s cussin’, especially when there are children present and if there’s another thing, it’s Swedish farmers telling lies.
Believe you me this Torvalds fella is lying.
Any cowboy worth his spurs knows that “Git” is what you yell at the herd of cattle to get them to take their heads out of the grasses and their little hooves moving down the trail.
So without wasting any more time trying to figure out what “Git” means let’s saddle up and starting using it.
“Git”!

Now the first thing a cowboy does when he’s riding into unfamiliar territory is to find the highest point – a bluff, a butte, the top of a mountain, what have you – to get the lay of the land.
(I know it’s tough to see, but that’s me there on top Bartlett mesa just outside of Raton).
From this vantage point, you can get the big picture: Process flows (streams) and Files.
Before we follow those, our first stop is to head into the town just over the next ridge where we can pick up some supplies – provisions and intel.

.. sidebar::

    .. image:: /_static/bluff.png

Communication/Issues
--------------------

The best way to figure out what’s going on around here is to mosey on over to the General Store and scan the items on that notice board hanging by the side of the door.
You can do this In GitHub by going to the top bar (ribbon) and clicking on the “Issues” tab.

.. sidebar::

    .. image:: /_static/bank.png

Once you click on “Issues” you’ll see what looks like a bulletin board where people working on the project have listed problems. concerns, and challenges they’re facing and where they’re looking for help.

Issues related to the Distribution Project fall into a few basic categories: Reviewing (packages, ), Developing, and Supplementing.
Some of the issues have little labels next to them that make me think of the brands on the flanks of my cattle.
These indicate the type of issue (e.g. “automation”) and the status (e.g. “Help Wanted”).

.. image:: /_static/issues.png

If you’re a greenhorn just starting out, look for issues that have a label like this:

.. image:: /_static/good_first_issue.png

If you see an issue you want to try and tackle you need to assign it to yourself as a first step.
To do that, click on the heading of that issue and a full profile of the issue you’re interested in will appear.
On the far right you’ll see a column of headings.
The first heading is “Assignee”.
The status under “Assignee” should read “No one assigned”.

Click on the wheel symbol next to the word “Assignee” and a directory that lists the names of all the project’s participants will appear.
Scroll down to your name (the first name on the list, by default) and click on it.
A check mark will appear to the right of your name.
To confirm the assignment click on the wheel icon again and verify that your name now appears under the “Assignee” heading.
Congratulations!

.. Attention:: If your name doesn’t appear on the drop-down list you will need to request access from either Vinoo Salvarajan or Jake Beal  (sending a note via the Slack channel).

So now its time to sign on to first project and get started.


(Illustrate using a real example here)


Organization
The GitHub file organization structure reminds me of a set of those Russian dolls, each one nested in another one that’s just a little bit larger.   The biggest one is the Repository.  The next largest after that is the Folder.  And then there is the File.  So let’s look at each one of these.  “Git !”












Repository (“Repo”)
A lot of folks call the Repository, “Repo” which to me was a bit confusing at first.   That’s because back when I was growing up “Repo” meant only one thing … The fella from the bank was coming out to take back our pickup. “Payment overdue,” he shrugged as he put the key in the ignition and drove the truck back into town.  

Seen from under the brim of a ten-gallon hat,  the GitHub “Repository”  looks like one big barn.   But instead of being a place where you keep your chickens, your horses, your geese and all manner of farm implements.   It’s  more like one big trough that holds all the files, issues, etc. related to the GitHub project you’re working on.   

You can find the name of the Repository for the Distribution Project:  iGEM -distribution  highlighted in blue color at the top of the ribbon.  I took a snapshot of it for you here:

 

Cloning
One of the most common things people do with Repositories is to “clone” them.  “Cloning”  sounds like a fancy word, but all it means is copying the contents of the Repository – the whole kit-and-caboodle (files, commits, and branches) - to your own computer.    Having a copy of the project’s repository on your computer makes it easier for you to work with the contents such as adding and removing files,  pushing commits, xxxx. 

The first thing you have to do to “clone” the Repository is click on the green “Code” button 


(The “Code” button is located to the right the “Add File” button and to the left of the “About column)

and choose “Clone” open from the dropdown menu that appears. 
 

Folder
To create a new folder in a repository click “create a new file.” Type your new folder’s name in the area where you would write the file name, and at the end of the file name type a “/” to designate it as a folder. After this you can create a new file in the folder
File
Navigate to the main page of the iGEM distribution project repository  (iGEM -distribution )   Once you’re in the  iGEM -distribution repository, browse to the folder where you want to create a file.  
To create a new file, click the ‘Add File’ button 
  
Above the list of files, using the Add file drop-down, click Create new file. "Create new file" in the "Add file" dropdown.  
 

This is what will appear
 
In the circle that looks kinda’ like the ring at a rodeo you’ll see the words “Name Your File” in gray.  This is where you write the name of the file you want to create.  Make sure it’s a name that relates to the content of the file. 
In the big while space below, what I call the “Open Range”, that’s where you want to enter the content.  After you’ve added all the content you can click “Preview” to see how it looks.  

At the bottom of the page, just below the “Open Range” where you’ve just entered all your content, you’ll see another box, smaller size,  called “Commit New File”.    
 
Now, when I was growing up “Commit” had only one meaning…. It’s what my uncles figured they had to do with great-aunt Betty when she couldn’t find the chicken coop anymore or even tell a bull from a cow.    In Git language, “Commit” is like saving a file.  So go ahead and type a short message that describes what you’ve done in the box provided.  This is sort of like a diary or journal entry.   
[this then will be the transition to the next part about “Process and Flow” that expands on “Commit” and positions it within the larger process flow that includes “Pull Requests” etc.]

Actions/Process   
The instructor of our coding class told us there was going to be an examination tomorrow on everything we’ve learned about GitHub and I’m hard put to figure out how to keep all those danged steps straight.  
I’ve spent the whole night just saying “Branch-Commit-Pull-Accept”, Branch-Commit-Pull-Accept” … “Branch-Commit-Pull-Accept”  over and over again hoping it would stick.  The only ones paying any attention to what I’m saying are a few coyotes sitting up on the ridge over there and even they’ve had enough.  Seems they’ve come up with their own version.  
As a “do-or-die”  cowboy I knew I had to keep going.  And suddenly as I repeated:  “Branch-Commit-Pull-Accept” … “for the 375th time,  it suddenly hit me.  “Branch-Commit-Pull-Accept” , “Branch-Commit-Pull-Accept”  is like the sound my horse Silver’s hooves make when he’s trotting along the trail.  Cowboys being naturally musical folk, I picked up my guitar and composed a little ditty on the spot, inspired by “Branch-Commit-Pull-Accept”.     I’ll strum the first few bars for you here:
The sound of hooves
To a cowboy’s ear,
Is music of the sweetest strain;

And the “giddy’yap go”
Of the GitHub flow
To him are a glad refrain.

The Comanche say that a good chief can “speak” the language of trees.  What they mean is that a tree-savvy chief can find water, shelter, even a fast-food joint just by studying the trees he encounters and understanding what they’re telling him.   

I believe that the chief of a Comanche tribe would feel right at home with GitHub because all the most effective GitHub users I’ve heard about know something about trees.  Hell, the entire Git structure is organized like a tree – it’s all about branches, roots,  and such like.   

Whether you want to be a proficient GitHub user or you have aspirations of becoming the chief of a Comanche tribe, the first step, and by far  the most important thing you have to learn,  is how to create a branch.  




Branch
GitHub is a platform built for collaboration, but there is always a tension between people collaborating and at the same time working on their own part of the project.  Things can very messy when a lot of people are working on a project and trying to make changes or add to it.   The way GitHub avoids potential problems is by having anyone who wants to make a contribution to a project use a branch.  To add anything new or to make changes to an existing project  you create a branch.  Think of a branch as your own development space that lies outside of the project flow.

Branches are the set of code changes that correspond to the edits,  additions,  and changes you want to make.  Once you’ve completed making changes in your branch you are working in you can follow the following steps to have the branch with the changes integrated into the project, represented by the Main branch.    

The Main branch is, conceptually, sort of like the trunk of a tree.  It’s the current version of the Distribution project and is what you are looking at when you visit the Distribution project repository at  iGEM Engineering/ iGEM -distribution. 





How to create a new branch
On GitHub.com, navigate to the main page of the repository.
Optionally, if you want to create your new branch from a branch other than the default branch for the repository, click  NUMBER branches then choose another branch:
Click the branch selector menu.
type a name for your new branch, preferably one that describes what the branch is about.  then select Create branch.


Commit
Now where I come from “Commit”  has only one meaning….  It’s what a self-respectin’ fella does  when meets a gal at the Saturday evening square dance down by Foster’s barn and decides she’s the one.   But I was sorely disappointed to find out that in GitHub, a “Commit” is nothing more than making a change to a file and saving it.   

When you “make a commit” to save your work, Git automatically generates a unique ID for it that makes it possible to keep track of the changes that were committed as well as a record of who made the changes and when.  git commit creates a commit, which is like a snapshot of your repository. These commits are snapshots of an entire repository at a specific time.  Commits usually contain a commit message which is a brief description of the changes that were made.
Pull Request
A Pull Request is in effect a request to Jake or Vinoo, the administrators of the Distibution project repository, to review  changes you propose and approval to merge the new code changes in the project repository (Main branch).

The Pull Request process was put in place to ensure that unfinished or incorrectly written updates would not be prematurely merged with the main repository.  It is a way of maintaining the quality of the content and the integrity of the project by only merging code that has been appropriately reviewed and approved.  Pull requests also encourage collaboration and open communication when working on new product updates and keep teams motivated by highlighting and notifying the team when someone completes a new feature.

Contributions.  Different types of contributions.  What they entail.  What is expected (detail) – graphics.  

