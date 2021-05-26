## About

-----

`imagemagick-screenshot` is a script to give style to a screenshot picture with imagemagick and flameshot as screenshot tool.

Originally i found from [@bandithijo blog](https://bandithijo.github.io/blog/memodifikasi-screenshot-dari-flameshot-dengan-imagemagick)



### Requirements

-----

1. [Imagemagick](https://www.imagemagick.org/)
2. [Flameshot](https://github.com/flameshot-org/flameshot)



### Screenshots

-----

![Screenshot](https://github.com/Iyankdesu/imagemagick-screenshot/blob/master/image.png)



### Installation

-----

1. Clone this repository :

   ```
   git clone https://github.com/Iyankdesu/imagemagick-screenshot.git
   ```

2. Copy `imagemagick-screenshot` file to your screenshot directory, in this case `~/Pictures/Screenshots` :

   ```
   cp imagemagick-screenshot ~/Pictures/Screenshots
   ```

3. Edit the `imagemagick-screenshot` file and change `screenshot_dir = "/path/to/screenshot/directory"`, to your full path screenshot directory, example `screenshot_dir = "/home/user/Pictures/Screenshots"`.

4. Create a shortcut to launch the `imagemagick-screenshot`, you can also just use `alias` instead.



### Usage

-----

1. Take screenshot with flameshot (with shortcut or alias).
2. Press `Return` and it'll automatically save the picture to your screenshot directory.

In some cases can't save the picture by pressing `Return` key, you can edit the flameshot configuration file in `~/.config/flameshot/flameshot.ini` and change the shortcut `TYPE_COPY` from `Ctrl+C` to `Return`

```
[shortcuts]
....
....
TYPE_COPY=Return
....
....
....
```
