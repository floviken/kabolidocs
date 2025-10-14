# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


This is your documentation home page.

## Quick Start

Get started with our [Getting Started Guide](getting-started.md).
```

### Step 3: Fix DNS (Do This First!)

1. Go to your domain registrar/DNS provider
2. Add the CNAME record as shown above
3. Wait 5-30 minutes for DNS propagation
4. Click "Check again" in GitHub Pages settings

### Step 4: Create CNAME File

After DNS is working, create a file named `CNAME` in your `docs/` folder:
```
doc.kaboli.xyz