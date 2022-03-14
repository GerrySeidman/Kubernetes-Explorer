# Kubernetes-Explorer

## Kubernetes API Object Explorer

There are over 70 Kubernetes HTML objects, each of which have a deep tree of fields.

The typical way to access descriptions and documentation for these are:

 - The ```kubectl explain``` CLI Command
 - Referring to the Official [API OVERVIEW](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.23/) 

While these are great, they are not the ideal format to either quickly find things or to explore the Kubernetes API objects

These HTML pages contain all the information that could be obtained using ```kubectl explain``` command, but  in as interactively expandable trees.

- [Full Kubernetes API Explorer](kubernetesExplorer.html)
- [Abridged Kuberenetes API Explorer](http://) (less important/deprecated objects and fields are omitted)
 

## ```kubectl``` Command Explorer

There are over 90 ```kubectl``` commands and subcommands

The typical way to access get the documentation for these commands is:

- ```kubectl``` \<comand> [\<sub-command>] --help

An HTML Explorable version will be posted 'soon', but in the mean time, the 'help' for all kubectl commands and sub-commands can be found here:

- [kubectl Commands](kubectlCommands)

    