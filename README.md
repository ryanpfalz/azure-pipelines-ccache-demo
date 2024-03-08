# azure-pipelines-ccache-demo

This is a simple example of how to use [Ccache](https://ccache.dev/) within Azure Pipelines.

Files:

- `.azure-pipelines/ccache-pipeline.yml`: Azure Pipelines configuration file which installs and configures Ccache for caching compilation, and compiles the code using a Makefile.
- `cppsrc/main.cpp`: A simple C++ program.
- `Makefile`: A simple Makefile to build the C++ program.

To use, [create a Pipeline](https://learn.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline?view=azure-devops&tabs=java%2Ctfs-2018-2%2Cbrowser) in Azure DevOps and point it to the `ccache-pipeline.yml` file.
