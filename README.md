# espn-polling - POC

This is a proof of concept of a live updating mechanism for ESPN snake drafts. This is for developer reference only so that they can hopefully integrate it within their own spreadsheets/applications. I believe this only works with public drafts, for now. But can pretty easily be updated to take cookies if necessary (or username and password).

## Getting started

Load the spreadsheet and open the settings tab.

Go to your draft and open up the lite draft application

![lite draft](https://github.com/jonrad/espn-polling/blob/master/lite-draft.png)

Once in the lite draft, go to view source and copy and paste the magic ESPN draft token

![token](https://github.com/jonrad/espn-polling/blob/master/token.png)

Paste this into the "Token" portion of the settings (Cell B2)

If you need to fill in proxy information, you may do so as well.

Once the draft has started, go to the results tab and press "Poll ESPN". You should see data start filling into rows 2+. 

## FAQ

* I'm not a developer, how do I use this?

This isn't for you. Sorry. This is intended for other developers to implement into their amazing spreadsheets and applications.

* Why did you use Excel/VBA and why didn't you use feature XYZ?

I don't know VBA. At all. I literally copy and pasted a bunch of stuff I found on the internet. But, there are so many good spreadsheets out their, I'm hoping people who are smarter than I am will take this and run with it.

* Nothing happens when I poll, what's up?

I don't know. I just do this for fun. I wish I had the time to find all the edge cases for when this does and doesn't work, but I'm quote busy researching for my leagues (and I guess work takes up time too). If you find a better way to do something or bug, feel free to do a pull request.
