## Changes from the original project:
* Redesigned the UI. Now it is more compact.
* Added minimize to tray. Now the app will minimize to the notification tray.
* Added support for more status changes: DoNotDisturb + TemporarilyAway + Offline.
* Workaround for email issues: The email you add to the list is not necessarily the same as the one taken from Lync so the function to assign colors to the contact balls may fail because of comparison failure. Changes were changing .First() to .Last(). **This may not work for you out of the box**.

---

# Lync Spy
Monitors and sends notification of anyones status changes in Lync or Skype for Business

for more information read my [Lync Spy](http://analystcave.com/lync-lync-spy-monitor-get-notified-anyones-status-changes/) post at [AnalystCave](http://analystcave.com/)

# What is does
The Lync Spy is a draft project from the [AnalystCave](http://analystcave.com/) website aimed to help track status changes of Skype for Business / Lync users. You can set whether you want to receive email notifications of status changes or if you want to track all status changes neatly in a CSV file.

# Comments
This project is a draft and hasn't undergone any code refactoring, sharely soley due to the large interest of my readers.

In case you would like to clone this project please link out to the original post on AnalystCave: [Lync Spy](http://analystcave.com/lync-lync-spy-monitor-get-notified-anyones-status-changes/)