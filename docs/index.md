# taco-simple

This repository implements a read filtering workflow for
[dahak-taco](https://github.com/dahak-metagenomics/dahak-taco).

In this documentation we will cover:

* Download raw sequence data from OSF data store (wget).

* Assess the quality of the pre-filtered reads (fastqc)

* Trim and filter the reads based on a quality threshold (trimmomatic)

* Assess the quality of the post-filtered reads (fastqc)

* Interleave post-filtered reads (khmer) 

We will not cover:

* How to install `taco`

* The basics of `taco` 

For those, see the [dahak-taco documentation](https://dahak-metagenomics.github.io/dahak-taco).


## Setting Up Taco

Before you can run any of these workflows, you must first 
install `taco`. See [dahak-taco documentation](https://dahak-metagenomics.github.io/dahak-taco)
for installation instructions.

Once `taco` is installed, it will be available on the 
command line. The `taco` commands covered in this document
should be run from the main workflow repository directory. 


## What's In This Repository

Required directories:

* `rules/` - contains rule and workflow definitions (REQUIRED)

Workflow files:

* `workflow-config/` - contains workflow configuration files
* `workflow-params/` - contains workflow parameter files
* `docker/` - contains custom Docker images for use in taco workflows
* `my-workflow-files/` - directory containing config/param/docker files 
    that should be kept together

Documentation files:

* `docs/` - contains the documentation files (i.e., the document you're reading now)
* `mkdocs.yml` - configuration file for mkdocs, the documentation generator used by this repo
* `mkdocs-material-dib/` - git submodule containing mkdocs theme

Optionally, you can also create a directory to contain 
all of the files for your particular workflow.


## Workflows

There's nothing here yet.

