
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
[![Watch the video](https://drive.google.com/file/d/12Pi0d2hQ7LbXxHek8V5uJ9MTk4hl0MuR/view?usp=sharing)
[![portfolio](https://img.shields.io/badge/Report_file-Word_doc-blue?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAA59JREFUWEftl1lME1EUhv8pW9WUgiDaFkTR0ERQDEJMAKEVHzT4osYggiAuYIxb9MHEFxOjJvrmiktcCYgaNTEqLmxtWST6oAmBB9wQCghY1GgU0F5z752ORaU1MzH6QF9m5s4593znP+fe2xHg5WcucRBvNgredwmenOeX9hcTQnIUBPDq6hHAXPKuDHBmep1FgcEowP+tQPLxlmvEiaWeSiwIgH/QRNldIEwvtG0kgnCMiIuN/LgBGyIAHyLild4S/s75GUGh/dBMnY2A4EmyIIRphbXi/JzgZ5ARg1MwAN+6qxFoTIWvJkwewNQCG89PiswndpG4xn8LRgBnby0Co5MUAjCZf6+AJLeYsfszRXX21ikDmLLeyiKbYoJxbmsspqyzSmVoO5PKZJ2cb6EdwKRpP29iY+F51cyO9FEFkuUrELnOwuYWBAEvT8/D/qsvcKK8nQV7fS6NBdtysgXX69+w+44LJlibHMg68ISDOqgCSgDWWqSS04zff/qKmZvrhgF09w8gYVsDK5P9ohlpOxvRav/IV4OjAVqjEoA1FmkVtJ3lGUfkW2A0jEXF3kQ8fvYeCdO1MORWY15MMMp2zoY+u5IHp57vHioDiMivkVZB0cYYLE6cgPDVNXh6JBmaMT5I3/UItoNzoc+pRPmeRMRFBUKX9YAHJwTCh0ZojSnye4ABsP4i0Kh90VyUgvC8Glbry7ZubD/VDHvxfMwosKD5VBorkXFtFeDkAF86LAjQxUM1JkTePhCeV+227Ak6LphReLQJJzfFsqxpkM6SBahtciAldjz2lbbiyI3nogLAQKdVGYCBAogK0CttMvvbLzCEqKFfWcECvS5Oh5+vimU4cfldvkmJPTDYZUOAbo58BQy5LgX4OrcXm9n89JChtaYPplmhuLQrngMsK+fngliCwe5aBOgVAOhXVbFTxtVUCdFa3NydiDf9A4jbUMMCqQSg68pCBhC25LZkS/2GeuqVAeiyK3kBxIw4iHjiiVL/ABS3bApM7UEw1NsAtRIFdCsrhingAnApQrudNQm9imDuig31NUBtSJDfA5NW3HcD+DVD98ASlFQy4GufFeqIJAUAmfcWESe5M3zyPyuB83MPBrsq4BcaB5W/Vt4+4MlLHZVRB0KSRrIR/MZBpQ6Bzzj93wHQxO+4BUIyvKXmExjpzWTE9x7/FQebDpcRQv7dh8koQFDqofMQkCe7wH/g6LEHqH9Q2qG/+Xn+6jtHFUHO+f5+igAAAABJRU5ErkJggg==)](https://docs.google.com/document/d/1kyCxt3N62EXxhKRtoVnn4KER5whWo7Ssbpqk1AVCXdQ/edit?tab=t.0#heading=h.gjdgxs)

