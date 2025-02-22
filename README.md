# Committing Exercise 1

## Scenario

Imagine you are organizing a long-awaited adventure. To keep your travel plans in order, you decide to use Git for version control. In this exercise, you will create a repository to manage two important files: one for your travel itinerary and another for your budget details. You will practice initializing a Git repository, creating files, staging changes selectively, and reviewing your commit history. Follow the steps below to simulate tracking your travel plans with Git.


## Instructions

**1. Create the Project Folder:** Create a new folder named **TravelPlanner**.

**2.Initialize the Repository:** Initialize a new git repo inside of the TravelPlanner folder (make sure you're not already inside of a Git repo!)

**3. Create Initial Files:** Create a file named itinerary.txt

**4.** Create another file named budget.txt

**5.** Make a commit that includes both empty files.  The message should be "itinerary and budget"

**6. Open itinerary.txt and add the following lines:**

```
- Paris: Visit the Eiffel Tower and Louvre Museum
- Rome: Explore the Colosseum and Vatican City



Add Budget Details:
Open budget.txt and add:

bash
Copy
- Paris: $1500
- Rome: $1200
Commit Itinerary Changes:
Stage only the changes in itinerary.txt and commit with the message:
"Add initial travel destinations and activities"

Commit Budget Changes:
Stage only the changes in budget.txt and commit with the message:
"Add initial budget estimates"

Update Both Files:

Append a new line to itinerary.txt:
diff
Copy
- Berlin: Tour the Brandenburg Gate and Museum Island
Modify budget.txt by updating the Paris budget to $1600 and adding:
bash
Copy
- Berlin: $1000
Commit Combined Changes:
Stage the changes from both files and commit with the message:
"Update itinerary with Berlin and revise budget details"

Review Commit History:
Use a Git command (for example, git log --oneline) to display your commit history. You should see exactly 4 commits!
