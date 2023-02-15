# fract-ol
![JSr07885](https://user-images.githubusercontent.com/111196709/218948128-d71cb8e5-3bf9-4046-be96-808fe6ce0f96.gif)

One of the first graphical projects at 42 school, fract-ol generates beautiful fractals from the complex numbers of an iterative mathematical construct. A fractal is a fragmented geometrical figure that infinitely repeats itself at smaller scales. This project uses the school's graphical library, MiniLibX.



# Status

Finished: 22/04/2022.

Grade: 125%.

# Usage


## Installing and Compiling Fract-ol

Clone the repository, including the embedded MiniLibX repository:
```shell
git clone https://github.com/mcombeau/fract-ol.git && cd fract-ol && git submodule init && git submodule update
```

You will now be in the correct directory for compilation. Compile with ```make```. Fract-ol should now be ready!

## Executing Fract-ol

At execution time, you must specify a fractal to display. You may also provide other optional parameters:

```shell
./fractol <type>
```

Types are :
*  Mandelbrot fractal => 1
*  Julia fractal => 2
*  Tricorn fractal => -0.8 0.156

## Fract-ol Controls

While Fractol is running, the following set of controls are available:

<table>
  <tr><td><strong>Controls</strong></td><td><strong>Action</strong></td></tr>
  <tr><td><kbd>&nbsp;W&nbsp;</kbd><kbd>&nbsp;A&nbsp;</kbd><kbd>&nbsp;S&nbsp;</kbd><kbd>&nbsp;D&nbsp;</kbd> or <kbd>&nbsp;▲&nbsp;</kbd><kbd>&nbsp;◄&nbsp;</kbd><kbd>&nbsp;▼&nbsp;</kbd><kbd>&nbsp;►&nbsp;</kbd></td><td>Move</td></tr>
  <tr><td><kbd>&nbsp;-&nbsp;</kbd>, <kbd>&nbsp;+&nbsp;</kbd> or <kbd>&nbsp;scroll wheel&nbsp;</kbd></td><td>Zoom in and out</td></tr>
  <tr><td><kbd>&nbsp;space&nbsp;</kbd></td><td>Stop Mouse Movement</td></tr>
  <tr><td><kbd>&nbsp;Enter&nbsp;</kbd></td><td>Continue Mouse Movement</td></tr>
  <tr><td><kbd>&nbsp;1&nbsp;</kbd>, <kbd>&nbsp;2&nbsp;</kbd>, <kbd>&nbsp;3&nbsp;</kbd>, <kbd>&nbsp;4&nbsp;</kbd>, or <kbd>&nbsp;5&nbsp;</kbd></td><td>Change Color Scheme</td></tr>
  <tr><td><kbd>&nbsp;esc&nbsp;</kbd> or close window</td><td>Quit fract-ol</td></tr>
</table>

# Screenshots

## Mandelbrot set
![644px-Mandel_zoom_00_mandelbrot_set](https://user-images.githubusercontent.com/111196709/218947895-ca5bdc8c-938b-4d3f-9064-24ba06e02762.jpeg)

## Julia set
![JSr07885](https://user-images.githubusercontent.com/111196709/218948128-d71cb8e5-3bf9-4046-be96-808fe6ce0f96.gif)

## Tricorn Set
![720px-Mandelbar_20210819](https://user-images.githubusercontent.com/111196709/218948505-17ea0eec-7d4a-499f-87b2-b599b967eb33.png)

