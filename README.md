# ImageToText-MultiModals

The code takes a video as the input. 
It asks the user to choose a frame number from the video(it displays the number of frames for that video) and displays the output using two multimodals 
1. vikhyatk/moondream2
2. llava-hf/llava-1.5-7b-hf

I've used google colab to run this code, changed the runtime type to "T4 GPU".
The given "output.pdf" is the resultant output for "SampleVideo.mp4". 
The sample pdf displays the 180th frame of the video and the descriptions generated by the above 2 models.
