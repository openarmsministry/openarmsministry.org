# Open Arms Ministry Landing Page

## How to Develop:
1. clone this repo.
2. create a directory called `themes` in the clone repo's directory.
3. clone [this (modified) `hugo-highlight-theme` theme](https://github.com/openarmsministry/hugo-highlights-theme) into the `themes` directory.
4. go back to the root repo directory, and run `hugo serve -c static` to start a dev server, and actively watches the files changed.

## How to publish:
1. Follow the "How to Develop" steps until the last step.
2. Run `hugo -c static`, and you should see a list of assets generated.
3. git add, commit, and push to github.  The website will automatically publish.