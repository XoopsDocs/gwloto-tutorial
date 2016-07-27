# 5.0 The User Side

# **User Functions**

## **_Place Functions_**

### **Place Browser**

The Place Browser is the primary navigation screen for gwloto. In addition to the Place Bar and Action Menu, it will display a list of any control plans associated with the current place, the hazard inventory and required personal protective equipment defined for the current place, a list of any media attached to the current place, and a list of any active jobs the user may have access to.

The place bar can be used for navigation between places by selecting a new current place.

### **Add a New Place**

An option to add a new place will be shown in the Action Menu if the user has edit authority for the current place. Enter the details for the new place, click the "Add" button to add the place. Places are always added as children of the current place.

The following fields are available.

* Place Name - A short name for this place

* Hazard Inventory - An inventory of the hazard present in this place. If supplied, this will become the default for all control plans for this place.

* Required Personal Protective Equipment - The PPE requirement for this place. If supplied, this will become the default for all control plans for this place.


### **Edit Places**

An option to edit the current place will be shown in the Action Menu if the user has edit or translate authority for the current place. With edit authority, one can edit the place record in the current language. With translate authority, one can edit any language version, except the default language, or add a translation in a new language if one does not yet exist.

The fields are the same as listed above in "Add a New Place."

### **Set As Home**

An option to Set As Home will be shown in the Action Menu if there is a valid current place selected. Setting a place as home will make it the first place shown on entry to gwloto. Depending on the place structure and authorities assigned, using a home place could save many steps in a typical workflow. The user can change the home place at any time.

## _**Control Plan Functions**_

### **Start New Energy Control Plan**

An option to add a control plan will be shown in the Action Menu if the user has edit authority for control plans at the current place. Enter the details for the new plan, click the "Add" button to add the control plan. A new control plan is always assigned to the current place.

The following fields are available.

* Control Plan Name - Descriptive name for the control plan

* Reviews / Approvals - Indicate the review and\/or approval status of the control plan

* Hazard Inventory - The hazard inventory present when executing this control plan. If left blank, the hazard inventory for the parent place will be shown when the control plan is displayed.

* Required Personal Protective Equipment - The PPE requirement for executing this control plan. If left blank, the PPE requirements for the parent place will be shown when the control plan is displayed.

* Authorized / Required Personnel - Indicate the personnel that are authorized or required to execute this control plan.

* Additional Requirements- Indicate any extra safety equipment or other dependencies required for the execution of this control plan.


### **View Energy Control Plan**

An option to view a control plan will be shown in the Action Menu if the user has view, edit or translate authority for control plans at the current place, and a control plan is associated with the current page.

The fields are the same as listed above in "Start New Energy Control Plan" with the addition of:

* Counts - shows total numbers of control points, locks required and tags required

* Last Updated By - The user making the last update

* Last Update Time - date and time the last update was made

* Point Sequence - select disconnect, inspection or reconnect order for control point list


Also shown are a list of control points associated with the current plan, a list of any media attached to the current plan, and, if the user has translation authority, some basic statistics on the number of translated control points and the latest modification time.

### **Edit Energy Control Plan**

An option to edit a control plan will be shown in the Action Menu if the user has edit or translate authority for control plans at the current place, and a control plan is associated with the current page. With edit authority, one can edit an existing control plan record in the current language. With translate authority, one can edit any language version, except the default language, or add a translation in a new language if one does not yet exist.

The fields are the same as listed above in "Start New Energy Control Plan."

### **Add New Energy Control Point**

An option to add a control plan will be shown in the Action Menu if the user has edit authority for control plans at the current place and a control plan is selected. Enter the details for the new control point, click the "Add" button to add the control point to the current control plan.

The following fields are available.

* Control Point Name - A descriptive name for the control point

* Locks Required - The number of locks required to secure this control point. Defaults to one.

* Number of Tags Copies - The number of tags needed to secure this control point. Defaults to one.

* Disconnect State - The de-energized state for this control point.

* Disconnect Instructions - Instructions to safely de-energize this control point.

* Inspection State - The state expected for this control point during inspection.

* Inspection Instructions - Instructions for the inspection of this control point.

* Reconnect State - The normal, or energized state for this control point.

* Reconnect Instructions - Instructions to safely energize this control point.


### **View Energy Control Point**

An option to view a control point will be shown in the Action Menu if the user has view, edit or translate authority for control plans at the current place, and a control point is associated with the current page.

The fields are the same as listed above in "Add New Energy Control Point" with the addition of:

