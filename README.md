# PSR Ar_Paint

## AR Paint

This program allows you to use an object of your choice as a brush and paint on a white canvas by moving the object in the air as it is being recorded by your webcam. You may choose to use the video stream mode, which lets you paint on the live video of your camera, as opposed to a white canvas, you can mirror your videocapture and even paint a picture so the program can evaluate it!

To use this program, you need to create a threshold.json file using the program, color_segmenter.

### How to run the program ar_paint.py:

To run the code, you need to pass in the required argument -j, of json file path. You may also pass in some additional arguments, as follows.

```text
optional arguments:
  -h, --help            show this help message
                        and exit
  -j, --json
                        Full path to json file.
  -usp, --use_shake_prevention
                        To use shake prevention.
  -vs, --video_stream
                        To draw on displayed
                        frame
  -m, --mirror_image    Mirror the image
                        captured by camera
  -np, --numbers_paint
                        Path to file to paint by
                        numbers

```

***
Projeto da unidade curricular de Programação de Sistemas Robóticos.
Trabalho realizado por:

- Beatriz Cruzeiro
- Carlos Gabriel Cardoso
- Joáo Cruz
