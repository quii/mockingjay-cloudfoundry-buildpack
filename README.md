# Mockingjay Cloud Foundry Buildpack

This buildpack will let you take a mockingjay config and monkey config and have a mockingjay web server run in your Cloud Foundry environment. 

See https://github.com/quii/mockingjay-server

## Goal

Eventually have it so you can have two files; server.yaml & monkey.yaml in a directory and then be able to ````cf push my-fake-server -b https://github.com/quii/mockingjay-cloudfoundry-buildpack```` and that's it! 

## To try it out

- Create a directory and copy the yaml file from the examples directory
- ````cf push test-name -b https://github.com/quii/mockingjay-cloudfoundry-buildpack````

## TODO

Actually make it work, trying to follow http://docs.cloudfoundry.org/buildpacks/custom.html