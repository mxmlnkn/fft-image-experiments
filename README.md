Experiments with plane-filling curves and Fourier transform
===========================================================

A set of visual experiments: applying Fourier transform to various plane-filling curves.

![Sample results](media/curves-fft-sample.png)

Running
-------

To generate images, run:
```` sh
$ python fft_experiments.py
````
Or just
```` sh
$ make
````

To change parameters, edit the file fft_experiments.py.


Requirements
------------

Python 3, pillow, numpy.


Tests
-----
Some tests are present. Run
```` sh
$ make test
````
to execute them.


# Scaling the recursion depth

## Hilbert Curve

Depth  | FFT
-------|--------------
0      | ![](media/fft-inverted-hilbert-curve-order_0.png)
1      | ![](media/fft-inverted-hilbert-curve-order_1.png)
2      | ![](media/fft-inverted-hilbert-curve-order_2.png)
3      | ![](media/fft-inverted-hilbert-curve-order_3.png)
4      | ![](media/fft-inverted-hilbert-curve-order_4.png)
5      | ![](media/fft-inverted-hilbert-curve-order_5.png)
6      | ![](media/fft-inverted-hilbert-curve-order_6.png)
7      | ![](media/fft-inverted-hilbert-curve-order_7.png)
8      | ![](media/fft-inverted-hilbert-curve-order_8.png)
9      | ![](media/fft-inverted-hilbert-curve-order_9.png)
10     | ![](media/fft-inverted-hilbert-curve-order_10.png)
11     | ![](media/fft-inverted-hilbert-curve-order_11.png)
12     | ![](media/fft-inverted-hilbert-curve-order_12.png)
13     | ![](media/fft-inverted-hilbert-curve-order_13.png)

## Hilbert Pattern

Depth  | FFT
-------|--------------
0      | ![](media/fft-inverted-hilbert-pattern-order_0.png)
1      | ![](media/fft-inverted-hilbert-pattern-order_1.png)
2      | ![](media/fft-inverted-hilbert-pattern-order_2.png)
3      | ![](media/fft-inverted-hilbert-pattern-order_3.png)
4      | ![](media/fft-inverted-hilbert-pattern-order_4.png)
5      | ![](media/fft-inverted-hilbert-pattern-order_5.png)
6      | ![](media/fft-inverted-hilbert-pattern-order_6.png)
7      | ![](media/fft-inverted-hilbert-pattern-order_7.png)
8      | ![](media/fft-inverted-hilbert-pattern-order_8.png)
9      | ![](media/fft-inverted-hilbert-pattern-order_9.png)
10     | ![](media/fft-inverted-hilbert-pattern-order_10.png)
11     | ![](media/fft-inverted-hilbert-pattern-order_11.png)
12     | ![](media/fft-inverted-hilbert-pattern-order_12.png)
13     | ![](media/fft-inverted-hilbert-pattern-order_13.png)

## Dragon Curve

Depth  | FFT
-------|--------------
0      | ![](media/fft-dragon-diagram-0.png)
1      | ![](media/fft-dragon-diagram-1.png)
2      | ![](media/fft-dragon-diagram-2.png)
3      | ![](media/fft-dragon-diagram-3.png)
4      | ![](media/fft-dragon-diagram-4.png)
5      | ![](media/fft-dragon-diagram-5.png)
6      | ![](media/fft-dragon-diagram-6.png)
7      | ![](media/fft-dragon-diagram-7.png)
8      | ![](media/fft-dragon-diagram-8.png)
9      | ![](media/fft-dragon-diagram-9.png)
10     | ![](media/fft-dragon-diagram-10.png)
11     | ![](media/fft-dragon-diagram-11.png)
12     | ![](media/fft-dragon-diagram-12.png)
13     | ![](media/fft-dragon-diagram-13.png)

## Gosper Diagram

Depth  | FFT
-------|--------------
0      | ![](media/fft-gosper-diagram-0.png)
1      | ![](media/fft-gosper-diagram-1.png)
2      | ![](media/fft-gosper-diagram-2.png)
3      | ![](media/fft-gosper-diagram-3.png)
4      | ![](media/fft-gosper-diagram-4.png)
5      | ![](media/fft-gosper-diagram-5.png)
6      | ![](media/fft-gosper-diagram-6.png)
7      | ![](media/fft-gosper-diagram-7.png)
8      | ![](media/fft-gosper-diagram-8.png)
9      | ![](media/fft-gosper-diagram-9.png)
10     | ![](media/fft-gosper-diagram-10.png)
11     | ![](media/fft-gosper-diagram-11.png)
12     | ![](media/fft-gosper-diagram-12.png)
13     | ![](media/fft-gosper-diagram-13.png)
