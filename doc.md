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

### Publishing a Package to npm

To publish a package to npm, you need to first log in to your npm account and then publish the package.

#### Logging in to npm

To log in to your npm account, use the following command:

```
npm login
```

You will be prompted to enter your npm username, password, and email address.

#### Publishing the Package

Once you are logged in, you can publish your package using the following command:

```
npm publish --access public
```

This will publish your package to the npm registry and make it publicly available.

Make sure your `package.json` file is correctly configured before publishing.

### Installing a Specific Package Globally

To install a specific package globally, you can use the `npm install -g` command followed by the package name and version.

For example, to install the latest version of `@krishnakodoth/create-nodejs-app` globally, run the following command:

```
npm install -g @krishnakodoth/create-nodejs-app@latest
```

This will install the package globally on your system, making it available for use in any project.
