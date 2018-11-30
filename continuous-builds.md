# Continuous builds

I am currently experimenting with a simple continuous build system that:

* Runs a simple test (max a few minutes)
* Creates a new Docker image for every commit (tagged with commit ID and date)

I can then perform a manual release by running a script that performs a larger set of tests, tags the desired Docker image with a version the user inputs, and then extract out relevant binaries to use with the Github 'Releases' page.

Example: [dxda](github.com/dnanexus/dxda) (See the Travis YAML file, the Dockerfile, and create_release.sh script, e.g.)