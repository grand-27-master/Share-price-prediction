# Share-price-prediction

I’ll build a Python deep learning model that will predict the future behavior of stock prices. I assume that the reader is familiar with the concepts of deep learning in Python, especially <a href="https://colah.github.io/posts/2015-08-Understanding-LSTMs/">Long Short-Term Memory</a>.

While predicting the actual price of a stock is an uphill climb, i can build a model that will predict whether the price will go up or down. The data and notebook used for this project can be found here. It’s important to note that there are always other factors that affect the prices of stocks, such as the political atmosphere and the market. However, I won’t focus on those factors.
LSTMs are very powerful in sequence prediction problems because they’re able to store past information. This is important in our case because the previous price of a stock is crucial in predicting its future price.
