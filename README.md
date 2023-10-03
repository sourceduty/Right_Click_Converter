## Right-Click_Converter

🖱️ Add right-click menu file converter option for Windows 10/11.

## Step 1: 
Open “Run” and type “regedit” in the search box.

## Step 2: 
Navigate to the “ContextMenuHandlers” folder and then to HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers\.

## Step 3: 
Add a key to the ContextMenuHandlers folder. Right-click on the ContextMenuHandlers folder, move the cursor over to “New,” and click on “Key.” A sub-key will be created under the default name of “New Key #1.” Rename the new key to the name of the application or pathway you wish to add to the right-click context menu.

## Step 4: 
Change the default value of the sub-key by double-clicking on the “Default” value inside the sub-key that you have created. In order for the computer to recognize the application, you must add the path to the executable (.exe) file of the application to the Default value. To find the path of a file or folder, right-click on the address bar of the window in which the file or folder is located. Left-click on “Copy address” and paste it as the Default Value of the key.

## Step 5: 
Go to any file and right-click to view and confirm that the new right click menu option has been added.

# Converter: 
https://file-converter.org/

#
This customization to Windows 10/11 right-click context menu is an example to indicate file conversion should be included as a default right-click context menu option in future versions of Microsoft Windows.
#
