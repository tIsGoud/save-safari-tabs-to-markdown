# Save Safari tabs to Markdown

![Safari tabs to Markdown](img/Safari-tabs-to-Markdown.png)

This AppleScript saves all tabs and URLs from the Safari windows to a new Markdown file.

The markdown file contains the tab names and URLs as clickable links.
URLs are grouped per browser window and seperated by a horizontal rule.
The date and the number of tabs and windows are displayed just below the title. In the title the name of the computer is used to identfy from which computer this file originated.

By default the markdown file is saved in your "Documents" folder. The location can be changed, the target directory is not checked so make sure it exists.

On succesfull creation of the markdown file a notification is displayed.

Next steps:

- Download the zip file or clone this repository.
- Run it from the Script Editor to test the script in your environment.

Once you made sure it works on your system you can:

- Turn it into a Automator workflow to create a Service.
  - More information: [Use Automator to create a System-Wide service](https://developer.apple.com/library/content/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/MakeaSystem-WideService.html) or
- Use [BetterTouchTool](https://www.boastr.net) to set up a keybinding or
- Use [BetterTouchTool](https://www.boastr.net) to create a Touch Bar button.

I went for the last option 😉

## Related

Saving browser-tabs is a recurring scripting item, below some links to other scripts to save browser-tabs from Chrome or Safari:

- [Save all your Google Chrome tabs to a markdown file](https://github.com/tIsGoud/save-chrome-tabs-to-markdown)
- [Save all your Google Chrome tabs in a Bear note.](https://github.com/tIsGoud/save-chrome-tabs-to-bear)
- [Save all your Safari tabs in a Bear note.](https://github.com/tIsGoud/save-safari-tabs-to-bear)
- [Save all your Chrome tabs in a Day One 2 entry.](https://github.com/tIsGoud/save-chrome-tabs-to-day-one)
- [Save all your Safari tabs in a Day One 2 entry.](https://github.com/tIsGoud/save-safari-tabs-to-day-one)
