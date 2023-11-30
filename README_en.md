# FUT Trade Buddy (FTB) installation guide

This installation guide will help you setting up our FUT Trade Buddy Chrome Extension and will guide you through all settings FTB has to offer. Please exactly follow this guide to make sure everything is setup correctly before you start using FTB.
If you need any kind of support, please feel free to open a support ticket on our Discord server: https://discord.gg/hFfmPxTn96

## Index

- [Add FUT Trade Buddy to your chrome browser](#add-fut-trade-buddy-to-your-chrome-browser)
- [Registering your license](#registering-your-license)
- [FTB Settings](#settings)
- [Example 1 - General filter search](#example-1---general-filter-search)
- [Example 2 - Specific player search](#example-2---specific-player-search)
- [Example 3 - Consumable search](#example-3---consumable-search)
- [Example 4 - Autobidder](#example-4---autobidder)

## Add FUT Trade Buddy to your chrome browser

<font size="2"> [Back to Index](#index)
</font>

In Google Chrome Store search for our extension:

![image](https://github.com/exec85/FTB/assets/58392827/a090e4ef-9852-44b3-9959-0dd6ef119b3c)

Click on "Add" to add FTB to your Google Chrome browser:

![image](https://github.com/exec85/FTB/assets/58392827/462d08e0-a5c2-4fbd-a012-5b7b0a611e0a)

Click on the small puzzle icon in the upper right corner in Google Chrome and pin it:

![image](https://github.com/exec85/FTB/assets/58392827/b3b0be63-da86-4742-8c8c-0d9200f509f8)

It should look like this:

![image](https://github.com/exec85/FTB/assets/58392827/98249a19-138b-482b-9c67-000972ef8bd6)

## Registering your license

<font size="2"> [Back to Index](#index)
</font>

Follow the steps you see when you click on the FTB Google Chrome extension button

![image](https://github.com/exec85/FTB/assets/58392827/f368a160-977e-4744-a7af-bd68386cb0cf)

In case you do not see HWID, Extension ID, IP and Email please double check if you are logged in with an email in your Google Chrome browser.
Also make sure that "Synchronization" is active and then restart Chrome once:

![image](https://github.com/exec85/FTB/assets/58392827/e84ac3d0-6096-4c05-9583-2b834366e5f1)

After your license has been activated by exec85 or ophidias you are ready to use FUT Trade Buddy.

## Settings:

<font size="2"> [Back to Index](#index)
</font>

### The WebApp MUST be set to English language!

### Coin Threshold

![image](https://github.com/exec85/FTB/assets/58392827/70c20894-acbc-4e01-9717-236da954642e)

Enter the minimum number of coins you want to keep on your account while trading.
For example you have 1000 coins on your account, and you want FTB to stop if your coins would drop below 800 coins. Then you enter 800 in the "Coin Threshold" input field.

### Auto Buyer

![image](https://github.com/exec85/FTB/assets/58392827/c6976809-11ce-43ad-b1da-0df492a7d0a3)

**Auto-calculate selling price:**

Checking this box will cause FTB to do a price calculation of the item you bought and put in on the market for the best price. This overrides the value in the Sell Price input field, so it's either auto-calculated or fixed price. FTB automatically stops in case you would make loss.

\
**Buy only:**

Checking this box will cause FTB to only buy the item and put it on the transfer list without selling it.

\
**Playername + Rating:**

Used if you want to buy a specific player. Inside the EA Web App copy the player’s name and paste it into the input field "Player Name" on the FTB "Settings" tab.
The rating must be the general rating of that player which you also find inside the Web App when you look up the correct name:

![image](https://github.com/exec85/FTB/assets/58392827/c6b40dc7-c3ee-40c5-9294-38dc3be88d13)

\
**Sell Price:**

If you want to set your own custom selling price you can enter it here. FTB will list the bought items for that exact price on the transfer market.

\
**Speed:**

You can choose between the following speed options (enter 1,2 or 3):

1 = slow, 2 = normal, 3 = fast

\
**Search Loops:**

Enter a number for how many searches the tool should perform before it stops or goes into pause.

\
**Pause:**

Enter a number (minutes) how long FTB should pause after the Search Loops are done. FTB will restart with your routine after the pause is over. If you leave this field empty or set it to 0, then FTB will stop after all search loops are done.

### Autobidder

![image](https://github.com/exec85/FTB/assets/58392827/01540ea3-f616-4fb1-808e-2d37596e04b1)

**Bid Price:**

Enter the price you want to bid for om items.

\
**Pages to scan:**

Add a number indicating how many search result pages the autbidder should go through. It will stop when the remaining auction time of the card is above 1 hour.

### Transfer List

![image](https://github.com/exec85/FTB/assets/147206214/e1d7e5a9-2e74-44fc-8681-d49e9b05d387)


**Include transfer list clearing and relisting in Auto-Buyer routine?**

If you activate this check box FTB will randomly leave the search window, goes to the transfer list window and clears all sold items as well as relists all un-sold items. After that it goes back to the search window and restarts your routine. This can be useful if you want to make sure you transfer list is not getting full while running long sessions.

\
**Automatically calculate re-listing price**

If this is checked FTB will do a price calculation for each un-sold item before it gets relisted to make sure it has the best-selling price at that time. Please note that this will not check if you make a loss compared to your original buying price. So, take care and think about if you want to set this box.

\
**Do not delete sold items**

If this is checked FTB will not clear sold items so you can check the price they were sold for and manually clear the list.

### Notifications

![image](https://github.com/exec85/FTB/assets/58392827/63f8bdcf-c408-4e39-bee2-029ac5dc3bb4)

**Telegram**

If you want to receive notifications via Telegram regarding bought items, profits, captcha warning and so on, then enter your Telegram Chat ID here. To get this ID please add the "userinfobot" (@userinfobot) and in the chat with that userinfobot type "/start" like in the screenshot below. It answers with your personal Telegram Chat ID.

![image](https://github.com/exec85/FTB/assets/58392827/4bdcb5e9-413a-4492-b838-94ed8431a380)

![image](https://github.com/exec85/FTB/assets/58392827/7c69913f-1b07-4cdd-897e-68e031ce0c5c)

After that copy + paste your Chat ID into the Telegram input field in the FTB notifications settings. Please now add our Telegram FTB BOT and send it any message to activate the chat. You find our FTB Telegram bot by @ftbtelegram_bot

![image](https://github.com/exec85/FTB/assets/58392827/a9e95814-3a2f-4f49-ba3a-c8bacd32b275)

\
**Discord**

If you want to receive notifications via Discord regarding bought items, profits, captcha warning and so on, then enter your Discord User ID here. To find your Discord User ID you must activate the developer mode in Discord.
Open the Discord settings by clicking the gear icon at the bottom left of your profile:

![image](https://github.com/exec85/FTB/assets/58392827/22043857-f60d-4f14-a0db-daf2d03526b9)

Here you will find the option "Advanced" on the left side. Click on it and activate the developer mode on the right side:

![image](https://github.com/exec85/FTB/assets/58392827/a0282423-4e7b-4b9e-8bb2-44ea97dfc6f1)

Afterwards you can click on your name and then click on "Copy User ID":

![image](https://github.com/exec85/FTB/assets/58392827/5ae35a8a-1a4d-4ab1-86bc-82eeb0805a69)

After that copy + paste your Discord User ID into the Discord input field in the FTB notifications settings. Please now start a chat with our "FTB BOT" on Discord to receive all notifications:

![image](https://github.com/exec85/FTB/assets/58392827/e2198232-ff65-4f3d-b175-2f54cb4cfa0a)

## Example 1 - General filter search

<font size="2"> [Back to Index](#index)
</font>

![image](https://github.com/exec85/FTB/assets/58392827/db1b53f6-7ff5-4a53-bf9c-bc80fca58ce1)

In this example I want to search for all Gold - Rare players in the Premier League that have the nationality "Brazil" and play on position "Attackers". I only want to buy players with a max. price of 700 coin so I have put that also in the filter.

This is an example of a gerneral search filter which you can adapt to all kind of filters you prefer. Always make sure that you check the max. buy price before you enter a value there.

In the FTB settings you have several options. I have prepared one set of settings that I recommend using for a normal session of 4-6 hours.

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
