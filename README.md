# How To:

## Setup the Project
- Clone the Repo.
- Install Android Studio.
- Open Android Studio.
- Click "File"
- Click "Open"
- Navigate to the "WA-Android-Stickers" directory.
- Click on the Arrow to expand the directory.
- Select the "Android" folder (It will have a green Icon).
- Press "OK".
- If the IDE already has a project open select "This Window" when the dialogue for that appears.

## Build the Project
- After successfully opening the project it will automatically run a build (You can keep track of the progress by clicking on the "🔨 Build" tab at the bottom).

## Add you own Stickers!
- Navigate to "app/assets/", here you will find a file called "contents.json" where you will define the following properties:
-- "name" : The name of the sticker pack.
-- "publisher" : The name of the publisher eg your name here.
-- "publisher_website" : If you have a website you can add it here or leave it blank its optional.

- In the same file as above there is an array called "stickers", this is where you define the image and the name of the image you want to include, you can also define what "emojis" are related to said sticker.

## Add Sticker images
- There are two ways to add stickers, as webp files or as png files. I reccomend using the WEBP file format.
- Simply replace the images in the "app/assets/1" directory with the images that you want to include.

# Important
## Now to setup the APK to build your stickers app.
- Navigate to the "app/res/values" directory and open the "strings.xml" file.
- To set the name of your stickers app you can change the "app_name" value to the name you want to call the stickers app.
- Navigate to the "Gradel Scripts" directory and open the "build.gradle" file. Now change the "applicationId" to your publisher id eg "com.nicmeister.meisterstickers".

## Finally
- Now on the top right hand side you will see a green "🔨" (hammer icon), click this hammer.
- You will notice that the APK is getting built in the "Build Output" tab.
- Navigate to the "WA-Android-Stickers\Android\app\build\outputs\apk\debug" directory, copy the "app-debug.apk" file to your Android device and simply install it on your device.


# WhatsApp Stickers

If you'd like to create your own stickers for WhatsApp, you can package them in an Android or iOS app. You can publish your sticker app like any other app to the Google Play Store or Apple App Store, and users who download and install your app will be able to start sending those stickers right away from within WhatsApp. Stickers on WhatsApp must be legal, authorized and acceptable. Learn more about acceptable uses of our services from our [Terms of Service](https://www.whatsapp.com/legal/#terms-of-service).

To get started, review the `README` files in the [Android](https://github.com/WhatsApp/stickers/tree/master/Android) folders, and refer to the FAQ at https://faq.whatsapp.com/general/26000226.

### MUST READ
- Only use the GitHub Issues section if you discovered issues with the code itself. Do not mistake the Issues page as a help desk. You can ask for help at [Stack Overflow](https://stackoverflow.com/).  
For support, please contact <developer@support.whatsapp.com>.
- If you create issues or pull requests that are spammy by nature, you will be reported for abusive behavior immediately. You are providing no benefit to anyone.

### Issues
- Create an [Android](https://github.com/WhatsApp/stickers/issues/new?template=android.md) issue
- Create a [general issue](https://github.com/WhatsApp/stickers/issues/new?template=general.md)

For all three options, fill in all fields that apply.

### Pull Requests
- In order for us to accept pull requests, please complete the Contributor License Agreement by following instructions in [`CONTRIBUTING`](https://github.com/WhatsApp/stickers/blob/master/CONTRIBUTING.md).

## License
WhatsApp Stickers is BSD licensed, as found in the [`LICENSE`](https://github.com/WhatsApp/stickers/blob/master/LICENSE) file.