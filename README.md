# pixel-text-encoder

## 1. Project Description
In digital video and photography, the $Y'C_BC_R$ is a color space used as part of the color image/video pipeline. $Y'C_BC_R$ is based on RGB primaries. $Y'$ is the luma componant (luminosity), and $C_B$ and $C_R$ are the blue-difference and red-difference chroma componants.

## 2. Technical Information: Pixels and colour

### 2.1 Physics of colour



### 2.2 RGB

A pixel is represented by three values: **R**ed** B**blue** G**reen. Each channel commonly has values ranging from 0-255.

For example:

|**Colour**|**R**|**G**|**B**|
|---|---|---|---|
|Black|0|0|0|
|White|255|255|255|
|Red|255|0|0|
|Green|0|255|0|
|Blue|0|0|255|
|Gray|128|128|128|
|Yellow|255|255|0|

With a 8-bit RGB values, there are $256^3=16,777,216$ possible colours. RGB is usefull in regard to the possible combination of colour values, but what it doesn't account for is the luma of an image. Luma represents the achromatic portion (black and white) of an image, representing the brightness. \
Human vision relies more on luminance differences than chromatic ones, which is why $Y'C_BC_R$ colour space has been chosen as a basis for the encoding. $Y'C_BC_R$ is still based on RGB primaries ($C_BC_R$ values), but it also accounts for luminance ($Y'$)


## 3. Development Environment

- GitHub
- GitHub Codespaces
- C23
- gcc


## 4. Project Structure

```text
pixel-text-encoder/
|
|--- input/
|
|--- output/
|
|--- src/
|    |---main.c   
|    |---colour.c   
|    |---colour.
|    |---encoder.c   
|    |---encoder.h
|    |---file_reader.c   
|    |---file_reader.h
|    |---pixel_maker.c   
|____|___pixel_maker.h
```

## Resources 

- [Microsoft - "About YUV Video"](https://learn.microsoft.com/en-us/windows/win32/medfound/about-yuv-video?utm_source=chatgpt.com)
- [Charles Poynton - "Frequently Asked Questions about Gamma"](https://www.cs.tufts.edu/~nr/cs257/archive/charles-poynton/GammaFAQ.pdf)
- [emby - "YCbCr Video"](https://emby.media/learn/articles/video/color-pixel-formats/Video-YCbCr.html?utm_source=chatgpt.com)
- [NASA - "Colorspace Transforms"](https://gmao.gsfc.nasa.gov/media/gmaoftp/jkolassa/Matlab_scripts/colorspace.html?utm_source=chatgpt.com)
- [MIT - "Color Technology"](people.csail.mit.edu/fredo/comp-photo-book/02-fundamentals-09-color-technology.html?utm_source=chatgpt.com)
- [XILINX - "Color-Space Converter: RGB to YCrCb](https://docs.amd.com/api/khub/documents/zCxg8kafffeq02OBDWNnxA/content?utm_source=chatgpt.com)



