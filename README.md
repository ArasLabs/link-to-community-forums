# Link to Community Forums

This project adds a convenient "Community Forums" button to the main header toolbar in Aras Innovator, providing quick access to the Aras Community website. The button appears in the top-right area of the header and opens the community forums in a new tab when clicked.

Enhances the user experience by making it easy for users to access community resources, documentation, and support directly from within the Aras Innovator interface without having to bookmark or remember the community URL.

![Community Forums Button](./Screenshots/community-forums-button.png)

*The Community Forums button appears in the header toolbar with a community icon.*

## History

Release | Notes
--------|--------
[v1](https://github.com/ArasLabs/link-to-community-forums/releases/tag/v1) | Initial Release

### Supported Aras Versions

Project | Aras
--------|------
[v1](https://github.com/ArasLabs/link-to-community-forums/releases/tag/v1) | 14.0+ (Tested on Release 35)

*Note: This project was built and tested using Aras Innovator Release 35, but should work on any version of Aras Innovator 14.0 or later due to the simple nature of the CommandBarButton implementation.*

## Installation

### ⚠️ Important

**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. [Aras Package Import tool](https://aras.com/en/support/downloads).
3. **aras.labs.LinkToCommunityForums** import package

### Install Steps

#### Database Installation

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
    * *Note: You must login as root for the package import to succeed!*
4. Enter the package name in the TargetRelease field.
    * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\Link to Community Forums\Import\imports.mf` file in the Manifest File field.
6. Select the package in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Usage

1. Login to your Aras Innovator instance
2. Look for the Community Forums button in the top-right area of the header toolbar
    * ![screenshot](Screenshots/community-forums-button.png)
3. Click the button to open the Aras Community website in a new tab
4. The button is available to all users and provides quick access to:
    * Community discussions and forums
    * Technical documentation
    * Best practices and tips
    * Support resources

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by [Matt Toppi](https://github.com/matttoppi) for Aras Labs.

## License

Published to Github under the MIT license. See the [LICENSE file](./LICENSE) for license rights and limitations.
