



# The Ultimate Guide to Report Bugs,Non-conformities and Improvements



- Introduction
- Bugs
  - Card template for bugs
  - How to report bugs - walkthrough
  - How the report card looks on Jira
- Non-Conformities
  - Card template for non-conformities
  - How to report non-conformities - walkthrough
  - How the card looks on Jira
- Reporting layout problems
- Card template for layouts
  - How to report layout - walkthrough
  - How the layout card looks on Jira
  - Improvement suggestions
- Card template for improvements
  - How to report improvements - walkthrough
  - How the improvement card looks on Jira
  - Recommended tools to record videos and take screenshots
- Severity





# Introduction
This document is to guide the user on how to report bugs, nonconformities and improvements to the development team, from how to be objective in their description, what information is important, to how evidence is vital on the process to inform the team of an issue without relying heavily on one-on-one communication in order to understand the process.




Non-Conformities
Non-conformities are behaviors / functions / layout that are implemented in the system, but their behaviors or visuals differ from what was requested/expected by the product owner or higher management. It depends on the project organization, but some teams decide to put them in the same category as “bugs” despite their differences.

Card template for non-conformities

Title

[Description]

[image attachment]

Current Behavior:
System behaves like this.

Expected Behavior:
System should behave like this.

[video attachment]


How to report non-conformities - walkthrough:

Reporting functionality problems:

Title: It follows the same rules from bug titles, it must quickly explain what is happening and where.

Description - brief description of what the non-conformity is about
Ex: Buttons are not the same color and size as the prototype.

Current behavior: describes what is happening in the system at the moment.

Expected behavior: describes the actual way the system should behave. 
How the card looks on Jira:


Reporting layout problems

When a project has high fidelity prototypes, it is necessary to inspect each detail to see if the system mirrors it. But even without prototypes, this can also apply for layout errors.

Card template for layouts
Title

[Description]

Prototype
[link to the prototype]


Current layout:
Component currently looks like this:

[Image attachment of the component]

Expected layout:
The component should look like this:

[Image attachment of the component in the prototype]

[video attachment if necessary]


How to report layout - walkthrough:

Description - brief description of what the non-conformity is about.
Ex: Buttons are not the same color and size as the prototype.

Current layout: how the front-end is implemented in the system.
Expected layout: how it should look based on the prototype.


How the layout card looks on Jira:




Improvement Suggestions

During development, the team or the client will have ideas to improve the system. These cards need to be described in a way that it clearly shows where and why this improvement should be implemented.


Card template for improvements

Title

[argumentative description]

[image showing where the change should happen]



How to report improvements - walkthrough

Title: Again, it has to be succinct and indicate what feature, behavior or component should be improved. Ex: Display confirmation toast to inform the user that the invite was successfully sent.

Argumentative description: Explain the reason why this improvement should be implemented. Present the problem and the solution. Ex:Currently, when the user sends an invitation to a party, nothing on the screen shows up, and the user has no way of knowing if the invitation was actually sent. Having a toast informing that this action was completed could greatly improve user experience.
Image: It’s how the saying goes “an image is worth a thousand words”. The image helps anyone that reads the card to know where you want the change to happen.









How the improvement card looks on Jira:





Recommended tools to record videos and take screenshots

Screenshots:
For windows: Windows + Shift + S;
For other devices: Lightshot
Vídeos:
For windows: Xbox Game Bar (Windows + G)
For devices that do not meet the criteria for Xbox Game Bar: Screenpresso

Severity

When reporting  bugs, there are classifications to determine how much the bug influences the usage of the system and how critical it is for it’s overall performance.Here are the most generic classifications:

Minor
Annoyance, and doesn't need a workaround

Major
Creates problems, has a known workaround
	
Blocker
Prevents usage and no known workaround

