

##Authors
Krin Yongvongphaiboon @aboutkrin

Udit Bhansali @ubhansali 

##Overview
In our earlier discussions, we began thinking about how we can get live stock prices from Dow Jones. To ensure this, we have designed a GUI interface that allows a user to enter ticker symbols and get current price of the stock.

##Screenshot
![alt tag](https://github.com/oplS16projects/Krin-Udit/blob/master/fred.jpg)

##Concepts Demonstrated
Identify the OPL concepts demonstrated in your project. Be brief. A simple list and example is sufficient. 
* **Data abstraction** is used to provide access to the elements of the RSS feed.
* The objects in the OpenGL world are represented with **recursive data structures.**
* **Symbolic language processing techniques** are used in the parser.

##External Technology and Libraries
[web-server/insta](https://docs.racket-lang.org/web-server/run.html)
[jeeve/markets](https://planet.racket-lang.org/package-source/jeeve/markets.plt/1/2/planet-docs/manual/index.html)

##Favorite Scheme Expressions
####Krin
In Racket, I'm impressed how easy it was to create a webpage. The following code demonstrate how you can create a unique link for the webpage and be able to call a function. The function will be the body of the link itself.
```scheme
(define-values (start add-url)
  (dispatch-rules
   [("display-data") #:method "post"  display-data]
   [else get-first]))
```
####Udit

```scheme

```

#How to Download and Run
You may want to link to your latest release for easy downloading by people (such as Mark).

Include what file to run, what to do with that file, how to interact with the app when its running, etc. 

