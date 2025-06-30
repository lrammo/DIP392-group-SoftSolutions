
# Inventory Tool

a simple inventory tool for managing 3D assets within Unreal 
Engine 5.5. The tool should allow users to: 
- Store 3D assets in an inventory system. 
- Pick up 3D assets from the environment. 
- Discard 3D assets when no longer needed. 
The solution will be implemented in a playable first-person level inside Unreal Engine 5.5. 
The tool can be developed using either: 
- Unreal Engine’s Blueprints (visual scripting language), or 
- C++ for a more optimized approach. 
The 3D assets will be sourced from Quixel Megascans, imported into Unreal Engine, and 
configured with appropriate shaders before integrating them into the inventory system. 

To download Unreal Engine 5.5.1, follow these steps:

 1. Go to the Epic Games Website
    - Open your web browser and visit: https://www.unrealengine.com
      
 2.Sign In or Create an Epic Games Account
    - Click ‘Sign In’ in the top-right corner.
    - If you don’t have an account, click ‘Sign Up’ and create one (it’s free).

 3. Download the Epic Games Launcher
    - After signing in, hover over your profile icon and click ‘Download’.
    - Install the Epic Games Launcher by running the downloaded file.

 4. Open the Epic Games Launcher & Sign In
    - Launch the app and log in with your Epic account.
    
 5. Find Unreal Engine in the Launcher
    - Click on the ‘Unreal Engine’ tab in the left sidebar.
    - Then, go to the ‘Library’ section.

 6. Install Unreal Engine 5.5.1
    - Click the ‘+’ (plus) icon next to ‘Engine Versions’.
    - From the dropdown, select 5.5.1 (if it doesn’t appear, click ‘More Versions…’ and find it).
    - Choose your installation location and click ‘Install’.

 7. Wait for the Download & Installation
    - The download size is large (around 30-50GB), so it may take a while depending on your internet speed.

 8. Launch Unreal Engine 5.5.1
    - Once installed, click ‘Launch’ to open Unreal Engine!

  After the installation you have to download the files from our github repositry. Once everything is installed
  open the folder "src" and search for a file named "InventoryTool.uproject". Double click on the file and 
  the project should launch. After that press F5 to start the program and click on the window of the game so you
  can interact. Try to get close to an item and press the button "E" on your keyboard to store the item in your
  inventory. If you want to check your inventory press the keybind "I". Once you open your inventory your mouse cursor 
  should appear on the screen. You can discard an item by hovering the image of the item with your cursor and click on the image.
  To close your inventory simply press the keybind "I" again. To exit the game press "ESC".

  If you want to take a look at how we did the visual scripting search for a bar called "Content drawer" in the left bottom corner of your screen.
  Click on the bar then open the "All" folder and enter the folder "Content". After that open the folder named "FirstPerson" and then go to "Blueprints".
  Double click on "BP_InventoryComponent" and a new window will appear. This window will show you the blueprint of the class. You can do the same for
  "All->Content->Inventory->BP_Item" and "All->Content->FirstPerson->Blueprints->BP_FirstPersonCharacter".

Team roles:
- Lorin Rammo: Project Maneger
- Héctor Hernández Sánchez: Designer
- Nazarkevych Andrii: Designer
- Sorin Rammo: Tester
- Yaseen Almahayshi: Developer
- Georgi Beev: Developer

  

## 🔗 Links

