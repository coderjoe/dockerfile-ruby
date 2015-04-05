# A ruby-install image for Docker

Source for [coderjoe/ruby](https://registry.hub.docker.com/u/coderjoe/ruby),
a Docker image intended to be used as the base for images which need to install
a particular runtime ruby version.

## Pulling from Docker Hub

```
docker pull coderjoe/ruby
```

## Using in your Dockerfile

```
# latest version
FROM coderjoe/ruby

# specific version
FROM coderjoe/ruby:ruby-2.2.1
```

## Latest stable versions

* ruby-2.2.1

## Contributing

Suggestes, contributions, and bugs are welcome.
Please create a GitHub Issue.
