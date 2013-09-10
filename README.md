# Development MacPorts

These is my development repository for my local MacPorts. Feel free to use my local ports, but remember that these are unofficial.


## Documentation

To use my local MacPorts, you will have to set it up as a local portfile repository as follows:

1. Clone the [repository](https://github.com/matysek/macports) - `git clone git@github.com:matysek/macports.git`
2. `cd macports/ports`
3. `(echo "file:/$PWD [nosync]" && cat /opt/local/etc/macports/sources.conf) > sources.conf && sudo mv sources.conf /opt/local/etc/macports/sources.conf`
4. `portindex`

Now you can install new ports or upgrade existing ports from my local MacPorts repository. Remember to rerun `portindex` every time you pull from my repository.

See the official [MacPorts Guide](http://guide.macports.org/) for general instruction about how to setup MacPorts, especially the section about [Local Portfile Repositories](http://guide.macports.org/#development.local-repositories).

