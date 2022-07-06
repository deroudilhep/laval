# laval

*laval* is a shell script that uses *R* and *youtube-dl* to give you one or several youtube channels' total video duration. Use it in your terminal like so :

```bash
laval [URL] ([URL] ...)
```

*laval* can take as many youtube channels' url as you want, the result given is the total video duration of specified channels altogether. 

## Installation

### Requirements

First, *laval* needs *R* installed on your computer as well as *R* packages *tidyverse*, *lubridate* and *readr*. See the [CRAN website](https://cran.r-project.org/) to know how.

Second, *laval* needs *youtube-dl*. You can find it [here](https://github.com/ytdl-org/youtube-dl/)

### Installing *laval*

Download `laval` file, put it somewhere your `$PATH` is looking for (for Ubuntu, there must be a `~/.local/bin` or something like that), then open your terminal and there you go! 

## Support

For support or questions, email pierre.deroudilhe@pm.me.

## Authors

[@deroudilhep](https://www.github.com/deroudilhep)

## License

[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
