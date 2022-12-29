barcode-buddy-home-assistant
# Barcode Buddy add-on for Home Assistant

Based on "barcodebuddy-homeassistant" at https://github.com/Forceu/barcodebuddy-homeassistant

Based on "Barcode Buddy for Grocy" at https://barcodebuddy-documentation.readthedocs.io/en/latest/

**NOTE**: After adding the repository "https://github.com/Forceu/barcodebuddy-homeassistant" to the Add-on Store (using right top : menu > repositories), remember to **restart** Home Assistant (Settings > System > Restart) for ```BarcodeBuddy - Home Assistant Repository``` to show up in the Add-on Store.

**TIP**: In contrast to Grocy, unknown barcodes are looked up with OpenFoodFacts.org first, in order to find out the product name / category. If found, Barcode Buddy checks if the user has stored any tags associated with the name: For example, if the name is “Chocolate bar”, it can automatically be set to the Grocy product “Chocolate”.

A known barcode will be processed, so it reduces / increases the inventory or manipulates the shopping list.

If the product could not be looked up, the user can select it manually.

Chores can also be executed with barcodes.
