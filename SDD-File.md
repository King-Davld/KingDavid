# King David - Software Design Description



## Programming languages and software tools:
* Programming languages: C#.
* IDE: Visual Studio.
* GameEngine: Unity.

## Code structure:
### The code is divided into 8 main classes:
### 1. [Battle System](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/Battle%20System) - The fighting process in the game.
#### Main Methods:
* StartBattle.
* BattleNotification.
* AttackEffect.
* BattleCharacters.
### 2. [DialogManager](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/DialogManager) - The process of dialogue with the other NPC in the game.
#### Main Methods:
* DialogController.
* DialogHandler.
* StartQuestAfterDialog.
### 3. [Items](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/Items) - The process of creating / obtaining / using Items in the game.
#### Main Methods:
* Inventory.
* ItemButton.
* ItemsAssets.
* ItemsManager.
### 4. [LevelManager](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/LevelManager) - The process of switching between scenes + building the maps in the game(TileMap).
#### Main Methods:
* ExitArea.
* ArrivalArea.
* TileMaps.
* MapEdges.
### 5. [Managers](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/Managers) - The core processes of the game (sound, camera, main menu).
#### Main Methods:
* AudioManager.
* CamController.
* GameManager.
* MenuManager.
### 6. [Player](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/Player) - All processes related to the player (movement, stats, battles, items).
#### Main Methods:
* PlayerMovement.
* PlayerAnimation.
* PlayerStats.
### 7. [Quests](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/Quests) -  The process of accepting / completing quests in the game.
#### Main Methods:
* QuestManager.
* QuestObject.
* QuestZone.
### 8. [Shop](https://github.com/LeveI-Up/KingDavid/tree/main/Assets/Scripts/Shop) - The process of buying / selling items in the game.
#### Main Methods:
* ShopKeeper.
* ShopManager.
* BuyItems.
* SellItems.

## Responsibilities among the game team members:
* [Saar Barel](https://github.com/saar95) - in charge of the game engine files (scripts, animations, all the basic systems - regardless of the plot).
* [Almog Reuveny](https://github.com/almogre02) - building maps, creating dialogues, creating tasks (in collaboration with Uriah in order to maintain the sequence of the biblical story).
* [Uriya Shemla](https://github.com/uriyashemla) - Composing the plots of the stories about King David from the Bible to the game (main scenes, accompanying characters, etc.).
* [Omer Aden](https://github.com/omer6546) - responsible for game design (game menu, game characters, game items, etc.)





