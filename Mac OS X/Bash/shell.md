# Useful shell scripts


### Quick jump to localhost

Using "lh" (localhost) to jump to htdocs folder, accpets 3 more commands

`
lh () {
        cd /Applications/MAMP/htdocs $1 $2 $3
}`

### Show all branches except remotes 

`
gitm() {
        git log --branches --not --remotes
}`


### Delete Spotify's Cache to save some space

type "open ." to open this folder in your finder, Spotify's Cache takes up to a few GBs after a few months of using it.

`
spotifycache() {
 cd /Users/[USER]/Library/Caches/com.spotify.client/Storage/
}`

 

### Show/Hide hidden files in Mac OS X (Finder)

this accepts the following values (YES or NO). 

`
files () {
 defaults write com.apple.finder AppleShowAllFiles $1
}`

