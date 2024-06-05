                                                              Import data from Google Sheet to firebase
                                                           -----------------------------------------------
* Given the  multiple steps:

Steps-1 : 
* First of all open the google sheet.
* Change the Spreadsheet name and sheet name.
* Create temp data such as image given the bellow
* Now you go file menu button and show share option click  open publish to web
* show the preview data 
![1](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/19f12580-4d7d-4489-850e-32e7fda3ff4e)

Step-2 :
* Open Google Chrome Browser.
* Click the link [https://firebase.google.com/].
* click (Go To Console) button given the top right side.
* ![2](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/888d60f8-6a06-435f-827a-4b2c286c956d)
* Create Add New Project click
* ![3](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/df6142ad-1aa7-4d3a-91dc-40a61e3de6a2)
* Enter your Project Name in firebase.
* ![4](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/948efa19-0185-406e-8d18-bb9a9c5106b8)
* Click Continue
* ![5](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/09b26161-a0c0-4ae0-a80b-79faecd8985f)
* Choose or create a Google Analytics account then create.
* ![6](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/11bf671d-493f-4f46-b134-65782663500b)
* Your Firebase project is ready
* ![7](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/4f0d6695-1ccd-4898-81ae-fde16b3ed760)

Step-3 :
* Show the Dashboard in firebase
* And you go now left side Build option and opne the list and select (Realtime basebase) option
* ![8](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/91bae57f-70ce-4f85-b3dd-88d0b2d5b77f)
* Create Realtime Database Name
* ![9](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/47d278f6-5243-453a-b17e-288cf4686403)
* Setup database is enable.
* you go now realtime database and select rules tab and convert false statement true both and click publish button.
* ![10](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/84f4d92b-af74-4b2b-95bb-28d68ff8d59a)
* then come data tab

Step-4 :
* Go to google sheet and select Appscript from the extension main menu.
* ![11](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/784984e9-213a-40a3-876c-3be386e875fc)
* Rename Project Name
* ![12](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/5db2edd2-717b-421a-a749-137cb5c03203)
* Create code from in Code.gs file
* And change spreadsheetID: "1URr9bS6lu83C3Td9kJf6sEqblnejqfFmQpjGHyv0TKg", And firebaseUrl: "https://project1-52af0-default-rtdb.firebaseio.com/",
* ![13](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/2f190a31-b769-493b-b6bf-a764ef1109a2)
* ![14](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/44274016-4864-4cb3-b51b-d53838d166b4)
* Go to Project setting open and checkbox (Show "appsscript.json" manifest file in editor) Option.
* ![15](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/ec67acad-08b3-4f91-8ea9-28695f3cf243)
* Go to editor and click [appsscript.json].
* create code from [appsscript.json].

Step-5 :
* Go to GetEnvironment and select initialize option
* On click Run Button
* ![16](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/40b49c5a-3f5b-4328-a938-0ee7ca187636)
* Verify Account and.
* Go to firebase and show the all data .
* ![17](https://github.com/Digisoft-Noida/firebase-flutter/assets/171772732/e1e1f3e9-2df8-45b8-9c2d-64e37117d21f)
* Import data from firebase.


  End_________

