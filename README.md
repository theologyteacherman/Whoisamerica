# Who Is America

Static site. No build step, no dependencies. Upload as-is.

## Structure

```
index.html                     the hub landing page
games/glue-game/index.html     Who Is the Nation? (single self-contained file)
```

## Publishing to GitHub Pages

1. Push both files to your repo, keeping the folder structure above.
2. Repo **Settings → Pages → Source: Deploy from a branch → main → / (root)**.
3. The site appears at `https://<username>.github.io/<repo>/`
   and the game at `.../<repo>/games/glue-game/index.html`.

Give it two or three minutes on the first publish.

## Adding the next game

In `index.html`, copy the `<div class="pending">` block and replace it with a
copy of the `<a class="folder">` block above it. Change the href, the case
number, the title, and the blurb. Nothing else needs to change.

To keep a game unfinished but visible, leave it as a `pending` block.

## Editing the copy

Everything on the hub is plain text in `index.html`. No names appear anywhere
on the site.
