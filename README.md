# EXP-2 Welcome message in Message box with IF Condition and Switch case
## NAME : SAI SANJIV R 
## REG.NO : 212223230179
# AIM : 
to create a Welcome message in Message box with IF Condition and Switch case.

## PROCEDURE : 
IF Condition Robot (special for RAM)

### IF:
if name = RAM → say Welcome Mr. Ramachandran

else → say Welcome <name>


#### steps

1. open UiPath Studio → make new Process → open Main.xaml.


2. drag a Sequence.


3. create variable → userName (String).


4. drag Input Dialog:

Title: Enter Name

Label: Please type your name:

Result → userName



5. drag an If activity:

Condition → userName.ToUpper = "RAM"



6. inside Then → add Message Box:

Text → "Welcome Mr. Ramachandran"



7. inside Else → add Message Box:

Text → "Welcome " & userName



8. Run ▶ → try with RAM and with other names.




---

###  2) SWITCH Case Robot (different greeting for every name)
RAM → Welcome Mr. Ramachandran

SITA → Welcome Ms. Sita Devi

JOHN → Welcome Mr. John Carter

anything else → Welcome <name>


#### steps

1. add variable userName (String).


2. drag Input Dialog →

Title: Enter Name

Label: Type your name:

Result → userName



3. drag a Switch activity:

TypeArgument → String

Expression → userName.ToUpper



4. Add Case "RAM" → Message Box:

"Welcome Mr. Ramachandran"



5. Add Case "SITA" → Message Box:

"Welcome Ms. Sita Devi"



6. Add Case "JOHN" → Message Box:

"Welcome Mr. John Carter"


7. Add Default → Message Box:

"Welcome " & userName


8. Run ▶ → type different names.

---

## OUTPUT :
### IF ELSE: 
<img width="1917" height="1071" alt="Screenshot 2025-08-23 085635" src="https://github.com/user-attachments/assets/923d630b-4e19-40d9-9b1b-09511ca968bb" />
<img width="185" height="178" alt="Screenshot 2025-08-23 085650" src="https://github.com/user-attachments/assets/d1987cf4-89dc-496b-9f2a-af02b67afd79" />
<img width="164" height="181" alt="Screenshot 2025-08-23 085732" src="https://github.com/user-attachments/assets/da8d43b0-b5ff-4467-9c88-157462ae9eee" />



### SWITCH :

<img width="1919" height="1079" alt="Screenshot 2025-08-23 090654" src="https://github.com/user-attachments/assets/4fd6a793-6737-480f-a840-586263617195" />
<img width="150" height="179" alt="Screenshot 2025-08-23 090709" src="https://github.com/user-attachments/assets/0532399a-f76a-47ec-a70c-766b9ca503e9" />

## RESULT : 
Thus the process to display Welcome message in Message box with IF Condition and Switch case is created successfully.

