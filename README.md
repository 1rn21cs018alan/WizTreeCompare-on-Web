# WizTreeCompare-on-Web
A wiztree scan comparing program designed to run in browser (regular html css js)
<br>
<br>
At the time of this project being uploaded, the existing comparision software required .NET and I didn't want to install stuff again (running out of disk), hence this project exists
# How To Use
1. Get the 2 CSVs of the WizTree scans you've done
2. drag and drop the old scan's CSV to the left slot and new to right slot
3. Click the `Generate Diff Tree(Unified)` button and the differences between the 2 scans will be shown
# Diff Tree Color Scheme
1. Strong Red = File/Folder Deleted
2. Strong Green = File/Folder Added
3. Light Red = File/Folder has decreased in size
4. Light Green = File/Folder has increased in size

# Potential Improvements
1. Based on some reddit comments, I've added a computed allocations and computed deallocation in the internal tree object (not the visible HTML document). Anyone can feel free to fork this repo and modify the rendering logic to display the contents in your preffered format
2. The Tree structure I've used is not very memory efficient, there definitely are some optimisations that are possible

# AI Use
This Code is Partially AI Generated
(My.Skills.Frontend = null)
