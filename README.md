# Export YouTube Subscriptions
A simple and fast method for extracting your YouTube subscriptions ✨

---

I found it tricky to export a list of my YouTube subscriptions when I needed it for a project.

API requires the whole process of generating a key and OAuth if you haven't already.. Google Takeout is slow, and it was frustrating just trying to grab some channel IDs!

In the end, I realised that a simple viewsource and a quick Python script can easily export all of the data you want in under 30 seconds.

## Extracting subscription list

1. Included is the file 'getsubs.py'.
2. Head to https://www.youtube.com/feed/channels and load the entire page (you may need to scroll down)
3. Right click and view page source code 
4. Copy and paste the FULL page source code to a text file and save it as 'viewsource.txt' in the same directory
5. Run 'python3 getsubs.py'
6. A new file should be generated 'extracted_channels.yml'
7. In my case, I loaded the channels from that yml file into Zerotube!
8. ✨
