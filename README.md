# DeltaQuick Save Manager

## Tutorial on how to use the DeltaQuick Save Manager

> **Disclaimer:**  
> This repository does **not** include, host, or distribute any copyrighted material.  
> All instructions provided are for **educational purposes only**.  
> Users are solely responsible for obtaining and using their own legally acquired game files.

---

## Requirements
- [DeltaQuick](https://play.google.com/store/apps/details?id=com.bookerpuzzle.deltaquick&pcampaignid=web_share)
- [DELTARUNE – Windows (Steam version)](https://store.steampowered.com/app/1671210/DELTARUNE/)
- Android device running **Android 7.0 or higher**

---

## Loading Files

- When you are on the main screen of the Save Manager, or inside any folder (as shown in the image below), tap the **“Load Files”** button located at the bottom of the screen.

![Preview](images/preview.png)

- A system file picker will open. Simply select the files you want to load.
- If the selected files already exist in the app’s storage, they will be **automatically replaced**.

![Preview](images/preview.png)

---

## Extracting Files

- To extract files to internal storage, **long-press** a file to enter selection mode.
- You can then tap additional files to select multiple items, as shown in the image below.

![Preview](images/preview.png)

- Once files are selected, the bottom bar will change and display the following buttons:
  - **Extract (X)**
  - **Cancel**
  - **Delete**

![Preview](images/preview.png)

- To extract the selected file(s), tap **Extract (X)**.  
  A dialog will appear asking you to choose the destination folder where the files will be saved.
- To exit selection mode, tap **Cancel**.
- To permanently remove the selected file(s), tap **Delete**.

---

## Only for Modders

>  **This section is intended for experienced users only.**

- To modify the game, you must first extract the **`game.droid`** file.
- The location of this file depends on what you want to modify:
  - From the main screen (global changes)
  - Or from a specific chapter folder

- After extracting `game.droid`, transfer it to your PC and open it using **UndertaleModTool** to apply your modifications.

- To load the modified file back into DeltaQuick:
  1. Open DeltaQuick
  2. Navigate to the **correct folder**
  3. Tap **Load Files**
  4. Select the modified `game.droid`

>   **IMPORTANT:**  
> Before loading a `game.droid` file, make sure you are inside the correct directory.  
> For example, if you are modifying **Chapter 4**, you must:
> - Enter the `CHAPTER4_WINDOWS` folder
> - Extract `game.droid` from that folder
> - Replace **only** the `game.droid` located in that same directory

Loading the file into the wrong folder may result in crashes or unexpected behavior.
