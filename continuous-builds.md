# Continuous builds

I am currently experimenting with a simple continuous build system that:

* Runs a simple test \(max a few minutes\)
* Creates a new Docker image for every commit \(tagged with commit ID and date\)

I can then perform a manual release by running a script that performs a larger set of tests, tags the desired Docker image with a version the user inputs, and then extract out relevant binaries to use with the Github 'Releases' page.

Example: [dxda](https://github.com/geetduggal/notes/tree/0ab8ff3c31fae32a5ef500d572c5f87a63abe943/github.com/dnanexus/dxda/README.md) \(See the Travis YAML file, the Dockerfile, and create\_release.sh script, e.g.\)

