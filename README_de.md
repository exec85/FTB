# FUT Trade Buddy (FTB) installation guide

Diese Installationsanleitung hilft dir, unsere FUT Trade Buddy Chrome Extension einzurichten und führt dich durch alle Einstellungen, die FTB zu bieten hat. Bitte folge dieser Anleitung genau, um sicherzustellen, dass alles korrekt eingerichtet ist, bevor du FTB benutzt. Wenn du irgendeine Art von Unterstützung benötigst, kannst du gerne ein Support-Ticket auf unserem Discord-Server hier öffnen: https://discord.gg/hFfmPxTn96

## Index

- [Add FUT Trade Buddy to your chrome browser](#add-fut-trade-buddy-to-your-chrome-browser)
- [Registering your license](#registering-your-license)
- [FTB Settings](#settings)
- [Example 1 - General filter search](#example-1---general-filter-search)
- [Example 2 - Specific player search](#example-2---specific-player-search)
- [Example 3 - Consumable search](#example-3---consumable-search)
- [Example 4 - Autobidder](#example-4---autobidder)

## FUT Trade Buddy zu deinem Chrome-Browser hinzufügen

<font size="2"> [Back to Index](#index)
</font>

Gehe in den Google Chrome Store und suche nach unserer Chrome-Erweiterung wie folgt:

![image](https://github.com/exec85/FTB/assets/58392827/a090e4ef-9852-44b3-9959-0dd6ef119b3c)

Danach klicke auf "Hinzufügen", um FTB zu deinem Chrome-Browser hinzuzufügen.

![image](https://github.com/exec85/FTB/assets/58392827/462d08e0-a5c2-4fbd-a012-5b7b0a611e0a)

Klicke auf das kleine Puzzlesymbol in der oberen rechten Ecke deines Browsers und pinne es an, damit es immer sichtbar ist:

![image](https://github.com/exec85/FTB/assets/58392827/b3b0be63-da86-4742-8c8c-0d9200f509f8)

Es sollte dann wie folgt aussehen:

![image](https://github.com/exec85/FTB/assets/58392827/98249a19-138b-482b-9c67-000972ef8bd6)

## Registrierung der Lizenz

<font size="2"> [Back to Index](#index)
</font>

Folge den Schritten, die du siehst, wenn du auf die Schaltfläche der FTB-Chrome-Erweiterung klickst:

![image](https://github.com/exec85/FTB/assets/58392827/f368a160-977e-4744-a7af-bd68386cb0cf)

Falls du HWID, Extension ID, IP und Email nicht siehst, überprüfe bitte, ob du mit einer Email in deinem Chrome-Browser eingeloggt bist.
Stelle außerdem sicher, dass die Synchronisierung aktiv ist, wie hier zu sehen:

![image](https://github.com/exec85/FTB/assets/58392827/e84ac3d0-6096-4c05-9583-2b834366e5f1)

Nachdem deine Lizenz von exec85 oder ophidias aktiviert wurde, kannst du FTB verwenden.

## Settings:

<font size="2"> [Back to Index](#index)
</font>

### Münzen Grenze

![image](https://github.com/exec85/FTB/assets/58392827/70c20894-acbc-4e01-9717-236da954642e)

Hier gibst du die Mindestanzahl an Münzen ein, die du während des Handels auf deinem Konto behalten möchtest.
Nehmen wir zum Beispiel an, du hast 1000 Münzen auf deinem Konto und du möchtest, dass der FTB stoppt, wenn deine Münzen unter 800 Münzen fallen würden. Dann gibst du 800 in das Eingabefeld Coin Threshold ein.

### Auto Käufer

![image](https://github.com/exec85/FTB/assets/58392827/c6976809-11ce-43ad-b1da-0df492a7d0a3)

**Auto-calculate selling price:**

Wenn Du dieses Kästchen anklickst, führt FTB eine Preisberechnung für den Artikel durch, den Du gekauft und zum besten Preis auf den Markt gebracht hast. Dadurch wird der Wert im Eingabefeld Verkaufspreis außer Kraft gesetzt. FTB würde auch automatisch stoppen, wenn du einen Verlust machen würdest.

\
**Buy only:**

Wenn du dieses Kästchen anklickst, kauft FTB den Artikel nur und setzt ihn auf die Transferliste, verkauft ihn aber nicht.

\
**Playername + Rating:**

Dies wird verwendet, wenn du einen bestimmten Spieler kaufen möchtest. Kopiere in der EA WebApp den Namen des Spielers und füge ihn in das Eingabefeld Spielername in den FTB-Einstellungen ein.
Das Rating muss das allgemeine Rating des Spielers sein, das du auch in der WebApp findest, wenn du den richtigen Namen nachschlägst (siehe Screenshot unten).

![image](https://github.com/exec85/FTB/assets/58392827/c6b40dc7-c3ee-40c5-9294-38dc3be88d13)

\
**Sell Price:**

Wenn Du Deinen eigenen Verkaufspreis festlegen möchtest, kannst Du ihn hier eingeben. FTB wird dann die gekauften Artikel zu genau diesem Preis verkaufen.

\
**Speed:**

Du kannst zwischen den folgenden Geschwindigkeitsoptionen wählen (gib 1, 2 oder 3 ein):

1 = langsam, 2 = normal, 3 = schnell

\
**Search Loops:**

Gib eine Zahl ein, wie viele Suchvorgänge das Tool durchführen soll, bevor es anhält oder in die Pause geht.

\
**Pause:**

Gib eine Zahl ein, wie viele Suchvorgänge das Tool durchführen soll, bevor es anhält oder in die Warteschleife geht. FTB wird nach der Pause mit deiner Routine neu starten. Wenn du dieses Feld leer lässt oder auf 0 setzt, dann hält FTB an, nachdem alle Suchschleifen beendet sind.o pause.

### Autobidder

![image](https://github.com/exec85/FTB/assets/58392827/01540ea3-f616-4fb1-808e-2d37596e04b1)

**Bid Price:**

Bitte gib den Preis ein, den du für alle Artikel bieten möchtest.

\
**Pages to scan:**

Füge eine Zahl hinzu, die angibt, wie viele Suchergebnisseiten der automatische Bieter durchlaufen soll. Der Vorgang wird abgebrochen, wenn die verbleibende Auktionszeit der Karte mehr als 1 Stunde beträgt.

### Transfer List

![image](https://github.com/exec85/FTB/assets/58392827/6489b24f-aff4-4cb6-bfe3-ac18f0be2dbd)

**Include transfer list clearing and relisting in Auto-Buyer routine?:**

If you activate this check box FTB will randomly leave the search window, goes to the transfer list window and clears all sold items as well as relists all un-sold items. After that it goes back to the search window and restarts your routine. This can be useful if you want to make sure you transfer list is not getting full while running long sessions.

\
**Automatically calculate re-listing price:**

If this is checked FTB will do a price calculation for each un-sold item before it gets relisted to make sure it has the best-selling price at that time. Please note that this will not check if you make a loss compared to your original buying price. So, take care and think about if you want to set this box.

### Notifications

![image](https://github.com/exec85/FTB/assets/58392827/63f8bdcf-c408-4e39-bee2-029ac5dc3bb4)

**Telegram:**

If you want to receive notifications via Telegram regarding bought items, profits, captcha warning and so on, then enter your Telegram Chat ID here. To get this ID please add the "userinfobot" (@userinfobot) and in the chat with that userinfobot type "/start" like in the screenshot below. It answers with your personal Telegram Chat ID.

![image](https://github.com/exec85/FTB/assets/58392827/4bdcb5e9-413a-4492-b838-94ed8431a380)

![image](https://github.com/exec85/FTB/assets/58392827/7c69913f-1b07-4cdd-897e-68e031ce0c5c)

After that copy + paste your Chat ID into the Telegram input field in the FTB notifications settings. Please now add our Telegram FTB BOT and send it any message to activate the chat. You find our FTB Telegram bot with its name @ftbtelegram_bot

![image](https://github.com/exec85/FTB/assets/58392827/a9e95814-3a2f-4f49-ba3a-c8bacd32b275)

\
**Discord:**

If you want to receive notifications via Discord regarding bought items, profits, captcha warning and so on, then enter your Discord User ID here. To find your Discord User ID you must activate the developer mode in Discord.
Open the Discord settings by clicking the gear icon at the bottom left of your profile (see below).

![image](https://github.com/exec85/FTB/assets/58392827/22043857-f60d-4f14-a0db-daf2d03526b9)

Here you will find the option "Advanced" on the left side. Click on it and activate the developer mode on the right side (see below).

![image](https://github.com/exec85/FTB/assets/58392827/a0282423-4e7b-4b9e-8bb2-44ea97dfc6f1)

Afterwards you can click on your name and then click on "Copy User ID" (see below).

![image](https://github.com/exec85/FTB/assets/58392827/5ae35a8a-1a4d-4ab1-86bc-82eeb0805a69)

After that copy + paste your Discord User ID into the Discord input field in the FTB notifications settings. Please now start a chat with our "FTB BOT" on Discord to receive all notifications.

![image](https://github.com/exec85/FTB/assets/58392827/e2198232-ff65-4f3d-b175-2f54cb4cfa0a)

## Example 1 - General filter search

<font size="2"> [Back to Index](#index)
</font>

![image](https://github.com/exec85/FTB/assets/58392827/db1b53f6-7ff5-4a53-bf9c-bc80fca58ce1)

In this example I want to search for all Gold - Rare players in the Premier League that have the nationality "Brazil" and play on position "Attackers". I only want to buy players with a max. price of 700 coin so I have put that also in the filter.

This is an example of a gerneral search filter which you can adapt to all kind of filters you prefer. Always make sure that you check the max. buy price before you enter a value there.

In the FTB settings you have also several options. I have prepared one set of settings that I recommend using for a normal session of 4-6 hours.

![image](https://github.com/exec85/FTB/assets/58392827/8ad15230-e58b-4f76-a8eb-b91d3de85800)

## Example 2 - Specific player search

<font size="2"> [Back to Index](#index)
</font>

![image](https://github.com/exec85/FTB/assets/58392827/180f14ce-f7de-4c3d-9420-dd6db7da781b)

In this example I want to search for a specific player. As explained above in the Settings section, you must copy the player's name and the general rating of the card from the WebApp into the FTB settings. In this Case "Sheraldo Becker" with the rating "78" like this:

![image](https://github.com/exec85/FTB/assets/58392827/28e2ceb4-990f-4b20-8a37-387b322efb7b)

If you want to search for an inform version of the card then you have to choose the right one from the "Rarity" filter option inside the WebApp for example "Team of the Week".
Also, remember to put in the desired max buy price into the WebApp filter.

## Example 3 - Consumable search

<font size="2"> [Back to Index](#index)
</font>

In this example I want to search for the consumable "SHADOW". So inside the webapp I choose the desired filter and I make my settings in FTB, for example like this:

![image](https://github.com/exec85/FTB/assets/58392827/9b6804a3-8166-4bd3-bf21-9a1c38e0136d)

In this case I do not want to to let FTB calculate the selling price, so instead I put in a Sell Price into the FTB settings like this:

![image](https://github.com/exec85/FTB/assets/58392827/4bc37fff-d1b4-416c-9b38-b8bd16b01738)

Of course, if you want, you can also here let FTB calculate the best price.
In general we recommend to use the "Auto-calculate selling price" feature because it will notice when you would make a loss with your filters and stops immediately. So it also protects your coins.

## Example 4 - Autobidder

<font size="2"> [Back to Index](#index)
</font>

To set up the Autobidder in the FTB settings simply enter the max. bid price you want to bid on a card and enter the amount of pages FTB should scan. Remember, FTB will stop if the remaining duration of an auction is > 1 Hour.

![image](https://github.com/exec85/FTB/assets/58392827/0033a0d9-c120-4dc7-9a57-e1bde57f5ecd)

Inside the WebApp simply choose your filter.
ATTENTION: If you want to search for a specific player then you have to add the player directly in the WebApp this time.
You not have to put any price values inside the WebApp for the Autobidder, but you can if you want to set a specific price range. This also works for all consumables the same way.

![image](https://github.com/exec85/FTB/assets/58392827/0ae4cf07-0f89-4035-a7c2-e15a63b9019d)
