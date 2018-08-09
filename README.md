 This project is based on NEthereum:
 
 https://github.com/Nethereum/Nethereum/releases/tag/3.0.0-rc1
 
 You can get the necessary DLLs to make the project work here:
 
 https://github.com/Nethereum/Nethereum/releases/download/3.0.0-rc1/unitynet35dlls.zip
 
--------------------------
--------------------------
YOUR ETHEREUM BASE PROJECT
--------------------------
--------------------------

This project is composed with 2 main submodules:

-YourEthereumController: The basic Ethereum controller to call to perform any operation

	Available scenes:
	
		Assets\YourEthereumController\Scenes\BasicManager.unity 
		Assets\YourEthereumController\Scenes\CreateKeys.unity
		Assets\YourEthereumController\Scenes\SignTextData.unity
		Assets\YourEthereumController\Scenes\SignImageData.unity
  
-YourEthereumScreens: A collection of screens that help you to manager your ethereum account and operations

	Available scenes:
	
		Assets\YourEthereumScreens\Scenes\YourEhereumWallet.unity

Before start, to make it work remember to get your own keys and set up the class: EthereumController.cs

		public const string ETHERSCAN_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX";   // Get your own key at: https://etherscan.io
        public const string INFURA_API_KEY = "YYYYYYYYYYYYYYYYY";   // Get your own key at: https://infura.io/

--------------------------
-------------------------
YOUR ETHEREUM CONTROLLER
-------------------------
--------------------------

Thanks to this plugin you will be able to include Ethereum cryptocurreny and Blockchain signning authentication
in your games and applications.

The video tutorials make reference to Bitcoin but the methodology works almost the same way with Ethereum.

TUTORIAL BASIC OPERATIONS
--------------------------

  1. SET UP THE RUNTIME:

	First of all, we make sure that the Scripting Runtime Version: ".NET 4.x Equivalent" in order for the Nethereum DLLs to work.
 
  2. INSTALLATION OF NEthereum DLL:
 
	On Visual Studio open the NuGet console and run the command line: "Install-Package Nethereum.Portable"
	
	After installing the DLL you will be able to run the code without problems.

  3. GET YOUR OWN KEYS AND SET UP AT AT CLASS: EthereumController.cs

		public const string ETHERSCAN_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX";   // Get your own key at: https://etherscan.io
        public const string INFURA_API_KEY = "YYYYYYYYYYYYYYYYY";   // Get your own key at: https://infura.io/
		
  4. RUN THE SCENE:

		Assets\YourEthereumController\Scenes\BasicManager.unity 
		
	 and you will be able to perform operations with Ethereum. 
	 
	 Follow the instructions on the video tutorial:
	 
		https://youtu.be/5Nj8FKymhjc
		
  5. Run the scene CreateKeys.unity to create new wallets
  
	 Follow the instructions on the last part of the video tutorial (time 2:32):
	 
		https://youtu.be/5Nj8FKymhjc?t=2m32s
		
  6. Run the scenes SignTextData.unity and SignImageData.unity to sign data and document using your keys
  
	 Follow the instructions on the video tutorial:
	 
		https://youtu.be/5Nj8FKymhjc?t=3m16s

--------------------------
--------------------------
YOUR ETHEREUM SCREENS
--------------------------
--------------------------

Thanks to this plugin you will be able to include Ethereum cryptocurreny and Blockchain signning authentication
in your games and applications.

The video tutorials make reference to Bitcoin but the methodology works almost the same way with Ethereum.

TUTORIAL INTEGRATE ETHEREUM IN YOUR APP/GAME
-----------------------------------------------

 1. SET UP THE RUNTIME:

	First of all, we make sure that the Scripting Runtime Version: ".NET 4.x Equivalent" in order for the NEthereum DLL to work.

 2. INSTALLATION OF NEthereum DLL:
 
	On Visual Studio open the NuGet console and run the command line: "Install-Package Nethereum.Portable"
	
	After installing the DLL you will be able to run the code without problems.

 3. GET YOUR OWN KEYS AND SET UP AT AT CLASS: EthereumController.cs

		public const string ETHERSCAN_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX";   // Get your own key at: https://etherscan.io
        public const string INFURA_API_KEY = "YYYYYYYYYYYYYYYYY";   // Get your own key at: https://infura.io/
	
 4. RUN THE SCENE:
 
		Assets\YourEthereumScreens\Scenes\YourEhereumWallet.unity
		
 5. OR FOLLOW THE INSTRUCTIONS OF THIS VIDEO TUTORIAL TO INTEGRATE ETHEREUM IN YOUR APP/GAME:
 
	https://youtu.be/LLz3_BFcWic

 6. CREATE NEW PROJECT AND IMPORT YourEthereumController PACKAGE
 
 7. DRAG THE PREFABS TO THE SCENE:
 
		Assets\YourEthereumController\Screens\Resources\Prefabs\ScreenEthereumController.prefab
		Assets\YourEthereumController\Screens\Resources\Prefabs\LanguageController.prefab
		
 8. ADD UI\EventSystem TO THE SCENE.
 
 9. CREATE A NEW GAMEOBJECT AND ATTACH IT A SCRIPT CALLED Example.cs
 
 10. OPEN THE SCRIPT AND ADD THE CODE INSTRUCTION THAT WILL ALLOW YOU TO OPEN THE WALLET SCREEN.
 
 11. FOLLOW THE INSTRUCTIONS IN THE VIDEO TO ADD ETHEREUM FUNDS
 
 12. MODIFY THE SCRIPT AND USE THE INSTRUCTION TO OPEN THE SCREEN THAT WILL ALLOW YOU TO SEND CASH
 
 13. AFTER PERFORMING THE OPERATION YOU CAN CHECK IN TRANSACTIONS' SCREEN THAT THE OPERATION HAS BEEN DONE.

 
