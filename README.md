# Introduction:
This is a project to create an online system that lets users keep track of seasonal activities.

# Website Address:
It has already been uploaded to my school website:  
https://i6.cims.nyu.edu/~st3890/webdev/macro_assignment_05.html

# Requirements:
Layout:  
1. Some kind of header to introduce your page.  
2. Four tabs that allow the user to select from four different seasons. The first tab / link should be visually distinguished in some way to show that it is currently selected.  
3. A content window associated with each tab. The two tabs that are not currently activated should have their content windows hidden when the page loads. Each tab should contain a description of the activity type, a text box and a button.  
4. A "corkboard" that will contain all of the activities that have been added to the log.  
5. A drop-down menu that will allow the user to "filter" by season.  

Tabbing Logic.  
1. Clicking on a tab should change its design in order to show it's 'active' status.  
2. Clicking on a tab should display the corresponding content window below the tab. The other content windows should hide themselves.  

Entry Logic.  
1. A user should be able to type into a seasonal text box and click the 'Add Note' button. When this happens a new "Sticky Note" should appear in the activity panel. Each note should be visually distinguishable (i.e. 'winter' entries will have a different background color than 'summer' entries).   
2. If the user does not type a value into the text box and clicks the button the system will detect this and prevent an empty entry from being added to the list.  
3. Entries should be added to the activity panel in chronological order, with the latest entries showing up on the right side of the panel.  
4. When you hover over a note a button should appear at the top right side of the entry. This button can be used to delete that particular entry.  
5. The 'Filter' drop down menu should let the user view all entries of a particular type, or view all entries regardless of type.   

More Advanced Features:  
1. Completed Event: add an additional button to each note to indicate that an event is 'complete' - i.e. if this was a 'to-do' list clicking on this button would cause the item to be 'checked off' as complete. Completed events should have some kind of visual indicator attached to them (a checkbox?). Also allow completed events to switch back to being 'un-completed'. The filtering system should also be updated to filter completed / un-completed items.  
2. Edit events: add an additional button to each note that allows the user to edit any event. The edit button should display some interface that lets the user change the text of the event as well as the category of the event. This can be a pop-up interface (modal box) or an in-line editing interface as is showin in the video - your choice.  
3. Reorder events: add two additional buttons to your notes which will allow them to move left and right in the list. Clicking on the 'left' indicator will move the element left by one position, and clicking on the 'right' indicator will move the element right by one position. If an element is already at the beginning of the list it should not be given an 'left' indicator, and likewise an entry at the end of the list should not be given a 'right' indicator.  
4. Delete Multiple Events (not shown in the video): delete multiple notes at the same time based on the current filter choice. For example, if the user is filtering to show only 'summer' then all summer notes will be deleted. If the filter is showing all entries then every entry should be deleted.  
