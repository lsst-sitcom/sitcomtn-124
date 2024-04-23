[![Website](https://img.shields.io/badge/sitcomtn--124-lsst.io-brightgreen.svg)](https://sitcomtn-124.lsst.io)
[![CI](https://github.com/lsst-sitcom/sitcomtn-124/actions/workflows/ci.yaml/badge.svg)](https://github.com/lsst-sitcom/sitcomtn-124/actions/workflows/ci.yaml)

# Metrics and Plots Available in Operations Rehearsal 3

## SITCOMTN-124

This technote is supposed to act as a jumping of point as an inventory of plots and metrics in analysis tools. 
If something you care about that exists is missing (or described poorly) feel free to add to this technote. 
If something you care about does not exist please add to analysis tools and then this technote. 

**Links:**

- Publication URL: https://sitcomtn-124.lsst.io
- Alternative editions: https://sitcomtn-124.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-124
- Build system: https://github.com/lsst-sitcom/sitcomtn-124/actions/


## Build this technical note

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

```sh
git clone https://github.com/lsst-sitcom/sitcomtn-124
cd sitcomtn-124
make init
make html
```

Repeat the `make html` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run `make clean`.

The built technote is located at `_build/html/index.html`.

## Publishing changes to the web

This technote is published to https://sitcomtn-124.lsst.io whenever you push changes to the `main` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-124.lsst.io/v.

## Editing this technical note

The main content of this technote is in `index.md` (a Markdown file parsed as [CommonMark/MyST](https://myst-parser.readthedocs.io/en/latest/index.html)).
Metadata and configuration is in the `technote.toml` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
