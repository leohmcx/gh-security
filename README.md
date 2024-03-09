# gh-security


![](readme-images/security-permissions.png?raw=true)

![](readme-images/security-concerns.png?raw=true)

- Injection ocurred when the issue was opened, the a" finished the command and injected all the thinks after ; that is present in the issue title.

![](readme-images/injection.png?raw=true)

- if you are using user generate values like the title of issue, it's strongly recomended that you first stored them in an envinronment variable before you using them anywhere in the command.

- This is after apply the suggestion above:

![](readme-images/injection-not-efective.png?raw=true)