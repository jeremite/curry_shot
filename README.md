## intro: stephen curry shot: web scraping + neural network <br>
use html web scraping to get stephen curry's shoot coordinates from http://buckets.peterbeshai.com
data used for training includes variable: the coordinate of each shoot made by stephen; the label: made shots(1) or miss shots(0)
try to practise building neural network from scrath (without framework like tensorflow or keras)
## lesson learning
when plot the coordinates of 'made shoot' and 'miss shoot' together at the beginning use matplotlib, easily found out that it's hard to draw a decision boundry cause the points overlap a lot.
Adjust the hyperparameters to achieve better accuracy: from 3 layers to 10 layers, training acc from 51% to 75%;
## next step
1. since the difference between training acc and val acc is large, then regularization should be attempted
2. try different learning_rate and regularization rate.
