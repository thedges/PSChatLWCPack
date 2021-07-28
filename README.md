# PSChatLWCPack

THIS SOFTWARE IS COVERED BY [THIS DISCLAIMER](https://raw.githubusercontent.com/thedges/Disclaimer/master/disclaimer.txt).

This is a copy of [Chat-Lightning-Web-Component-Pack](https://github.com/Colatabajonies/Chat-Lightning-Web-Component-Pack) but includes a few enhancments:

__1. lwcchatpackPS Lightning Web Component__

This is a new LWC used in the configuration of the chat bot. In __Setup > Feature Settings > Serivce > Embedded Service > Embedded Service Deployments__, in the section labled "Customize with Lightning Components" enter the value __lwcchatpackPS__ for the "Chat Messages (Text)" entry.

__2. lwcchatpack_recordform Lightning Web Component__

This component has been enhanced to include 2 extra parameters: 
* object label to show as card title
* [SLDS icon name](https://www.lightningdesignsystem.com/icons/) to show in card title
      
Format for chat bot configuration string is: **lwc:recordtile:objectName:recordId:objectFieldCSV:label:iconName__ where
- __objectName__ - the API name of the object
- __recordId__ - the record id to show the fields for
- __objectFieldCSV__ - a CSV list of field API names
- __label__ - the label to show in card title
- __iconName__ - the SLDS icon name
      
__3. lwcchatpack_fileupload Lightning Web Component__ 

this 

