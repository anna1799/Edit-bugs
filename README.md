# Edit-bugs

I've tested an app to convert and optimize pictures and was responsible for an "Edit" module. This module has 7 functions: delete, rotate left, rotate right, flip horizontal, optimize, select as cover, order by random.

Here are bugs reported by me that are related to the "Edit" module. I've attached screenshots from Jira because I was given access to Jira only for the duration of the training and the project and I am not able to give a link to Jira.

## Here is a list of defects sorted by priority:

   1. Critical bugs:
   
![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/critical.jpg)

   2. Major bugs:
   
![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/major.jpg)

   3. Minor bugs:
   
![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/minor.jpg)

   4 Trivial bugs:
   
![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/trivial.jpg)

## Critical bugs description

  ### 1. Edit: Delete: the picture is also deleted on the device after deletion confirmation
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/jira_deletion_on_the_device.jpg)
  
  Attachment:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/deletion_on_the_device.gif)
  
  ### 2. Optimize: Auto-optimize: button is disabled
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/auto-optimize_disabled.jpg)
  
  Attachments:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/1502.png)
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/1502(1).png)

## Major bugs description

  ### 1. Optimize: app error when decreasing window size to the minimum
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/error_screen_size.jpg)
  
  Attachment:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/1508.gif)
  
  ### 2. The Toolbar is missing
  
   ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/toolbar.jpg)
  
  Attachments:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-04-17-46-16-056.png)
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-04-17-48-41-393.png)
  
  ### 3. Optimize: all sliders are disabled
  
   ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/sliders.jpg)
   
  ### 4. Optimize: Apply: changes are saved only for the first picture if many pictures are selected at once
  
   ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/apply_many_pictures.jpg)
  
  ### 5. Optimize: Rotate Left, Rotate Right and Flip Horizontal: buttons work 2 times when doubleclicking
  
   ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/optimize_doubleclicking.jpg)
  
  ### 6. Edit: pictures aren't reordered randomly after clicking "Order by random"
  
   ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/order.jpg)
  
   Attachment:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/order_by.gif)
  
  ### 7. Edit: app error when deleting 2 pictures in the row
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/2_pictures.jpg)
  
   Attachment:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/deletion_2_times.gif)
  
  ### 8. Optimize: absolutely all changes are canceled, not just the last changes, when clicking "Cancel"
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/cancel.jpg)
  
   Attachment:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/79tsXgqKtK.gif)
 
  ### 9. Optimize: changes aren't displayed in the Main menu after clicking "Apply"	

  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/main_menu.jpg)
  
   Attachment:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/mainmenu.gif)
 
  ### 10. Edit: Delete: Deletion confirmation: the window closing button is disabled
 
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/confirmation.jpg)
  
   Attachment:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/screenshot-1.png)

 ### 11. Optimize: Red-Eye-Reduction: button is disabled

  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/red.jpg)
  
   Attachment:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/red.png)

## Minor bugs description

  ### 1. Edit: "Order by random" is active until a folder is selected
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/act.jpg)
 
  ### 2. Edit: double-click works like clicking 2 times in a row if the dropdown menu is open
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/double.jpg)
  
   Attachment:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/PCjYCqL2ER.gif)
  
  ### 3. Edit: option names are not displayed in the order described in the specification
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/names.jpg)
  
  Attachments:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-05-15-52-20-655.png)
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-05-15-56-38-288.png)
  
  ### 4. Edit: "Select as cover" isn't disabled when several pictures are selected
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/select.jpg)
  
  ### 5. Edit and Optimize: function "Filp Vertical" is displayed that is not in the specification
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/flip.jpg)
  
  Attachments:
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-05-15-29-22-810.png)
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-05-15-31-55-888.png)
  
  ### 6. Optimize: "Tab" and arrow keys navigation functions incorrectly
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/tab.jpg)
  
   Attachment:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/tab.gif)
  
  ### 7. Edit: Delete: Deletion confirmation: the names of the "Да" and "Нет" buttons are not translated
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/yes.jpg)
  
   Attachment:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-04-17-06-52-014.png)
  
  ### 8. Edit: Select as cover: picture isn't marked with a border if it is selected as a cover
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/border.jpg)
  
  ### 9. Optimize: window closing button is displayed without "x" icon
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/x.jpg)
  
   Attachments:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/1.png)
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/2.png)
  
  ### 10. Optimize: filename isn't displayed
  
   ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/filename.jpg)
  
## Trivial bugs description

  ### 1. Enhancement: add "Undo" and "Redo" buttons
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/undo.jpg)
  
  ### 2. Enhancement: Otimize and Options: unify the window names
  
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/unify.jpg)
  
  Attachment:
   
  ![Image alt](https://github.com/anna1799/Edit-screenshots/raw/master/image-2020-08-04-22-23-30-940.png)
  
  
