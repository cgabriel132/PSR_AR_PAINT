# PSR Ar_Paint
***
Projeto da unidade curricular de Programação de Sistemas Robóticos (Grupo 13 - P2).  
Trabalho realizado por:  

- Beatriz Cruzeiro 97934
- Carlos Gabriel Cardoso 98504
- João Cruz 99980

## AR Paint

This program allows you to use an object of your choice as a brush and paint on a white canvas by moving the object within the frame as it is being recorded by your webcam. You may choose to use the video stream mode, which lets you paint on the live video of your camera, as opposed to a white canvas and you can mirror your videocapture!

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

```
#### Extras:
. A menu showing all the shortcuts  
. Painting with other colors  
. Being able to erase the paint  
. Thicker/Thinner brush  
. Mirror video capture  
. Paint with your mouse  
