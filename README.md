---- whoever uses this software, uses it at their own risk ---

This software bot places automatically trades from Vader's discord channels.
Trades are taken in realtime without any delay and always using MARKET orders with alerted size x multiplicator.

!! PLEASE DISABLE the possibility for selling/writing options in IBKR account settings, because it can happen unintentional in unfavorable circumstances !!! 

Following must be fullfilled:
1. .NET8 framework on Windows 10/11 desktop installed
2. IBKR Workstation must run locally on the PC, IBKR user must be logged in. 
  !! PLEASE DISABLE the possibility for selling options in IBKR account settings, because it can happen unintentional in unfavorable circumstances !!! 
  
3. Follow the steps in IBKR Trader Workstation to enable API access:

    A. Go to File -> Global Configuration -> API -> Settings
    - Check the "Enable ActiveX and Socket Clients" box
    - Uncheck the "Read-Only API" box
    - Check the "Allow connections from localhost only" box

    B. Go to File -> Global Configuration -> Preset -> Options:
    - Check the "Timing / Allow order to be activated, triggered or filled outside of regular trading hours"

4. Logging into Discord using user token is officially not supported and can lead to user deactivation or ban - you do it on your own risk.

5. Please restart this application at least 1 time weekly - I personally suggest to restart it daily.
   You can use <add key="StartDirectly" value="True" /> in SimpleBot.dll.config file to start it from command line or scheduler without clicking start-button.

-----------
The software package provided in this repository is provided "as is" and without warranty of any kind, express or implied,
including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. 
In no event shall the author or contributors be liable for any claim, damages, or other liability,
whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the softwarepackage or the use or other dealings in the software package.

Please use this software package at your own risk. 
The author and contributors disclaim all liability and responsibility for any errors or issues that may arise from its use. 
It is your responsibility to test and validate the code and package for your particular use case.

---- whoever uses this software, uses it at their own risk ---
