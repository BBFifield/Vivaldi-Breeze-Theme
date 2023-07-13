# Vivaldi-Breeze-Theme

## Screenshots:
<img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/fe01e88e7822aa1d6d499cf999ff527d75640185/Vivaldi%20Breeze%20Screenshots/speed_dial.png">
<img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/fe01e88e7822aa1d6d499cf999ff527d75640185/Vivaldi%20Breeze%20Screenshots/settings_page.png">
<img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/fe01e88e7822aa1d6d499cf999ff527d75640185/Vivaldi%20Breeze%20Screenshots/bookmarks_popup.png" width="300px">

## About:
* This theme was created so KDE users could experience having an up-to-date chromium-based web browser that looks and feels tightly integrated within the plasma shell when using the default breeze-dark theme in KDE.
* The theme was created to closely resemble Breeze-dark from KDE 5.27.6 and tested against Vivaldi 6.1.3035.100.

* To enable this theme, go to vivaldi://experiments/ and check "Allow CSS Modifications". Then head to the Appearance section in Vivaldi settings and choose the root folder of this theme under "CUSTOM UI MODIFICATIONS".

* To allow Kwin to draw window shadows when not using the native window controls and border, perform the following steps:

  1. Set a Kwin window rule like so:
     Property Name | Input Option | User Input 
     | :--- | ---: | :---:
     Window Class  | Exact Match | Vivaldi Stable
     No titlebar and frame  | Force | No
     
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window_rules.png" width="450px">
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window_rules2.png" width="450px">
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window_rules3.png" width="450px">
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window_rules4.png" width="450px">
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window_rules5.png" width="450px">
  2. Go to the Window Decorations section in the Appearance category in KDE settings and click the edit button that is overlayed over the Breeze theme.
     
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window_decoration_page.png" width="600px">
  3. Go to the Window-Specific Overrides tab and click "Add". Click "Detect Window Properties" and click a Vivaldi window; it should fill the "Regular Expression to Match" textfield for you automatically.
     
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window-specific_overrides.png" width="450px">
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window-specific_overrides2.png" width="450px">
     
  4. Check "Border Size" (Select "No Borders") and "Hide window title bar".
   
     <img src="https://github.com/BBFifield/Vivaldi-Breeze-Theme/blob/83a055d7dd1f5d17cd702f9ffba1929effeac0f1/Setup%20Screenshots/window-specific_overrides3.png" width="450px">


## Rounded Corners
* To get rounded corners for the Vivaldi window when using this theme, use "KDE-Rounded-Corners" by matinlotfali: https://github.com/matinlotfali/KDE-Rounded-Corners
