# The `wget` command

`wget` is a Linux command line utility for downloading files from the web. It supports downloading files using HTTP, HTTPS and FTP protocols.


## Syntax

The `wget` syntax requires you to define the downloading options and the URL the to be downloaded file is coming from.
```bash
$ wget [options] [URL]
```


## Example

In this example we will download the Ubuntu 20.04 desktop iso file, which can also be found on https://releases.ubuntu.com/20.04/ . Go over to your terminal or open a new one and type in the below `wget`. This will stat the download. The download may take a few minutes to complete.

```bash
wget https://releases.ubuntu.com/20.04/ubuntu-20.04.3-desktop-amd64.iso
```



## More options

On top of downloading, `wget` provides many more features, such as downloading multiple files, dowloading in the background, limiting download bandwith and resuming stopped downloads. View all `wget` options in its man page.

```bash
man wget
```