* Last Updated By - The user making the last update

* Last Update Time - date and time the last update was made


Also shown are a list of control points associated with the current control plan.

### **Edit Energy Control Point**

An option to edit a control point will be shown in the Action Menu if the user has edit or translate authority for control plans at the current place, and a control point is associated with the current page. With edit authority, one can edit an existing control point record in the current language. With translate authority, one can edit any language version, except the default language, or add a translation in a new language if one does not yet exist.

The fields are the same as listed above in "Add New Energy Control Point."

### **Reorder Energy Control Points**

An option to sort control points will be shown in the Action Menu if the user has edit authority for control plans at the current place, and a control plan is associated with the current page.

* Actions - Action to take with the selected control point or list

  * Move Up - Moves the selected point up one position in the list

  * Move Down - Moves the selected point down one position in the list

  * Reverse - reverses the order of the entire control point list

  * Save - saves the current order of the list to the selected sequence


* Control Points - Ordered list of control point names. Click a point to select it

* Sequence to Set - Choose for Save or Re-Show, disconnect, inspect, reconnect

* Re-Show - reload data for the chosen sequence


## _**Media Functions**_

### **Browse Media Files**

This is the main entry point for the Media Center. An option to enter the Media Center will be shown in the Action Menu if the user has browse or edit authority for media at the current place.

A list of available media items is shown. Options to restrict this list by category or search term are shown above the list in the media toolbar.

### **Add New Media File**

An option to add a media file is shown in the Media Toolbar in the Media Center. To add media, the user must have add or edit media authority at the current place. Enter the details for the new media item, click the "Upload" button to add the media item.

* Media Name - A descriptive name for this media item

* Place for Authority - The place to use for determining user authority to use this item.

* File to Add - When uploading a file, use the "Browse" button to locate the proper file.

* Link to Media - A media item can also be a link to another network resource, such as a web page.

* Classification - The classification of this media item. Available classifications are permit, form, diagram, instructions, manual, material safety data sheet, and other.

* Description - A description of this media item.


### **Media Details**

This option will display the details of the media item. The fields are the same as shown in "Add New Media File" above. If the user has edit or translate authority, the data can be edited. Editing may include uploading a new version of the item.

Translation authority can be used to add a new translation or edit existing translations. Translations can include translated names and descriptions, and may also include alternate versions of the media file or link.

With the appropriate authority, a media item can also be deleted from this page. Deleting the default language version will delete all translated versions as well. Deleting a non-default language item will only remove the translation for that language.

### **Attach Media File**

An option to attach a media file will be shown in the Attached Media section of the Edit Places, Edit Control Plan or Energy Control Job pages. Choosing this option will enter the media center. Use the available options to locate an existing media item, or add a new media item. Then click the select button to bring up the attach options:

* Check to marked as Required.

* Check to attach additional media.


After setting the attach options, click the Attach button to complete the operation.

### **Detach Media File**

An option to detach a media file will be shown in the Attached Media section of the Edit Places, Edit Control Plan or Energy Control Job pages. Check the item in the "Select" column, and click the "Detach" button. Confirm the action, and the media item will be detached.

Detaching a media item does not delete the item from the media center, it only removes the association with the current place, plan or job.

## _**Job Functions**_

### **Start New Energy Control Job**

An option for new job with this plan will be shown in the Action Menu if the user has edit authority for jobs at the current place and a control plan is selected. Completing this process will create a job with a single step consisting of the current control plan. On successful creation, the user is redirected to the energy control job overview in edit mode. If more than one control plan is to be included in the job, plans can be added there.

* Job Name - A descriptive name for the job

* Work Order - the work order or control number associated with the job

* Supervisor - the supervisor over the job. The supervisor can be chosen from a list or manually entered. The supervisor list is populated with all users with "Supervisor of Place" authority in the current place context.

* Planned Start Date

* Expected Completion Date

* Job Description - a description of the work to be performed

* Control Plan - shows the name of the control plan associated with the new job.

* Step Name - a short descriptive name associated with the control plan being added.

* Assigned To - the user overseeing the execution of the control plan. By default, this is the user creating the new control plan, but any user with job edit authority can be chosen from the drop down list.


### **Energy Control Job Overview**

This option will display the details of the current job. Most fields are the same as shown in "Start New Energy Control Job" above. If the user has edit authority, the data can be edited.

The unique fields on this page include:

* Job Status - A new job is assigned a status of 'planning'. The available job status designations are planning, active, complete and canceled. A status of complete or canceled will cause the job to disappear from most views. The list of jobs is shown in the place browser includes the job status set here.

