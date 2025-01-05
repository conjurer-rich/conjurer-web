# conjurersolutions.co.uk

---

The website for Conjurer Solutions Ltd

## Development

---

### Setup environment

Install Docker Desktop on Windows:

```pwsh
\$ winget install -e --id Docker.DockerDesktop
```

Install Docker Desktop on MacOS:

```fish
\$ brew install --cask docker
```

### Day-to-day Development

To run a server locally:

```fish
\$ docker compose up
```

Or open the project as a dev container and directly start the server:

```fish
\$ bundle exec jekyll serve
```

Configuration
The Minimal Mistakes skin was customized by copying the original main.scss file to assets\css. Any changes to the theme's Sass variables must be made before the any @importlines.
