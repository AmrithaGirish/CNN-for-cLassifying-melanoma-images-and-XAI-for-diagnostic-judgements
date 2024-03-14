# CNN-for-cLassifying-melanoma-images-and-XAI-for-diagnostic-judgements


The block diagram for the proposed classification model is shown in below Fig. The suggested design works
on the principal of ensemble method which aims at improving its accuracy of the result by combining multiple
models instead of using a singular model. It provides better predictive performance by combining predictions of
multiple models. This classification model is created by making integrated stacked ensemble models consisting
of networks like ResNet50, InceptionV3 and MobileNetV2. These models are first trained and saved individually
and then their outputs are concatenated along with an added dense layer by implementaion of LIME which will help to lighten up the black box                     ![Untitled Diagram drawio (1)](https://user-images.githubusercontent.com/89260426/188706612-7a0112e0-0bec-453b-bfc3-f5ca6b5be0fc.png).
