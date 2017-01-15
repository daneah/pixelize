# Pixelize

`pixelize` is a tool to make glitch art from source images, based on the work in
[this article](http://theorangeduck.com/page/generating-icons-pixel-sorting) by
[orangeduck](https://github.com/orangeduck).

## Usage

`pixelize` uses [`invoke`](http://www.pyinvoke.org/) for command line argument parsing
and fork-friendliness to extend the tool at your leisure.

```shell
$ invoke pixelize --output-width=2048 --sampling-factor=32 someimage.jpg
```

## Example

In | Out
-- | ---
<img src="in.jpg" width="250" />|<img src="out.jpg" width="250" />
