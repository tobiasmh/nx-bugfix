Bugfix example.

Bug encountered:
```aidl
bash-5.0$ npx nx g @nrwl/react-native:app mobileapp --verbose
Cannot read property '1' of undefined
TypeError: Cannot read property '1' of undefined
    at /home/developer/IdeaProjects/bugfix-example/example/node_modules/@nrwl/jest/node_modules/@nrwl/devkit/src/utils/invoke-nx-generator.js:46:55
    at Generator.next (<anonymous>)
    at /home/developer/IdeaProjects/bugfix-example/example/node_modules/@nrwl/jest/node_modules/tslib/tslib.js:117:75
    at new Promise (<anonymous>)
    at Object.__awaiter (/home/developer/IdeaProjects/bugfix-example/example/node_modules/@nrwl/jest/node_modules/tslib/tslib.js:113:16)
    at /home/developer/IdeaProjects/bugfix-example/example/node_modules/@nrwl/jest/node_modules/@nrwl/devkit/src/utils/invoke-nx-generator.js:40:39
    at MergeMapSubscriber.project (/home/developer/IdeaProjects/bugfix-example/example/node_modules/@angular-devkit/schematics/src/rules/call.js:75:24)
    at MergeMapSubscriber._tryNext (/home/developer/IdeaProjects/bugfix-example/example/node_modules/rxjs/internal/operators/mergeMap.js:69:27)
    at MergeMapSubscriber._next (/home/developer/IdeaProjects/bugfix-example/example/node_modules/rxjs/internal/operators/mergeMap.js:59:18)
    at MergeMapSubscriber.Subscriber.next (/home/developer/IdeaProjects/bugfix-example/example/node_modules/rxjs/internal/Subscriber.js:66:18)

```


Steps to reproduce
1. Clone this repo
2. npm install
3. npx nx g @nrwl/react-native:app mobileapp --verbose

