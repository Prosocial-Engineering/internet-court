# Anatomy of an Internet Argument

This is the project home for the "Anatomy of an Internet Argument" project, a game you play on the internet to find & propagate truth while improving social norms.

Read it here: https://prosocialengineering.org/internet-court/

### Contributing

Anyone with a GitHub account can edit this book! Just click the pencil icon in the top right of any page, and it will take you to GitHub where you can propose a change and open a pull request.

### Running locally

See mdBook docs: https://rust-lang.github.io/mdBook/

To run locally, install `mdBook` (v0.5.x, same as CI), then:

```
mdbook serve --open
```

### Deployment

Every push to `main` builds the book and deploys it to GitHub Pages ([.github/workflows/ci.yaml](.github/workflows/ci.yaml)). The repo must be named `internet-court` under the `Prosocial-Engineering` org, with Pages set to deploy from "GitHub Actions" (Settings → Pages → Source).
