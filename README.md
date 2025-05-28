# Lab8-Starter

## [MyPage](https://ahmad-180.github.io/Lab8_Starter/) 

# How are graceful degradation and service workers related?

Graceful degradation and service workers are related in a beautiful way. Graceful degradation is a design approach that ensures that the core website still works regardless if certain features fail or aren't supported. This is where service workers come in to play because they are a perfect tool for this. Service workers served cached responses when your network is offline or slow and also intercept network requests. So for our case even if the user's connectivity downgrades the user will still see the recipes because the service worker has cached them. The pairing of features with reliable feedbacks is what makes graceful degradation and service workers helps make that happen.
