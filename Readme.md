# Telegram-Auto-Filter-Bot

__Just Sent Any Text As Query It Will Search For All Connected Chat's Files In Its MongoDB And Reply You With The Message Link As A Button__

---

### Follow [Tharuk Renuja](https://github.com/TR-TECH-GUIDE)
#### PR's Are Very Welcome

---

## Usage

<details>
  <summary><b>How To Use Bot?</b></summary>
<br/>

* -> Add me to any group and make me admin<br>
* -> Add me to your channel as admin with full previlages

</details>

<details>
  <summary><b>Bot Commands (Works Only In Groups) :</b></summary>
<br/>

  * -> `/add chat_id`<br>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
OR
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- To establish a connection of group with a channel (Bot should be admin with full previlages in both group and channel)<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`/add @Username`


  * -> `/del chat_id`<br>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
OR 
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- To delete a group's coneection with a channel (Use disable option from settigns pannel for disconnecting temporarily instead of deleteing)<br>
    &nbsp;&nbsp;&nbsp;&nbsp; `/del @Username`


  * -> `/delall`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - To delete all connections of a group and deletes all its file from DB
  
  * -> `/settings`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -  To disaply a Settings Pannel Instance which can be used to tweek bot's settings accordingly

    * -> Channel - Button will show you all the connected chats with the group along with there index buttons correspnding to there order for furthur controls...

    * -> Filter Types - Button will show you the 3 filter types available in bot... Pressing each buttons will either enable or disable them and this will take into action as soon as you use them...without the need of a restart....

    * -> Configure - Button will help you to change no. of pages/ buttons per page/ total result without acutally editing the repo... Also it provide option to Enable/Disable  showing Invite Link in each results

    * -> Status - Button will show the stats of your current group

</details>

---

## Deploy
You can deploy this bot anywhere.

<details><summary><b>Deploy To Heroku</b></summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/TR-TECH-GUIDE/Telegram-Auto-Filter-Bot/tree/main">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary><b>Deploy To VPS</b></summary>
<p>
<pre>
git clone https://github.com/TR-TECH-GUIDE/Telegram-Auto-Filter-Bot
cd Telegram-Auto-Filter-Bot
pip3 install -r requirements.txt
# Change The Vars Of bot/__init__.py File Accordingly
python3 -m bot
</pre>
</p>
</details>

---

## Support

Join Our [Telegram Group](https://www.telegram.me/trtechguide) For Support/Assistance And Our [Channel](https://www.telegram.me/SLBotsOfficial) For Updates.   
   
Report Bugs There..   
Do Fork And Star The Repository If You Liked It.

---

## Disclaimer

[![GNU Affero General Public License v3.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL v3.0.](https://github.com/TR-TECH-GUIDE/Adv-Auto-Filter-Bot-V2/blob/main/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.

---

## Credits
 - [Fayas](https://github.com/FayasNoushad)
 - [Me](https://github.com/TR-TECH-GUIDE)
