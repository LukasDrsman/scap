# scap
A minimal (read "garbage") screen capture script based on scrot and ffmpeg. I made it for my own personal entertainment and it messes up any output format other than gifs if I recall correctly.

## Dependencies
 - scrot
 - ffmpeg
 - bc

## Instal
### linux
```sh
sudo ./install
# or
doas ./install
```

## Usage
```sh
scap [duration in seconds] [output file name] [additional scrot arguments...]
```
Example:
```sh
scap 10 ~/test.gif -p -u
```
Output:
 - a gif
 - 10 seconds long
 - `-p` : enables pointer capture for scrot
 - `-u` : makes scrot track a specific window

## TODO
 - [ ] improve framerate
 - [ ] fix the awful mp4 output 
