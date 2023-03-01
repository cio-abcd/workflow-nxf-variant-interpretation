
## Introduction

TO-DO: Add a short description of the pipeline, its intended use and give short overview of the project.

The pipeline is built using [Nextflow](https://www.nextflow.io), a workflow tool to run tasks across multiple compute infrastructures in a very portable manner. It uses Docker/Singularity containers making installation trivial and results highly reproducible. The [Nextflow DSL2](https://www.nextflow.io/docs/latest/dsl2.html) implementation of this pipeline uses one container per process which makes it much easier to maintain and update software dependencies. Where possible, these processes have been submitted to and installed from [nf-core/modules](https://github.com/nf-core/modules) in order to make them available to all nf-core pipelines, and to everyone within the Nextflow community!


## Pipeline summary

TO-DO: Add a flowchart and an overview on the required input and expected output data.

## Quick Start

1. Install [`Nextflow`](https://www.nextflow.io/docs/latest/getstarted.html#installation) (`>=22.10.1`)

2. Install any of [`Docker`](https://docs.docker.com/engine/installation/), [`Singularity`](https://www.sylabs.io/guides/3.0/user-guide/) (you can follow [this tutorial](https://singularity-tutorial.github.io/01-installation/)), [`Podman`](https://podman.io/), [`Shifter`](https://nersc.gitlab.io/development/shifter/how-to-use/) or [`Charliecloud`](https://hpc.github.io/charliecloud/) for full pipeline reproducibility _(you can use [`Conda`](https://conda.io/miniconda.html) both to install Nextflow itself and also to manage software within pipelines. Please only use it within pipelines as a last resort; see [docs](https://nf-co.re/usage/configuration#basic-configuration-profiles))_.

3. Continue describing the use of the pipeline for a default use case


## Documentation

TO-DO: Add extensive and detailed documentation of the pipeline here.

## Contributions and Support

This Pipeline development repository is a collaborative effort of the Center for Integrated Oncology of the Universities of Aachen, Bonn, Cologne and Düsseldorf to standardize and optimize data analysis in a clinical context.

TO-DO: Add information on CIO

**Contributing authors**:

- RWTH University Hospital (UKA): Lancelot Seillier
- University Hospital Bonn (UKB): Patrick Basitta, Florian Hölscher
- University Hospital Cologne (UKK): --
- Heinrich-Heine University Hospital Düsseldorf (UKD): Kai Horny

**Further Contributions**:

- TO-DO: Add further contributors 


## Citations

...
