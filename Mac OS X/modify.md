# Modify Mac OS


## disable dashboard

Everytime I accidently hit cmd + left the dashboard appeared, prevent it with the following:

`defaults write com.apple.dashboard mcx-disabled -boolean true`

## add spaces to dock

![docks + spaces](https://raw.githubusercontent.com/keeev/recipes/master/assets_readme/dock.png)

`defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'`
`killall Finder`

## show all files in finder
`defaults write com.apple.finder AppleShowAllFiles TRUE`
`killall Finder`
