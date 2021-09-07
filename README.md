
<p align="center">
  <ahref="https://bkalita-git.github.io/img_red"> <img src="https://icon-library.com/images/try-icon/try-icon-8.jpg"></a>
</p>
<br>

METHODS<br>
*x is the original resolution say 0.17753379642 byte per pixel*
```
target_pixel = (165*2^10)/0.17753379642) = 951706.116847
aspect_ratio = 2156/2876 = 0.74965229485
height_of_new_image = sqrt(951706.116847/0.74965229485)= 1126.73424195 pixel
width_of_new_image  = 0.74965229485 * 1126.73424195 = 844.658910164 pixel
original quality level (information stored in %)
a 100% quality jpeg size =  width*height/1.7  in bytes
for ex: an image with 2156*2876 the max jpeg is = (2156*2876/1.7) bytes
now a 51% of it = (2156*2876/1.7) * 0.51 = 1.7MB
a 50% jpeg size wil be =   original_size*.5
calculate quality = 1100826/(2156*2876/1.7)
```
