# Public Update set repository for use in ServiceNow
In this repository I public update sets with the configuration/code I use in my blogs and videos for easier access for the viewers & readers.

I take no responsibility on the results of using these update sets in your instances. Make sure that you always test them in a safe environment first. E.g. personal developer instance or your company dev instance.

As you can see below, I have splitted up each blog/video with some small description, link to video/blog as well as a download link for the update set. So just right-click and save ass and it will be downloaded.

To make it easier to download the update sets I made a link within each section

## Responsive Widget for Service Portal
Video: https://youtu.be/-eJMULIa43A

Update set: [download (Save as)](https://raw.githubusercontent.com/goranlundqvist/Update-sets/master/Responsive%20Widget/Responsive%20widget.xml)

Question came up on the community and it isn't the first one. A member would like to have a "action button" that would appear or disappear on the page without needed to reload the page.

In this example I borrow an example of a action button from Serviceportal.io which has some really nice examples. A link to the specific page for it is at the description of the YouTube video. Then we add some code so depending if the state of the incident is "resolved" or not it will show different buttons with different behaviors. Either it's "Resolve incident" or "Reopen incident". And even if you have the page already open and someone else changes the state from the normal UI, the widget will change. All this is made possible through 1 (almost) line of code with the magic of recordwatch.

## Best Practice with Client Script and GlideAjax:
Video: https://www.youtube.com/watch?v=p5F3lpXgkHk

Update set: [download (Save as)](https://raw.githubusercontent.com/goranlundqvist/Update-sets/master/GlideAjax%20example/GlideAjax%20example.xml)

I go through how to use GlideAjax and the importance of setting both value and displayValue on a reference field.

Update set containing a Client script and a Script include. Example is used on incident form and when a CI is entered, it does a GlideAjax call, and returns a JSON with both the value and displayValue of the support group.

## Nice features to know about in ServiceNow:
Video: https://youtu.be/4Dp2rlMO-7c

Update Set: [download (Save as)](https://raw.githubusercontent.com/goranlundqvist/Update-sets/master/nice%20to%20have/Nice%20to%20have.xml)

In this video I show some nice features for the admins/developer. E.g. How to effectly filter the app navigator, .config/.list etc., syntax editor macros and I also give away two nice scripts. One to find which record a sys_id belongs to and one to find records in the a table that has the same value in a field without specifying the value itself.
