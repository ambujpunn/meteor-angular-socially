# meteor-angular-socially - [Tutorial's site](http://angularjs.meteor.com/tutorial)
angular-meteor example and tutorial app

The tutorial starts at branch 'step_00' till the last step.

The master branch is always equal to the last step.

Here is the deployed final version - http://socially-step17.meteor.com/

Please contribute to the tutorial.
Pull request the master branch to add new features or pull request specific step to improve that step.

Our goal in this tutorial is to add more steps as we go along, to cover as many use cases as possible.

#FAQs
1. ERROR whitelist rejection while running on ios
   * Create ```mobile-config.js``` and add ```App.accessRule('*');```
   * Re-run meteor and it should work
   * Take a look at this for extra help: https://github.com/Urigo/meteor-angular-socially/issues/34#issuecomment-143902353
