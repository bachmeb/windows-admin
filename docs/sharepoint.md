# sharepoint

## References
* 

##### Documents becoming "locked for editing" by self, when no other edits are happening
* *This is because when a document is opened by a client program, Windows SharePoint Services puts a write lock on the document on the server. The write lock times out after 10 minutes. Users cannot modify the document during the time when the document is locked. To work around this behavior, wait 10 minutes before opening the document again.* (https://social.technet.microsoft.com/Forums/sharepoint/en-US/7966c35d-b815-4951-8374-d64840ccf16c/documents-becoming-locked-for-editing-by-self-when-no-other-edits-are-happening?forum=sharepointadminlegacy)
* *I think this KB article can help you: http://support.microsoft.com/kb/899709*
* *The fastest way to unlock is delete the file, but before that you need to copy the file to your PC or Desktop first. After you delete the file then you upload as new file with same name. Now the file should be ok.* (https://community.office365.com/en-us/f/154/t/170220)

##### I have a group call Excel Services Viewers. Can it be deleted?
* *Excel Services Viewers is the default OOB group. If you/organization is using the Excel Services in your site then this group is helpful. Otherwise it is just like the site visitors group.* (https://social.technet.microsoft.com/Forums/en-US/3d94dbef-fd15-4e9c-a7ff-ca1128ef01fa/i-have-a-group-call-excel-services-viewers-can-it-be-deleted?forum=sharepointgeneral)
