# Construction material's concrete compressive strength prediction using neural network algorithm

This is a neural network algorithm that predict concrete compressive strength using a .csv file (containing Cement (component 1)(kg in a m^3 mixture), Blast Furnace Slag (component 2)(kg in a m^3 mixture), Fly Ash (component 3)(kg in a m^3 mixture), Water  (component 4)(kg in a m^3 mixture), Superplasticizer (component 5)(kg in a m^3 mixture), Coarse Aggregate  (component 6)(kg in a m^3 mixture), Fine Aggregate (component 7)(kg in a m^3 mixture), Age (day) and Concrete compressive strength(MPa, megapascals)) to train. The algorithm can also predict concrete compressive strength based on user inputted features.

## Installation

Download the files from here on GitHub.

for the executable version, you can use it straight away if you have Microsoft Visual C++ which you can get from (https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).

for the source code please follow the following installation requirements in order:

1) Open terminal in the source code folder.
2) Paste the following string in the terminal.
```bash
pip install -r requirements.txt
```
3) Close the terminal and enjoy the program.

The code was developed on python 3.12 and should work best on it.

## How to use
Open the app then select the dataset to unlock all the input fields.

From here you can either train the model or use the already trained model.

To train the model click on train and wait (approximately 1 minute to an hour to finish), then two buttons will appear instead of training which are Results and Graph. the results option will open a window with R², RMSE and MAE values that the model achieved based on the training data. The graph button will show the actual vs predicted concrete compressive strength.

To predict inputted values, please input your features numbers in their perspective box, then click on predict. A prediction should appear in the model prediction box.

## Known issues and fixes
On some computers the text might be too large or too small and/or when the fullscreen feature is used the HUD becomes a box on the top left of the screen.

To fix these issues, right click on the program (MAIN.exe) then 'Properties', followed by 'Compatibility', then 'Change high DPI settings', check the 'Override high DPI scaling behavior.' box, and choose 'System (Enhanced)' from 'the scaling performed by:' menu.

or you can set the screen scale to 100% and display resolution to 1920x1080 from the display settings.
