# HAL-Mimic-2.0

This is an improvement over my existing Hal Mimic chatbot. This uses an Encoder-Decoder model along with an attention layer for better context responses compared to the previous chatbot which used two bi-directional LSTM layers.

You can check out the previous chatbot [here](https://github.com/Utkichaps/HAL-Mimic)

The model being used here is inspired by the Neural Machine Translation model used in the Natural Language Processing Specialization by Deep Learning.ai (Course 4 - Attention Models) and has been tweaked to be used as a chatbot

Point to remember: As this a more complex model than the previous one, for best results you will need a lot of data to train it (I tried it with around 3 years of chat data with a few friends I text). If you have a smaller dataset, you can try [my previous chatbot](https://github.com/Utkichaps/HAL-Mimic). That works well with less data too.
