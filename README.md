# Machine-Learning-Stanford

We are gaving two Course Together here Old Version and New Version Both

[Old Link Videos](https://www.youtube.com/watch?v=gb262LDH1So&list=PLiPvV5TNogxIS4bHQVW4pMkj4CHA8COdX)

[Old PPT](https://github.com/vkosuri/CourseraMachineLearning/)

[New PPT](https://github.com/LasithaAmarasinghe/Machine-Learning-Specialization-Coursera/)

Some Highlihs to Remember:
- Siimultanous updates of parameters w,b

- Reference --> Week 1 : Gradient descent intuition (Look Slides)
- **consider graph : y-axis J(w) and x-axis : w decrease in weight**
 - decrease J(w) ? --> no --> slope is negative
 - otherwise slope positive
- Derivative(cost Fucntion) with respect to Weight
  - Decrease value of weight increase Cost so Derivative is --> Negative
  - Decrease value of weight Decrease Cost so Derivative is --> Positive
  - Weight = Weight - alpha (derivative Result) --> equation --> Achieve our desire Aim
  - Links to Understand [Derivative](https://www.mathway.com/examples/calculus/derivatives/using-the-limit-definition-to-find-the-derivative?id=665)



 - Gradient descent finds Local Minimum
 - Varability in Learning Rate
   - The quantity of derivative will tell us learning rate steps with fixed value

- Covex Function have onlt one local minima otherwise the cost function depending on initial stage to start to end up with different local minima
- Batch gradient descent --> different local minimums in --> cost function

**overfitting vs under**
- overfitting occurs when a model learns the training data too well, including noise, and performs poorly on unseen data, while underfitting happens when a model is too simple to capture the underlying patterns in the data, leading to poor performance on both training and testing sets

**overshoot**
- Gradient descent never reach min because LR too high

## Week 2
- Vectorisation faster and short the code
- Multiple linear Regression : different factors to measure house for ex : size , rooms, life --> rooms more its adds 2000 dollars * number of rooms in house price
- w1 x1 , w2 x2 ...wn xn
- Vecorisation Part 1-2 Explain parallel processing of code 
  



