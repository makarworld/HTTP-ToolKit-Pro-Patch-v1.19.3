# HTTP-ToolKit-Pro-Patch-v1.19.3

**At first check this:** [HTTP ToolKit Pro Patcher Repository](https://github.com/httptoolkit/pro-patcher)

I share my work because I myself have done a lot of work to understand how to “crack” the program. If you can support the development of HTTP ToolKit, you should buy a subscription. If you want to get the Pro version, you should check out the repository above, it describes how to get the Pro version for free and without hacks.

Use this method only as a last resort. I am immensely grateful to the author of the application and everyone involved in the development for the best tool I have ever used.

My crack works with [this place in the main JS code of the HTTP ToolKit UI page](https://github.com/httptoolkit/httptoolkit-ui/blob/0147fd8eac40a05da153c4ce2c6ada75246dcacf/src/model/account/account-store.ts#L174C1-L192C6)

I use Fiddler Everywhere and hacked `app.asar` file to enable the app to use global proxy settings for Electron.

## Guide

1. **Install Fiddler Everywhere:**
   - Download and install [Fiddler Everywhere](https://www.telerik.com/download/fiddler-everywhere).

2. **Optional: Use a crack for Fiddler Everywhere:**
   - You can use [this crack for Fiddler Everywhere](https://github.com/Eilte/Fiddler-Everywhere-Crack/releases) if needed.

3. **Replace the `app.asar` file:**
   - Download the `app.asar` file from the repository and replace the main file in the `/resources` directory of HTTP ToolKit.

4. **Import the FARX file:**
   - Download `HTTP ToolKit Pro.farx` from the repository.
   - Enable Rules in Fiddler Everywhere and import the `HTTP ToolKit Pro.farx` file.

5. **Launch HTTP ToolKit:**
   - Launch Fiddler Everywhere before starting HTTP ToolKit.
   - Enjoy the Pro features!

## Important Notes

- **Settings Page:** The settings page is not working.
- **Fiddler Everywhere:** For the crack to work, you should launch Fiddler Everywhere before HTTP ToolKit.
- **Updates:** HTTP ToolKit updates the JS file by timer. If Fiddler Everywhere is closed, you will be downgraded to the free version.
