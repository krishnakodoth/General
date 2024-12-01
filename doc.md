## Source tree not starting

* <u>For me, the fix was to </u>

1. Navigate to C:\Users\<UserName>\AppData\Local\Atlassian
2. Under there, you will see SourceTree.exe_Url_<RandomGuid>
3. Delete all of those style folders so you are only left with one folder called SourceTree
4. Start SourceTree, and it will rebuild that settings file.


### List Globally Installed Packages:

To see a list of all globally installed npm packages, run the following command:

```
npm list -g --depth=0
```

This will display a list of all globally installed packages along with their versions.
npm list -g --depth=0

