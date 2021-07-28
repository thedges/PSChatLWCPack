# PSChatLWCPack

THIS SOFTWARE IS COVERED BY [THIS DISCLAIMER](https://raw.githubusercontent.com/thedges/Disclaimer/master/disclaimer.txt).

This is a copy of [Chat-Lightning-Web-Component-Pack](https://github.com/Colatabajonies/Chat-Lightning-Web-Component-Pack) but includes a few enhancments:

__1. lwcchatpackPS Lightning Web Component__

This is a new LWC used in the configuration of the chat bot. In __Setup > Feature Settings > Serivce > Embedded Service > Embedded Service Deployments__, in the section labled "Customize with Lightning Components" enter the value __lwcchatpackPS__ for the "Chat Messages (Text)" entry.

__2. lwcchatpack_recordform Lightning Web Component__

This component has been enhanced to include 2 extra parameters: 
* object label to show as card title
* [SLDS icon name](https://www.lightningdesignsystem.com/icons/) to show in card title
      
Format for chat bot configuration string is: __lwc:recordtile:objectName:recordId:objectFieldCSV:title:iconName__ where
- __objectName__ - the API name of the object
- __recordId__ - the record id to show the fields for
- __objectFieldCSV__ - a CSV list of field API names
- __title__ - the label to show in card title
- __iconName__ - the SLDS icon name
      
__3. lwcchatpack_fileupload Lightning Web Component__ 

This component has been enhanced to include 3 extra parameters: 
* a filename to override the uploaded file
* boolean field on parent record to set to true when file is uploaded
* a true/false value to show in community

Format for chat bot configuration string is: __lwc:fileupload:recordId:fileName:bField:commAccess__ where
- __recordId__ - the record id to attach the uploaded file to
- __fileName__ - the name of the file to set after it is uploaded (overrides name of file from source OS)
- __bField__ - the boolean field API name on the record to set to true once the file is uploaded
- __commAccess__ - make the file accessible from community/experience site
