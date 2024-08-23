# HamsterKombatBot
🖱️ clicker for [https://t.me/hamster_kombaT_bot](https://t.me/hamster_kombaT_bot/start?startapp=kentId558455838)

## Recommendation before use
# 🔥🔥 Use PYTHON 3.10 🔥🔥

## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto APPLY COMBO                                               |     ✅     |
| Auto APPLY PROMO CODES                                         |     ✅     |
| Auto APPLY DAILY CIPHER                                        |     ✅     |
| Auto APPLY DAILY REWARD                                        |     ✅     |
| Auto APPLY DAILY ENERGY                                        |     ✅     |
| Auto APPLY DAILY MINI GAME                                     |     ✅     |
| USE RANDOM MINI GAME KEY                                       |     ✅     |
| AUTO COMPLETE TASKS                                            |     ✅     |
| Random USE TAPS                                                |     ✅     |
| Support tdata / pyrogram .session / telethon .session          |     ✅     |


## [Settings](https://github.com/sizifart/HamsterKombatBot/.env-example)
| Setting                      | Description                                                                              |
|------------------------------|------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**        | Platform data from which to launch a Telegram session _(stock - Android)_                |
| **MIN_AVAILABLE_ENERGY**     | Minimum amount of available energy, upon reaching which there will be a delay _(eg 100)_ |
| **SLEEP_BY_MIN_ENERGY**      | Delay when reaching minimum energy in seconds _(eg [1800,2400])_                         |
| **AUTO_UPGRADE**             | Whether to upgrade the passive earn _(True / False)_                                     |
| **MAX_LEVEL**                | Maximum upgrade level _(eg 20)_                                                          |
| **MAX_PRICE**                | Maximum upgrade price _(eg 50000000)_                                                    |
| **BALANCE_TO_SAVE**          | Balance limit that the bot "won't touch" _(eg 1000000)_                                  |
| **UPGRADES_COUNT**           | The count of cards that the bot will upgrade in 1 lap _(eg 10)_                          |
| **MAX_COMBO_PRICE**          | Maximum purchase price for buying combo cards with an available balance _(eg 10000000)_  |
| **APPLY_COMBO**              | Whether to apply the buying and claiming combo cards _(True / False)_                    |
| **APPLY_PROMO_CODES**        | Whether to apply the activation promo codes _(True / False)_                             |
| **APPLY_DAILY_CIPHER**       | Whether to apply the claiming daily cipher _(True / False)_                              |
| **APPLY_DAILY_REWARD**       | Whether to apply the claiming daily reward _(True / False)_                              |
| **APPLY_DAILY_ENERGY**       | Whether to apply the activation daily energy boost _(True / False)_                      |
| **APPLY_DAILY_MINI_GAME**    | Whether to apply the activation mini game _(True / False)_                               |
| **USE_RANDOM_MINI_GAME_KEY** | Whether to use random key for mini game cipher _(True / False)_                          |
| **AUTO_COMPLETE_TASKS**      | Whether to complete tasks _(True / False)_                                               |
| **USE_TAPS**                 | Whether to use taps _(True / False)_                                                     |
| **RANDOM_TAPS_COUNT**        | Random number of taps _(eg [50,200])_                                                    |
| **SLEEP_BETWEEN_TAP**        | Random delay between taps in seconds _(eg [10,25])_                                      |
| **USE_RANDOM_DELAY_IN_RUN**  | Использовать ли рандомную задержку при запуске _(True / False)_                          |
| **RANDOM_DELAY_IN_RUN**      | Random delay in run _(eg [0,15])_                                                        |
| **USE_RANDOM_USERAGENT**     | Whether to use random User Agent every time to start _(True / False)_                    |

## 📕 Profiles
Possible to create a profile with unique data for each session:
```json
{
  "session1": {
    "proxy": "socks5://yGow3a:uBro3wL@58.195.21.83:9715",
    "headers": {"...": "..."},
    "fingerprint": {"...": "..."}
  },
  "session2": {
    "proxy": "socks5://yGow3a:uBro3wL@58.195.21.83:9715",
    "headers": {"...": "..."},
    "fingerprint": {"...": "..."}
  },
  "...": {}
}
```
> ❕ **Note**:  `session1` и `session2` - are examples of session names.


## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10**
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Auto Install/Run
- Click on Install.bat to automatically install the required dependencies 
- Then click on START.bat to run the project

## Menual Install/Run
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Please edit the name file .env-example to .env and add your API_ID and API_HASH:
   
## Usage
1. Run the bot:
   ```bash
   python main.py
   ```
 
# Telegram Channel

✅ Channel for information and training on Telegram airdrop bots 🔷 Follow us on Telegram : [SIZIFAIRDROP](https://t.me/sizifairdrop)
   
# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)
