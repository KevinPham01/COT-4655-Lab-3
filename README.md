# ios102-lab3-Fall2024

## What I Learned
* Camera Integration: Used UIImagePickerController to capture photos and handle media selection.
* Parse Backend: Added custom user properties (e.g., lastPostedDate) and applied query constraints to fetch posts from the past 24 hours.
* UI Enhancements: Implemented a blur view to hide posts based on timing, using UIVisualEffectView.
* Async Data Handling: Saved data to Parse asynchronously with smooth UI updates.
* Permissions: Updated Info.plist for camera access permissions.

## Features
* Users can capture and upload photos using the device camera.
* Posts are hidden until the user uploads their own photo.
* Fetches the 10 most recent posts within the last 24 hours.
* Blurs posts older than 24 hours since the user's last post.
* Asynchronous saving of user data to Parse.

![instaparse_walkthrough_1_xtra_small](https://user-images.githubusercontent.com/11927517/199710313-700aef85-ba89-427c-aa07-f89f0fdfdbbe.gif)
