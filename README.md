# Animal Identification with Convolutional Neural Networks

## Abstract

Animal identification is an important practice with numerous applications in the realms of wildlife conservation, poaching, animal behavior research, and biodiversity monitoring. It is essential for animals to be identified accurately, especially when the amounts of useful data collected may be limited. We train 3 Convolutional Neural Networks (CNNs), including a basic CNN designed from scratch, ResNet-18 trained from scratch, and a version ResNet-18 pre-trained on ImageNet, to determine which CNN yields the most accurate and precise animal identification. The ANIMAL-10N dataset serves as our benchmark for evaluating the performance of the CNN architectures. After training, various experiments were performed on the models to learn about their abilities and the impacts of transfer learning on such tasks. We calculated each neural network's top-1 classification accuracy, precision and recall. ResNet-18 with transfer learning emerged as the most accurate model for animal classification with a peak training accuracy of $87.6\%$ over 20 epochs. Its classification patterns were quantified used the Confusion Matrix and its features were visualized using Saliency Maps. The contribution this paper makes is exploring the learning behaviour and features of CNNs for animal identification and analyzing the effects of transfer learning, as well as shallow versus deep networks on their classification effectiveness. The results showcase that transfer learning makes the biggest contribution to achieving highly-accurate animal classification. 


