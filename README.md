# IST Image Synthesis Dataset

This is the location of the IST synthesized image database. The IST View Synthesis Image Quality Dataset was used in the design of a no-reference quality assessment metric. The IST Dataset contains 180 images synthesized either with the VSRS-1D-Fast [1] or with the VSIM [2] algorithms, where rendering and compression artifacts are present; the corresponding original images and the texture and depth maps of the lateral source images (left and right), used for the synthesis, are included. The subjective quality scores of the synthesized and original images are also provided. 

Thus, the synthesized images obtained by the two methods, VSRS-1D-Fast and VSIM, were evaluated by human observers during the test sessions. 	All the images synthesized with the VSRS-1D-Fast algorithm were extracted from the SIAT database [3]. The images may contain compression artifacts, as well as rendering artifacts resulting from the synthesis process; each observer has given his opinion about the overall image quality.

The assessment method used in the subjective test is the absolute category rating with hidden reference (ACR-HR). ACR-HR is a single-stimulus method, where only a single image is presented at a time. Without informing the subjects, the test procedure also includes an original version of each synthesized image, shown as any other test stimulus. A five-grade scale was used, indicating five quality levels: Excellent, Good, Fair, Poor and Bad.

Before the start of the subjective test, subjects filled their name and gender in a form, and were carefully introduced to the method of assessment, to the types of distortions and to the grading scale, in a training session. During the training session, several images (different from the test session), with different levels of distortion, were shown with the corresponding quality score. During the subjective test, the images were presented in a random order. The subjective test interface is the same as in the training session but without the image label.

The experiment was conducted in two sessions. In the first session, the subjects assessed 197 images and in the second session, 182 images. The test session duration was approximately 25 minutes, for each session. In the first session, 25 subjects (24 males and 1 female) participated in the test, and in the second session, 18 subjects (15 males and 3 females). The subjects selected to participate in each session were essentially non-experts; more precisely, there were 17 subjects in the first session and 8 in the second session with no previous experience in image processing.

[1]	M.S. Farid, M. Lucenteforte, M. Grangetto, “Depth image based rendering with inverse mapping”, IEEE Workshop on Multimedia Signal Processing, Pula, Italy, September 2013. 

[2]	“VSRS-1D-Fast”. [Online]. Available: https://hevc.hhi.fraunhofer.de/svn/svn_3DVCSoftware, [Accessed November 2017]. 

[3] X. Liu, Y. Zhang, S. Hu, S. Kwong, C.-C. J. Kuo and Q. Peng, “Subjective and objective video quality assessment of 3D synthesized views with texture/depth compression distortion,” IEEE Transactions on Image Processing, vol. 24, no. 12, pp. 4847 – 4861, December 2015.
