# King David - Software Design Description



## Programming languages and software tools:
* Programming languages: C#.
* IDE: Visual Studio.
* GameEngine: Unity.

## Code structure:
### The code is divided into 8 main classes:
### 1. Battle System - The fighting process in the game.
#### Main Methods:
* StartBattle.
* BattleNotification.
* AttackEffect.
* BattleCharacters.
### 2. DialogManager - The process of dialogue with the other NPC in the game.
#### Main Methods:
* DialogController.
* DialogHandler.
* StartQuestAfterDialog.
### 3. Items - The process of creating / obtaining / using Items in the game.
#### Main Methods:
* Inventory.
* ItemButton.
* ItemsAssets.
* ItemsManager.
### 4. LevelManager - The process of switching between scenes + building the maps in the game(TileMap).
#### Main Methods:
* ExitArea.
* ArrivalArea.
* TileMaps.
* MapEdges.
### 5. Managers - The core processes of the game (sound, camera, main menu).
#### Main Methods:
* AudioManager.
* CamController.
* GameManager.
* MenuManager.
### 6. Player - All processes related to the player (movement, stats, battles, items).
#### Main Methods:
* PlayerMovement.
* PlayerAnimation.
* PlayerStats.
### 7. Quests -  The process of accepting / completing quests in the game.
#### Main Methods:
* QuestManager.
* QuestObject.
* QuestZone.
### 8. Shop - The process of buying / selling items in the game.
#### Main Methods:
* ShopKeeper.
* ShopManager.
* BuyItems.
* SellItems.

## חלוקת אחריות בין חברים הצוות:
* Saar Barel - in charge of the game engine files (scripts, animations, all the basic systems - regardless of the plot).
* Almog Reuveni - building maps, creating dialogues, creating tasks (in collaboration with Uriah in order to maintain the sequence of the biblical story).
* Uriah Shamla - Composing the plots of the stories about King David from the Bible to the game (main scenes, accompanying characters, etc.).
* Omar Aden - responsible for game design (game menu, game characters, game items, etc.)






