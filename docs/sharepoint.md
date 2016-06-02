# sharepoint

## References
* https://social.technet.microsoft.com/Forums/sharepoint/en-US/7966c35d-b815-4951-8374-d64840ccf16c/documents-becoming-locked-for-editing-by-self-when-no-other-edits-are-happening?forum=sharepointadminlegacy

##### Documents becoming "locked for editing" by self, when no other edits are happening
* *This is because when a document is opened by a client program, Windows SharePoint Services puts a write lock on the document on the server. The write lock times out after 10 minutes. Users cannot modify the document during the time when the document is locked. To work around this behavior, wait 10 minutes before opening the document again.*
* *I think this KB article can help you: http://support.microsoft.com/kb/899709*
