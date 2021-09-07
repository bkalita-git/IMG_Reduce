[![TRY it](https://icon-library.com/images/try-icon/try-icon-8.jpg)](https://bkalita-git.github.io/img_red)

<br>
x is the original resolution
say 0.17753379642 byte per pixel
((165kb*2^10 = target byte)/0.17753379642 = output pixel)/x)*100

ex:
(2156x2876)*(((165*2^10)/0.17753379642)/(2156x2876))*100)%
or
((((165*2^10)/0.17753379642)/(2156x2876))*100)/100)*(2156x2876)
or
((165*2^10)/0.17753379642)/(2156x2876))*100
---------------------------------------------- * 2156x2876
		100
or

((165*2^10)/0.17753379642)
------------------------------ * 2156x2876
	(2156x2876)

or

target_pixel = (165*2^10)/0.17753379642)

aspect_ratio = w/h

h = round(sqrt(total/aspect_ratio))
w = round(h*aspect_ratio)

always (wxh)



create a javascript program to do that automatically
ex: 
target_pixel = (165*2^10)/0.17753379642) = 951706.116847
aspect_ratio = 2156/2876 = 0.74965229485
h = sqrt(951706.116847/0.74965229485)= 1126.73424195
w = 0.74965229485 * 1126.73424195 = 844.658910164
original quality level (information stored in %)





a 100% quality jpeg size =  width*height/1.7  in bytes

for ex: an image with 2156*2876 the max jpeg is = (2156*2876/1.7) bytes
now a 51% of it = (2156*2876/1.7) * 0.51 = 1.7MB

a 50% jpeg size wil be =   original_size*.5

calculate quality = 1100826/(2156*2876/1.7)






found blob jpeg size using  this 0.7499765025190587 factor  just multiply it
