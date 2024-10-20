## OBJECTIVE
Learn more about other Regex commands in UiPath.
## TECHNICAL REQUIREMENTS
 1)  [Is Text Matching](https://docs.uipath.com/activities/other/latest/workflow/is-match)
 2)  [Replace Matching Patterns](https://docs.uipath.com/activities/other/latest/workflow/replace)
 3)  [Assign activity](https://docs.uipath.com/studio/standalone/2023.10/user-guide/the-assign-activity)
 4)  [Message Box](https://docs.uipath.com/activities/other/latest/workflow/message-box)
 5)  [Sequence](https://docs.uipath.com/studio/standalone/2023.10/user-guide/sequences)

## PROCEDURES
1) Assign,Enter the information you want to search in 


   ![image](https://github.com/user-attachments/assets/b76a1c01-4d79-4b62-848a-7bc60d951025)


3) Insert Is Text Matching > Properties Panel inside the patterns box put the a Regular expresion > insert the variable in Text to search in box > in the Result box make a variable
  * Result Variable: boolean var

     ![image](https://github.com/user-attachments/assets/29f81b57-822e-4a67-bc37-dab765bd40cb)

4) Insert a new sequance > Assign

   ![image](https://github.com/user-attachments/assets/68ce2ed9-d9a0-481b-9f6d-73d180be5f30)

5) Insert Replace Matching Patterns > Properties Panel inside the patterns box put the Text > In the Replace with Text Select the text that will be replacedx > in the Result box make a variable
   
     
    ![image](https://github.com/user-attachments/assets/1e24c012-1670-4791-8739-6384f9d1a2b0)



## Results
To watch  Bot run this video, [click here](https://drive.google.com/file/d/1fuQc-gi1RbzHNjNmb6styhAbGYtdc5Wr/view?usp=drive_link)

