# gh-security

Links:
- https://github.com/marketplace?type=actions
- https://docs.github.com/en/actions/using-jobs/assigning-permissions-to-jobs

---

- Introduction:

![](readme-images/security-permissions.png?raw=true)

- Concerns:

![](readme-images/security-concerns.png?raw=true)

- Injection ocurred when the issue was opened, the a" finished the command and injected all the thinks after ; that is present in the issue title.

![](readme-images/injection.png?raw=true)

- if you are using user generate values like the title of issue, it's strongly recomended that you first stored them in an envinronment variable before you using them anywhere in the command.

- This is after apply the suggestion above:

![](readme-images/injection-not-efective.png?raw=true)

- Verified creators of actions, when you see it means that github has approved this action and gave that badge to creator.

![](readme-images/verified-creators-actions.png?raw=true)

![](readme-images/verified-creators-actions.png?raw=true)

![](readme-images/using-actions-securely.png?raw=true)