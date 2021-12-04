# Test Plan

**Author**: Team ML4XRay

## 1 Overall Testing Strategy

Integration test (Hua Wang, Mengjun Han): test backend connections among backend components and backend-frontend connections. 

Functional system test: test the app against the functionalities in the requirements

Regression-testing: every time that we change our system and we need to make sure that the changes behave as intended and that the unchanged code is not negatively affected by the modification, by these changes.



## 2 Test Cases

| #    | test cases description | purpose                                                      | steps                                                        | expected result                                              | actual result | pass/ fail |
| ---- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------- | ---------- |
| 1    | upload image           | test the functionality of image uploading                    | Step 1. launch the app. Step 2. click "browse" button, and then choose a png file; Step 3. click "submit" button. | Step 1. loads the expected info of selected patient; fields in observations (height, weight, etc.) and medication requests can be empty. Step 2. the app shows a preview of the selected image. Step 3. shows the predicted results under "Prediction Results". |               |            |
| 2    | upload a wrong format  | test the functionality of throwing an error when a wrong image format is uploaded | Step 1. launch the app. Step 2. click "browse" button, and then choose a jpeg file; Step 3. click "submit" button. | Step 1. loads the expected info of selected patient; fields in observations (height, weight, etc.) and medication requests can be empty. Step 2...  Step 3... |               |            |
| 3    | take an annotation     | test the functionality of "Add an annotation for the image/prediction" | Step 1. launch the app. Step 2. type "test note" in the box and press "Add". | Step 1. loads the expected info of selected patient; fields in observations (height, weight, etc.) and medication requests can be empty. Step 2. under "Latest annotation", the app displays "Test Author" + time when the note was made + "test note". |               |            |

