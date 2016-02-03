# docker-gc-whitelist

[![wercker status](https://app.wercker.com/status/7f0335cb65caf7174e744605d960bd54/s/master "wercker status")](https://app.wercker.com/project/bykey/7f0335cb65caf7174e744605d960bd54)

List of docker images we whitelist from the docker-gc script.
Images listed here will stay cached on the machine they're downloaded on for
longer.

See
https://github.com/spotify/docker-gc#excluding-images-from-garbage-collection
for details on the format.

## Contributing

If you have a commonly used image you'd like to see added to the exclude list,
please add it and make a pull request.
