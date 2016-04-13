# ScreenShare

ScreenShare allows you to take and share a screenshot from anywhere on your Mac simply by pressing on the icon in the statusbar.
Inspired by [ClipUpload](http://clipupload.net/) and [ShareX](http://getsharex.com/) there are simple .json files used to create "addons" or add "providers". This allows custom uploaders of any kind. A good example is the Dropbox configuration found in the providers folder (dropbox.json.example) that shows how to upload to dropbox using an auth token (this can be acquired by creating your own app for dropbox and grabbing your auth token). Some custom uploaders of ShareX are even compatible right out of the box.

Uploading text and shortening a URL is also possible and will be put under "Tools" in the context menu. For this you can look at the pastebin.json and hnng.moe (URL shortener).json.

## How to add custom providers
1. Right click on ScreenShare and select "Show Package Content"

![](http://i.imgur.com/ldYcjjNl.png)

2. Navigate to Contents -> Resources -> Providers
3. Drop your custom provider .json file here
4. Restart ScreenShare

## Screenshot
![So easy](http://i.imgur.com/2E5nyHsl.png)
