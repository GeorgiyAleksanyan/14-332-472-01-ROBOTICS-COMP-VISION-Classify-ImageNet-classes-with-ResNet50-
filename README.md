# 14-332-472-01-ROBOTICS-COMP-VISION-Classify-ImageNet-classes-with-ResNet50-
Classifying ImageNet classes with ResNet50 Using pytorch by setting up the pre-trained network. Start by obtaining 10 images that are similar to Imagenet classes and classifying them. Then choose 10 images from 5 different classes (2 images/class). Report the confusion matrix, the accuracy, the f-score, precision and recall of the classifier.
**Special Thanks to the following people for providing the images for this project:**


0. Photo 0_0 by <a href="https://unsplash.com/@choudharyankith?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Ankith Choudhary</a> on <a href="https://unsplash.com/photos/honeybee-perched-on-yellow-flower-in-close-up-photography-during-daytime-AbBZKCPzLQQ?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

1. Photo 0_1 by <a href="https://unsplash.com/@milverton?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Michael Milverton</a> on <a href="https://unsplash.com/photos/black-and-yellow-bee-in-close-up-photography-FpFkjVDALnI?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
  
2. lynx: Photo 1_0 by <a href="https://unsplash.com/@zmachacek?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Zdeněk Macháček</a> on <a href="https://unsplash.com/photos/brown-lynx-cat-sSEEbAzB6fU?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

3. lynx: Photo 1_1 by <a href="https://unsplash.com/@zmachacek?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Zdeněk Macháček</a> on <a href="https://unsplash.com/photos/brown-and-black-cat-on-snow-covered-ground-k8z65TBa9dY?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

4. mangoose: Photo 2_0 by <a href="https://unsplash.com/@chandan_siddu?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Chandan Siddaramaia</a> on <a href="https://unsplash.com/photos/brown-and-white-animal-on-brown-wood-U5ANPofqlxM?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

5. mangoose: Photo 2_1 by <a href="https://unsplash.com/@veverkolog?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Dušan veverkolog</a> on <a href="https://unsplash.com/photos/brown-animal-standing-on-brown-field-vA_f4gPmg1w?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

6. obelisk: Photo 3_0 by <a href="https://unsplash.com/@sofiavilaflor?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Sofia Vila Flor</a> on <a href="https://unsplash.com/photos/white-concrete-tower-under-blue-sky-during-daytime-Ao-9mKqRAjo?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

7. obelisk: Photo 3_1 by <a href="https://unsplash.com/@louishansel?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Louis Hansel</a> on <a href="https://unsplash.com/photos/brown-obelisk-NDjDJW-fkPI?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

8. cock: Photo 4_0 by <a href="https://unsplash.com/@dareen0987?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">榮達 陳</a> on <a href="https://unsplash.com/photos/white-and-brown-hen-standing-on-gray-concrete-surface-iHzpnUYS3Zc?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

9. cock: Photo 4_1 by <a href="https://unsplash.com/@rosyid144?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Muhammad Rosyid</a> on <a href="https://unsplash.com/photos/a-rooster-standing-on-the-ground-in-a-forest-XH5QvKL2AL0?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
