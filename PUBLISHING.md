# How to Publish to a-view.org

Hugo site hosted on Cloudflare Pages. Cloudflare auto-builds on every push to GitHub.

## From a Laptop

1. Edit markdown in `content/post/` using Typora, VS Code, or whatever
2. Working directory is the Dropbox-synced local clone of the repo
3. Open Fork, stage changes, commit, push
4. Cloudflare builds automatically. Done.

## From iPhone — Writing a Real Post

1. Write in 1Writer, saving to Working Copy's repo directory via Files
2. Open Working Copy, commit, push
3. Cloudflare builds automatically. Done.

## From iPhone — Quick Edit

1. Open the GitHub iOS app
2. Edit the file directly (commits straight to remote, no push needed)
3. Cloudflare builds automatically. Done.

## Coming Home from a Trip

If you published from your phone, pull in Fork on the laptop before making new edits.

## Post Structure

Each post is a folder under `content/post/`:

```
content/post/the-ride/
    index.md
    photo.jpg
```

## Things to Remember

- The Dropbox folder IS the local git repo. Yes, this is "wrong." It works for a single user.
- Cloudflare Pages handles Hugo — you never run `hugo` yourself.
- The old Digital Ocean VPS setup is retired. No server to maintain.
- Working Copy shows up in iOS Files app. That's how 1Writer accesses the repo.