* Job Tools - May include buttons to Save, Add Step or Print based on the user's authority.


### **Energy Control Job Step Detail**

This option will display the details of a single job step. Most fields are the same as the step related fields shown in "Start New Energy Control Job" above. If the user has edit authority, the data can be edited.

The unique fields on this page include:

* Step Status - A new job step is assigned a status of 'planning'. The available job step status designations are planning, disconnecting, disconnected, reconnecting, reconnected, inspecting, inspected, complete, canceled. A status of canceled will exclude the step from job printing functions unless it is explicitly selected. The list of job steps shown in the energy control job overview includes the step status set here.

* Job Step Tools - May include buttons to Save or Print based on the user's authority.


### **Add an Energy Control Job Step**

An option button to add a step is shown on the Energy Control Job Overview when the user has job edit authority. The current job information will be captured, and the user is taken to the place browser to locate the control plan to be added to the job. When an eligible control plan is displayed, a clipboard operation block will be shown giving you the option to add the control plan to the job. Clicking the Add to Job button will add a new job step with the displayed control plan and bring you to the energy control job step detail page in edit mode for the newly added step.

### **Print Energy Control Job Documents**

Energy control job documents can be for an entire job, or just one selected job step. The display will include a summary of the job or job step that has been selected. The summary includes fields listed above under Energy Control Job Overview and Energy Control Job Step Detail as well as the following:

* Select what to print - this list shows all of the installed "jobprint" plugins. Choose the appropriate type, such as Tag or Log Sheet.

* Print for Phase \(Disconnect Inspection Reconnect\) - This option controls the sequence to be used in the report, for example you can choose to print a Reconnect phase log sheet.

* Job Tools - Click the Print Button to generate the requested document, or the View\/Edit button to inspect the job details.


### **Search Energy Control Jobs**

An option for Search Jobs will be shown in the Action Menu if the user has edit or view authority for jobs.

* Search Criteria - By default, jobs with a status of Planning or Active will be shown, but you may choose a specific status, or all possible job statuses from the list. Also, you may enter a search term that may occur in the Job Name, Job Description or Workorder fields.


## _**Miscellaneous Functions**_

### **Set User Authorities**

An option for User Authorities will be shown in the Action Menu if the user has edit or view authority for user authorities at the current place

* Select User - Choose the user for Show or Save operations from the list

* Show current authorities - Click the Show button to display the authorities for the selected user

* Authorities - these are the authorities assigned at the current place, click the check box beside the authority description to set or unset the authority. The listed authorities are:


* * Edit User Authorities - set user authorities for this place and all places below it. This is the place admin authority assigned by the system administrator when creating a top level place.

  * View User Authorities - view user authorities, for example for security auditors

  * Add or Edit Places

  * Supervisor of Place - includes the user in the list of supervisors for this place

  * Add or Edit Control Plans

  * View Control Plans

  * Add or Edit Jobs

  * View Jobs

  * Add or Edit Media

  * Browse Media

  * Translate Places

  * Translate Control Plans

  * Translate Media


* Save changes


The Active Authorities for User by Place listing shows the source of all authorities that are active for the selected user at the current place. Authorities are cumulative and apply to the place for which they were assigned, as well as all places under the assigned place. You can navigate to the place where a given authority is assigned by clicking on it in this list.

### **Clipboard Actions**

An option to select the current entity (place, control plan or control point) will be shown in the Action Menu if the user has any edit authority for such entities. Only the most precise entity will be shown, for example, it a current control point is shown, no select option for the control plan or place will be shown.

Selecting the entity will bring up a page showing the available options, possibly including Move\/Copy and Delete.

Selecting Delete will, after confirmation, delete the entity.

Selecting Move\/Copy will copy a reference to the current entity to the clipboard. Once the item is selected to the clipboard, a select action for clipboard item form will be shown where ever such actions might be appropriate. As you navigate the system, the options shown will change as appropriate to the context and your authorities.

Moving an item will change the item's parent. With this, you can move a single control point to a different control plan, move a control plan from one place to another, or move a place (including all of the place's children and associated control plans) to a different parent place.

Copying an item will make a copy of the selected item into the currently active parent. With this, you can make a new copy of a control plan in the same or a different parent place, or make a copy of a control point into the same or a different control plan. Places cannot be copied.

If you have selected a control plan, and navigate to a Job for which you have edit authority, you will be able to add a job step referencing the selected control plan to the job.

