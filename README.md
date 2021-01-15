# Prediction-in-Weight-Lifting-Exercises

 This is a project towards scientific research of human activity recognition, which is focused on discriminating between different human activities (sitting/standing/walking etc.). The approach we propose for Weight Lifting Exercises for the sake of investigating how well an activity performed by the device wearer. Therefore, we might predict the manner in which they did exercise rather than only quantify how much of a particular activity they do, i.e. sports training, clinical training and so on.
  
  The goal of our first experiment was to assess whether we could detect mistakes in weight-lifting exercises of 06 participants in the study. In particular, the algorithm we made is eventually to predict which exercise participants took throughout 17 important indicators (let's see how we figured out 17 amongst 160 features of data-set) reported by a sensor device worn by themselves.

  The write-up will walk you through the following pinpoints:
  
- How we build the model to learn the mapping from input to output.
- How we used cross-validation to understand how well the model will perform.
- What we think the expected out of sample error is.
- Why we made the choices.

  Eventually, we use our prediction model to forecast which exercise (class) applied in 20 different test cases, where we don't actually know the outcomes. The links are enclosed.

Training Data : https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
Testing Data: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

Data is collected from the study, whereas 06 participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: 
- 1. Exactly according to the specification (***Class A***)
- 2. Throwing the elbows to the front (***Class B***)
- 3. Lifting the dumbbell only halfway (***Class C***) 
- 4. Lowering the dumbbell only halfway (***Class D***)
- 5. Throwing the hips to the front (***Class E***)

More information is available from the website here:
http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har

**This data-set is licensed under the Creative Commons license (CC BY-SA).**

