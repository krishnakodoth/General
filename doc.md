Source tree not starting

For me, the fix was to 

Navigate to C:\Users\UserName\AppData\Local\Atlassian
Under there, you will see SourceTree.exe_Url_RandomGuid
Delete all of those style folders so you are only left with one folder called SourceTree
Start SourceTree, and it will rebuild that settings file.
