# Use Case Model

**Author**: \<Team ML4XRay\>

## 1 Use Case Diagram

*This section should contain a use case diagram with all the actors and use cases for the system, suitably connected.*

![Use case diagram](C:\Users\chaof\cs6440\Practicum\practicum\Final Delivery\Documentation Directory\UseCaseDiagram.png)

## 2 Use Case Descriptions

### "Log in" Use Case

- Requirements: "Log in" allows the user, specifically a practitioner, to log into the system with their credentials.  
- Pre-conditions: the app is launched. 
- Post-conditions: at the end of the use case, the user is able to log into the app with their credentials.  
- Scenarios: 
  1. the user launches the app.
  
  2. the user enters or selects "User Name" from the drop down list and enters "Password". 
  
  3. the user presses the "Login" button.
  
     

### "Choose a patient" Use Case

- Requirements: "Choose a patient" allows the user to choose a patient from the group he/she has access to. 

- Pre-conditions: the user is logged in. 

- Post-conditions: at the end of the use case, a specific patient is chosen. 

- Scenarios: 

  1. the user selects a patient from the list on the screen.
  
  

### "View patient demographic info" Use Case

- Requirements: "View patient demographic info" allows the user to view the key demographic info of a patient. 

- Pre-conditions: a patient is chosen. 

- Post-conditions: at the end of the use case, key demographic info of a given patient is displayed, including name, gender, and date of birth. 

- Scenarios:

  1. the user views the displayed patient demographic info on the banner area of the app 
  
  

### "View key observations and meds" Use Case

- Requirements: "View key observations and meds" allows the user to view the key observations and medication requests of a patient. 

- Pre-conditions: a patient is chosen. 

- Post-conditions: at the end of the use case, key observations of a given patient are displayed (including height, weight, blood pressures, and metabolic indicators such as LDL and HDL) as well as a list of medication requests. 

- Scenarios:

  1. the user views the patient's observations and medication request list displayed on the app. 

  

### "Predict possible chest disease" Use Case

- Requirements: "Predict possible chest disease" allows the user to predict the type of disease based on a pre-trained model using machine learning. 

- Pre-conditions: a chest X-ray image is uploaded. 

- Post-conditions: at the end of the use case, a message the indicating no disease or the type of disease is displayed under "Prediction Result". 

- Scenarios

  1. the user clicks on "Browse" to choose a png image file from a local device. 
  2. the app displayed a preview of the chosen file. 
  3. the user presses the "Submit" button. 
  4. results of the prediction are displayed under "Prediction Results". 
  5. the user can choose to add an annotation to the image or prediction. If so, the app displays the latest annotation under "Latest Annotation", including the author (Test Author) and time when the annotation is made. 

