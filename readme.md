![](https://i.yapx.ru/RTuEU.jpg)

___In this guide, we wrote how to set up a bot to track the state of the nodes of the cosmos ecosystem___

To install, follow a few simple steps:

1. Create a bot, get an api token and a telegram chat id, you can read how to do it at the link - [(ENG)](https://sean-bradley.medium.com/get-telegram-chat-id-80b575520659 "") [(RU)](https://nastroyvse.ru/programs/review/telegram-id-kak-uznat-zachem-nuzhno.html "")  
2. Run the script, select the installation stage, which will ask you to enter the API_token and telegram chat id
```html
curl -s https://raw.githubusercontent.com/StakeTake/scriptcosmos/main/telegram_bot/start > start.sh && chmod +x start.sh && ./start.sh
```
3. Select the "Start bot" item and enter the following data in the line that appears, you also need to leave the next line empty, as in the photo.
```html
*/1 * * * *  /bin/bash $HOME/alerts/alerts.sh
```
![](https://yapx.ru/v/Ri8JO.jpg)
