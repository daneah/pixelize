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

See all options with `invoke --help pixelize`

## Examples

Parameters | In | Out
---------- | -- | ---
`sampling_factor`: 16 | <img src="examples/one.in.jpg" width="250" /> | <img src="examples/one.out.jpg" width="250" />
`sampling_factor`: 1 | <img src="examples/two.in.jpg" width="250" /> | <img src="examples/two.out.jpg" width="250" />
`sampling_factor`: 1 | <img src="examples/three.in.jpg" width="250" /> | <img src="examples/three.out.jpg" width="250" />
