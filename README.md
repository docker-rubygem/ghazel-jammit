[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/ghazel-jammit.svg)](https://hub.docker.com/r/rubygem/ghazel-jammit/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/ghazel-jammit.svg)](https://hub.docker.com/r/rubygem/ghazel-jammit/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/ghazel-jammit.svg)](https://hub.docker.com/r/rubygem/ghazel-jammit/)
[![Gem Downloads](https://img.shields.io/gem/dt/ghazel-jammit.svg)](https://rubygems.org/gems/ghazel-jammit/)
# ghazel-jammit

Auto-Generated Docker image for ghazel-jammit to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/ghazel-jammit`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/ghazel-jammit`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/ghazel-jammit`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/ghazel-jammit/)
