# First train then test different pictures
This is the first version, also the simplest.

You should run the training.py first in Spyder, then input "run_training" in the Ipython console, after training finished, 
uncomment the evaluation functions below, and use them to evaluate how the CNN works in test data. I offer two functions for
evaluating, one of them can randomly pick one picture from test datas and judge its emotion, the other can evalute all test 
datas and calculate the final accuracy of testing.

In this version, we first train with 1024 pictures, then test with 255 different pictures, and we only get an bad accuracy 
about **51~52%**, if use data argumentation, we can get **54.9%**. There is still lot of work to do.

**Do remember to change those directories to yourselves' in the code.**

[TensorFlow官网](http://www.tensorflow.org)

[Kevin Xu教学视频](https://www.youtube.com/watch?v=xWiEX6GMYUo&index=4&list=PLnUknG7KBFzqMSDZC1mnYMN0zMoRaH68r)

