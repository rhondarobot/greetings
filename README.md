### Playing around with the following features:

- `git rerere` - good to use when a branch has a long life and is branched off again and keeps getting the same merge conflicts. It helps the user reduce the amount of merge conflicts

- `git bisect` - helps you track which version broke a previous feature. You'd want to start by saying `git bisect start` and then naming the current version `git bisect bad`. Go through your version history `git log --oneline` to choose the last version you remember the feature working. When you find it, type `git bisect good` (plus the version number) and then you can start weeding through the versions and testing where exactly the feature broke

- `git tag -a [name]` to add a tag for the version to help communicate with your team

- `git bad` to see different versions

- `git log --oneline` - see your logs on oneline

- `git revert HEAD` - take back the last action you submitted to git

 
