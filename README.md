# CWL Virtual Training Setup

Replicability and reproducability are key to scientific analysis. To help achieve these aims, workflows provide a way to describe an analysis or tool in a software and operating system agnostic manner.

The common workflow language was created as standard way to describe these workflows, with a particular emphasis to describe workflows suited to data intensive sciences such as Bioinformatics, Medical Imaging, Astronomy, Physics, and Chemistry.  CWL allows workflows to be created that can run on different computational systems.


## Introduction

- aims
- what we won't do
- required prior knowledge
- tools required
- structure and format of course

### [[ Will ]]
This course will provide a brief introduction to the Common Workflow Language (CWL).  You will be shown how to write workflows in CWL and how to execute them. You will be shown the basic and more advanced features of the language such as executing workflows in docker containers.

### [[ Won't ]]
This tutorial will not explain why you should use workflows, or how to use a specific implementation such as Toil or Galaxy. Its focus is on how to use CWL to describe your workflows, and how to use the Common Workflow Language.

### [[ Prior knowledge ]]
No prior knowledge of workflows or CWL is required.  A basic understanding of the linux command line advised.  [[ Are we supporting windows and OSX ]]

### [[ Tools ]]
 - CWL installation (see: ...)
 - Docker installation (see: ...)

[[ If windows, what is our common basis? Git CLI? ]]

 - CLI?
 - Text editor? [[ Are we recommending one? VSCode? ]]


### [[ Structure ]]

This course will be conducted remotely using [[ INSERT DETAILS ]].

## Pre-course setup


Install CWL, the instructions can be found here:

https://github.com/common-workflow-language/cwltool#install

Later parts of the tutorial will require the use of docker. The team that built docker have good instructions to install docker that you can follow here:

https://docs.docker.com/engine/install/ubuntu/

To test docker is installed and setup correctly 

    > docker run hello-world

    docker : Unable to find image 'hello-world:latest' locally
    latest: Pulling from library/hello-world
    1b930d010525: Pull complete
    Digest: sha256:c3b4ada4687bbaa170745b3e4dd8ac3f194ca95b2d0518b417fb47e5879d9b5f
    Status: Downloaded newer image for hello-world:latest

    Hello from Docker!
    This message shows that your installation appears to be working correctly.
    ...

