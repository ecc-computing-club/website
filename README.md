# website

Website for the Computing Club at El Camino College. Uses [Hugo](https://gohugo.io) and the [Congo theme](https://github.com/jpanther/congo).

## Usage

Be sure to [install Hugo](https://gohugo.io/installation/) first.

> [!WARNING]
> Your hugo version must be _less than_ v0.146.0. See [this issue](https://github.com/jpanther/congo/issues/1049) for details.

```sh
git clone git@github.com:ecc-computing-club/website
cd website
hugo serve
```

Then, visit `http://localhost:1313/website/` in your browser.

## Deployment

The [github-pages.yaml](https://github.com/ecc-computing-club/website/blob/main/.github/workflows/github-pages.yaml) [GitHub Workflow](https://docs.github.com/en/actions/writing-workflows/about-workflows) is executed whenever commits are pushed to `main`.
