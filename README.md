# Upday Readme
Problem: 
our application should get a list of pics from shutterstock. our app can have pagination very smoothley. 

### Technologies:
I have created app with MVVM-C pattern. for handling work flow in our application I used coordinator pattern and for binding model with view in our application I used rxswift.
all pics will load with kingfisher.

Libs:
RxSwift ( reactive programming )
Kingfisher ( show images )

I use Swift package manager for third party libs.

I use clean architeture for developing application. 
first layer is domain. all models and use cases include in this layer.
second layer is platform. i have developed api service in this layer.
last layer is application. all screens include in this layer.

I use dependency inject for network layer. we can change varity implementation and inject to network layer.

this application has unit test and ui test. 
i wrote unit test for network layer.
for ui test, i wrote a senario for scroll collection and select one pic and check the alert controller.

