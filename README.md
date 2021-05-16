# Final_Project_BIT
Code

Your goal is to create an algorithm that identifies multimodal hate speech in internet memes.

Take an image, add some text: you've got a meme. Internet memes are often harmless and sometimes hilarious. However, by using certain types of images, text, or combinations of each of these data modalities, the seemingly non-hateful meme becomes a multimodal type of hate speech, a hateful meme.

At the massive scale of the internet, the task of detecting multimodal hate is both extremely important and particularly difficult. As the illustrative memes above show, relying on just text or just images to determine whether or not a meme is hateful is insufficient. Your algorithm needs to be multimodal to excel at this task!

The team at Facebook AI has decided to take the challenge head on—and they want your help! The team defines hate speech as:

A direct or indirect attack on people based on characteristics, including ethnicity, race, nationality, immigration status, religion, caste, sex, gender identity, sexual orientation, and disability or disease. We define attack as violent or dehumanizing (comparing people to non-human things, e.g. animals) speech, statements of inferiority, and calls for exclusion or segregation. Mocking hate crime is also considered hate speech.

This definition mirrors the community standards on hate speech employed by Facebook, and is intended to provide an actionable classification label: if something is hate speech according to this definition, it should be taken down; if not, even if it is distasteful or objectionable, it is allowed to stay.

Starter code from Facebook AI's MMF is also available on GitHub to help you get started.

This challenge provides an opportunity to help advance multimodal machine learning systems and push forward state-of-the-art performance on a novel data set. We can't wait to see what you come up with!

Note on Annotator Accuracy

As is to be expected with a dataset of this size and nature, some of the examples in the training set have been misclassified. We are not claiming that our dataset labels are completely accurate, or even that all annotators would agree on a particular label. Misclassifications, although possible, should be very rare in the dev and seen test set, however, and we will take extra care with the unseen test set.

As a reminder, the annotations collected for this dataset were not collected using Facebook annotators and we did not employ Facebook’s hate speech policy. As such, the dataset labels do not in any way reflect Facebook’s official stance on this matter.

All of the data for the Hateful Memes competition. This zip file is 3.4 GB! It contains the data license, readme, image files and text, training, dev, and test jsonl splits, as well as the submission format csv. It is password protected with the password KexZs4tn8hujn1nK

The zip file consists of the following files:

license.txt - the data set license
README.md - the data set readme
img/ - the directory of PNG images
train.jsonl - the training set
dev.jsonl - the development set
test.jsonl - the test set
submission_format.csv - copy of the submission format for leaderboard
