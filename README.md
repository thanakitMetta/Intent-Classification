# Intent-Classification

Intent Classification Idea:
The classification model and the pre-trained BERT model from Kaggle were the major
inspirations for this intent classification approach. Start by using pandas to organize the data, and
then use LabelBinarizer to perform the one-hot coding. After that, the data was lowercased and
tokenized using BERT En Uncased preprocess version 3 and the Tensorflow 2 framework. The
data should then be added to the categorization model. To avoid overfitting, the dropout
regulation was used for the classification model, and the layer was densely packed with 7 units.
For an output layer, the activation function is softmax. Then, it was adjusted by setting the
optimizer to Adam with a learning rate of 0.00001, batch size of 32, and epoch equal to 5. The
loss function was also set to categorical cross entropy loss.

Intent Classification Good Points and Difficult parts:
In my opinion, the tough part is the planning process where I have to find the suitable
model that can make my submission pass the based line. The benefits of this approach include
excellent accuracy for any given dataset and cost-effective memory utilization. In addition,
BERT is able to handle various lengths of input which make it extremely well-fitting for the
given task.

The Lesson Learn From Intent Classification task:
This hackathon made me understand more about how to choose the BERT model due its
varied versions. Developing the model by hyperparameter tuning also shows me which
parameters largely affect the output. So, I can make use of this experience next time I fine-tune
the model. Moreover, this hackathon helped me dig deeper into the field of transformers with the
use of the BERT model.
