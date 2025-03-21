# cdn-template

A template repo to create personal cdn.

## Usage

### Part 1: Clone & Permissions

Do this completely on github.

1. Clone the repo.
2. Allow github actions write access:
   - Settings > Actions > General > Workflow permissions > Read and write permissions

### Part 2: Deployment

#### Via Pages (recommended)

Settings > Pages > Deploy from a branch (using actions) > Branch: `main`

#### Via 3rd party pages

E.g. [Vercel](https://vercel.com/) or [Cloudflare Pages](https://pages.cloudflare.com/).

1. Delete the `./github/workflows/static.yml` file.
2. Follow instructions on your pages provider.

Under [its-ours](https://its-ours.org/) license.
