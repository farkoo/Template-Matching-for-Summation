# Template-Matching-for-Summation

In this program, using the pattern matching process, we try to add the Persian numbers in the text together and write the result at the bottom of the page.

Numbers 0 to 9 in 4 different sizes are in different places in the images and the images are impregnated with different amounts of salt and pepper noise.

The first step in solving this problem is to find the right patterns. Then, using the **normxcorr2** function and selecting the appropriate Threshold, we investigate the occurrence of patterns in the image. It should be noted that due to the presence of salt and pepper noise in the image, the noise is first eliminated using the **median** filter, and according to the initial amount of image noise, a suitable value is adopted for Threshold.

100 images have been used to measure the performance of the program.

The accuracy of my method is **64%**.

An example of running the program is attached.

## Input
<p align="center">
<img src="https://github.com/farkoo/Template-Matching-for-Summation/blob/master/Test.png" height=550 width=500>
</p>

## Output
<p align="center">
<img src="https://github.com/farkoo/Template-Matching-for-Summation/blob/master/Result.png" height=550 width=500>
</p>


## Support

**Contact me @:**

e-mail:

* farzanehkoohestani2000@gmail.com

Telegram id:

* [@farzaneh_koohestani](https://t.me/farzaneh_koohestani)


## License
[MIT](https://github.com/farkoo/Template-Matching-for-Summation/blob/master/LICENSE)
&#0169; 
[Farzaneh Koohestani](https://github.com/farkoo)
