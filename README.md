# custom-ui5-controls
Repository showcasing creation and usage of a very simple custom control in ui5.

The [control created](https://github.com/lalugeo/custom-ui5-controls/blob/master/ui/resources/webapp/custom/flightControl.js) is called `mh.custom.Flight`. And using this in ui5 code will give you the hex#9992(&#9992;) unicode character.

[Usage](https://github.com/lalugeo/custom-ui5-controls/blob/886d46ad901f8dd9210071c65768a600200ff079/ui/resources/webapp/index.html#L29)
```javascript
new mh.custom.Flight({
  // custom properties here
})
```

## Run
Please set the npm registry to your local SAP repository (di-local-npm-registry)

```bash
git clone ~
cd custom-ui5-controls/ui
npm install
npm run start #runs the sap app router on default port 5000
#browse to localhost:5000
```
