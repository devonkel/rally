# rally

##Rally Node Example Application

This application will utilize the Rally API with Node.JS to generate Rally dashboards.

+ Node.Js
+ Express
+ MongoDB
+ Rally - Rally/Node https://github.com/RallyTools/rally-node

##Installation:

``` npm i ```

##Run Application:

``` npm start ```

This will install all of the node dependencies included in the `./package.json` file.  All of the dependent files will be loaded under `./node_modules` directory.  Make sure you include an entry in the `./.gitignore` file for any files/folders you do not want saved in the repository.

##Build Application:

```npm build```

##Test Application:

```npm test```

##Outstanding Items:
- [X] Install Rally Dev Generator
- [ ] Configure with AA Rally OAuth
- [ ] Implement Schema / Connect classes
