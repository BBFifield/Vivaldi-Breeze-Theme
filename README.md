# Vivaldi-Breeze-Theme

## About:
* This theme was created so KDE users could experience having an up-to-date chromium-based web browser that looks and feels tightly integrated with the plasma shell when using the default breeze-dark theme in KDE.
* The theme was created to closely resemble Breeze-dark from KDE 5.27.6 and tested against Vivaldi 6.1.3035.100.

* To enable this theme, go to vivaldi://experiments/ and check "Allow CSS Modifications". Then head to the Appearance section in Vivaldi settings and choose the root folder of this theme under "CUSTOM UI MODIFICATIONS".

* To allow Kwin to draw window shadows when not using the native window controls and border, perform the following steps:

  1. Set a Kwin window rule like so:
     Property Name | Input Option | User Input 
     | :--- | ---: | :---:
     Window Class  | Exact Match | Vivaldi Stable
     No titlebar and frame  | Force | No
     
  2. Go to the Window Decorations section in the Appearance category in KDE settings and click the edit button that is overlayed over the Breeze theme.
  3. Go to the Window-Specific Overrides tab and click "Add". Click "Detect Window Properties" and click a Vivaldi window; it should fill the "Regular Expression to Match" textfield for you automatically.
  4. Check "Border Size" (Select "No Borders") and "Hide window title bar".


## Rounded Corners
* To get rounded corners for the Vivaldi window when using this theme, use "KDE-Rounded-Corners" by matinlotfali: https://github.com/matinlotfali/KDE-Rounded-Corners
