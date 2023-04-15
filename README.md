# HUGO.386
HUGO.386 is a port of the [BOOTSTRA.386](//github.com/kristopolous/BOOTSTRA.386) theme. It has a cool MS-DOS feeling and is ready to be used for blogs. Despite its antique look, the theme is responsive and can be viewed on mobile devices.

## [Test it on live here! (v1)](//hugo386.netlify.app/)

**Note:** A new version based on Bootstrap 4 is in the making with a slightly different design. It's still in beta but you can test it by fetching [the v3 branch](https://gitlab.com/jmfergeau/hugo.386/-/tree/v3) instead of the master. Don't use it in production yet, though. [You can test it here!](//hugo386v3.netlify.app/)

![Example of Hugo blog with the theme](images/screenshot.png)

## Installation

### As a Hugo module
Remove your previously used theme variable from your site config and remove the themes directory, or move it out of your Hugo site repo.

In your siteconfig add the following:

```
[module]
  [[module.imports]]
    path = "gitlab.com/jmfergeau/hugo.386"

```

Inside the folder of your Hugo site run:

    $ hugo mod init hugo386

Finally to clean up the go.mod and update/generate the go.sum file which track the module dependencies for your site, run: 

    $ hugo mod tidy

### With git submodules

Inside the folder of your Hugo site run:

    $ git submodule add https://gitlab.com/jmfergeau/hugo.386 themes/hugo.386

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Getting started

After installing the theme successfully it requires a just a few more steps to get your site running.


### The config file

Take a look inside the [`exampleSite`](//gitlab.com/jmfergeau/hugo.386/tree/master/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//gitlab.com/jmfergeau/hugo.386/blob/master/exampleSite/config.toml).
It contains detailed information about the customization of all strings in this theme. 

To use it, copy the [`config.toml`](//gitlab.com/jmfergeau/hugo.386/blob/master/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change strings as you like.


### Nearly finished

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//gitlab.com/jmfergeau/hugo.386/issues) to let me know. Or make directly a [merge request](//gitlab.com/jmfergeau/hugo.386/pulls).


## License

This theme is released under the Apache License 2.0 For more information read the [License](//github.com/digitalcraftsman/hugo-freelancer-theme/blob/master/LICENSE).


## Annotations

Thanks to [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project. Many thanks to [Kristopolous](//github.com/kristopolous) as well for the BOOTSRTA.386 theme. And finally huge thanks for all the contributors for helping this theme to stay updated and glitch-free!
