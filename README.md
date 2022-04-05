Code files will be uploaded in "code" folder so check it out
These codes are for nystagmus detection
and the most of the symptoms are "shaking eyes"

- making connected layer having 2 inputs each and preprocessing test data
- x1 is the first input so the numpy array structure will be (N, 15, 60, 160) 
- x2 is the second input so the numpy array structure will be (N, 15, 60, 160) 
- y is only 1 output so the numpy structure will be (N, 3)
- I'm supposed to train the data and check up the result score to train the real data of "nystagmus" afterwards
- so far so good
- the plan has been changed. our plan was making connnected layer of 2 inputs but we decided to make just separte 2 models - 2022.04.06
