## Node Soap (forked from https://github.com/vpulim/node-soap)

## Release process
1. `git checkout master`
1. `yarn build`
1. `git commit -m "chore: build"`
1. `yarn version --[major|minor|tag]` <- upgrades version in package.json, commits, creates tag
1. `git push origin master --follow-tags`
