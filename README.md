# Exercise-01c-Export-from-Twine
Exercise for MSCH-C220, 1 September 2020

This exercise will set up Twine to be able to export a version of your interactive fiction game for use in your Python game engine.

Begin by Forking this repository. Check that it has been forked successfully; the repository should now read [your username]/Exercise-01c-Export-from-Twine

Edit the LICENSE and replace BL-MSCH-C220-F20 with your full name. Commit your changes.

Press the green "Code" button and select "Open in GitHub Desktop". Allow the browser to open (or install) GitHub Desktop. Once GitHub Desktop has loaded, you should see a window labeled "Clone a Repository" asking you for a Local Path on your computer where the project should be copied. Choose a location where you will keep the repositories for this class (a C220 folder off your Desktop would be fine). Make sure the Local Path ends with "Exercise-01c-Export-from-Twine" and then press the "Clone" button. GitHub Desktop will now download a copy of the repository to the location you indicated.

Open Twine. In the right-hand sidebar, select "Formats". You should see a list of possible story formats for Twine. In the bar on the top of that window is a button "Add a New Format". Select that now.

The window should now read "To add a story format, enter its address below." Enter https://lazerwalker.com/twison/format.js and press the green "Add" button.

Now, press the green "+Story" button. Give the story a name (whatever you would like). Create a story with at least four passages. I recommend the 

If you need additional help with the Twine syntax or getting started, you can follow the example at the [Twine Cookbook](https://twinery.org/cookbook/starting/twine2/firststory.html). For more information about Passage links, read [Creating Links](https://twinery.org/cookbook/starting/twine2/creatinglinks.html).

If you try to Play your story, you will get a syntax-heavy (json) file instead of a playable game (that is the end-result of this exercise). If you want to test it before turning it in, you can select the story name (on the bottom bar of the Twine window, and choose "Change Story Format". Harlowe 3.1.0 is the default, playable story format for Twine).

When you are done, make sure Twison 0.0.1 is selected as the story format and press "Play". You will now see a single (JSON) file containing your story.

This content needs to be saved as a text file (named game.json) and added to this repository. You can open a new file in VS Code, copy the contents from the web browser and paste it into the new document. Save the file (in the repository folder) as game.json.

I don't really care about the contents of this game for now. I just want to make sure you can successfully export a JSON file from Twine. This could be a good opportunity for you to think about what the game for your project will be about.

In GitHub Desktop, you should now see game.json highlighted. Add a Summary message at the bottom of that panel, and push the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see that your files have been changed (with a new date).

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-01c-Export-from-Twine) on Canvas.

The final state of the file should be as follows (replacing my information with yours):

# Exercise-01c-Export-from-Twine

Exercise for MSCH-C220, 1 September 2020

A JSON file, describing an interactive fiction game, exported from Twine

## Implementation
Created using Twine 2 and exported with Twison 0.0.1 (https://github.com/lazerwalker/twison)

## References
None

## Future Development
None

## Created by
Jason Francis
