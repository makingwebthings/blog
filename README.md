# chris.nunciato.org

## Some Useful Instructions

### Upgrading Ghost Locally

This picks up the most recent app and Casper theme, which gets renamed to `chrisper-$VERSION` to faciliate customization. 

    bin/bump $VERSION # e.g., "bin/bump 0.6.2"

Run locally, then when everything looks good, push to Github:

    git add --all
    git commit -m "Bump Ghost to $VERSION"
    git push origin master

Now, you can bump the version of Ghost in your Chef repo, CCR and have a beer.
