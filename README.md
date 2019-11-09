# Free Data Collections for students beginning to learn ML
A collection of free data items that can be used by students beginning to learn ML (machine learning) .

# Data for Training: "ForTraining_0001.csv". 10000 rows and 12 columns

### Data has two input columns/features/independent numerical variables called A and B
### 9 mathematical operations have been performed to generate 9 dependent numerical columns
#### They are as below

* Addition = A + B
* Subtraction = A - B
* Multiplication = A * B
* Division = A / B
* Sin(Addition) = sin (A + B)
* Cos(Addition) = cos (A + B)
* sqrt(Addition) = SQRT( A + B) if (A + B) >= 0 or -1.00 if (A +B ) < 0
* 2 ^ Addition = 2 ^ (A +B)
* Log(Addition) = log(A + B)

### Additionally there is a dependent column present for classification training.
* ODD_OR_EVEN(CEIL(A+B)) = If MODULUS of CEIL(A + B) = 0 then "EVEN" else "ODD" [To be used for *classification training *]

### You can use A, B as input feature vectors and any of the operations (one at a time) to train your model. You can use it for 9 regressions and 1 classification.
