# TransferLearning
Artificial Intelligence project

Credits to
-Frank Kane with Sundog Education(https://www.udemy.com/course/data-science-and-machine-learning-with-python-hands-on/)
-Nvidia Deep learning course(https://courses.nvidia.com/courses/course-v1:DLI+S-FX-01+V1/)

I used knowledge gained from these two courses to share a presentation with my class to cover transfer learning.
Using resnet50, we took a look at the model summary (50 layer deep neural network), and how well it performed classifying a few images.
Next, I used the vgg16 to create an automatic doggy door. This model classified images of animals to only let dogs outside. Keeping the kitty cats inside and predators out.
Finally, I took the vgg16 model without the top. That means I cut the output layers off and created my own. This lets me place my own output for the task at hand.
I wanted to have a pretrained classifier to only let a single dog in. For this project we used former President Barrack Obama's dog 'Bo'.(this was used in the course, I didn't just have random pictures of the Obama's family dog laying around)
To train this model I only needed 20 pictures of 'Bo'.
I froze the weights and finetuned the model to be extremely accurate at detecting if 'Bo' was in the picture or not.
