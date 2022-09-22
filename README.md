# FleaMarket
ROOM library implementation to show data persistence.

App overview.
Fragment 1:
A recyclerview displays the list of items in the market database. 
Each item row has a bitmap image of the item displayed and the name and location of its production.
A fab is at the bottom right to add new items to the database.


<img width="179" alt="image" src="https://user-images.githubusercontent.com/38509636/191684632-e3ea9bc2-7067-483e-8cdc-cb565bc2425c.png">

Fragment 2:
There are 4 textfields to add a new item, with 1 checkbox to show whether the item is in season or not. 
Save button saves the item to db and displaed in Fragment 1.


<img width="179" alt="image" src="https://user-images.githubusercontent.com/38509636/191685149-3ec52759-2915-4a4c-8ea3-745590509e18.png">

Fragment 3:
A details fragment to show more info about the item once clicked in Fragment 1. The updates based on the navigation arguments sent to fragment.
Fab at bottom right to update the item.


<img width="180" alt="image" src="https://user-images.githubusercontent.com/38509636/191685666-1a6e1de6-fd3b-4b9b-b577-25c797b630e3.png">

Fragment 4:
Details about the item are already displayed in the textfields based on navigation arguments sent, including the URL of the bitmap image. 
Any updates will be echoed in the database.


<img width="178" alt="image" src="https://user-images.githubusercontent.com/38509636/191686294-2ec6a724-d62d-4e0f-bf79-c74c85025dde.png">

Clicking on Delete button will display an Alert Dialog to prompt user to delete or not.


<img width="179" alt="image" src="https://user-images.githubusercontent.com/38509636/191686846-ed4a6c0c-36f0-4c92-956b-62e1dbe8db8a.png">






