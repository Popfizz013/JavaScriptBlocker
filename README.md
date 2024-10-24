# AdGuard - JavaScript Ad Blocker

AdGuard is a powerful, lightweight ad blocker designed to enhance your browsing experience by eliminating intrusive advertisements. This project is being developed by a team of four, and we aim to make the web cleaner and faster by blocking unwanted ads across all websites.

## Features

- **Ad Blocking**: Automatically blocks a wide range of ads from websites.
- **Custom Blocklist**: Users can add new websites to their own custom blocklist for more personalized control.
- **Efficient & Lightweight**: Built for performance with minimal impact on browsing speed.
- **Chrome Webstore Compatibility**: Will be made available on the Chrome Webstore for easy access and installation.

## Getting Started

### Installation

While AdGuard is in development, you can try it out locally by following these steps:

1. Clone or download this repository.
2. Open Chrome and go to `chrome://extensions/`.
3. Enable **Developer mode** at the top-right of the page.
4. Click **Load unpacked** and select the project folder.
5. The AdGuard icon will appear in your browser toolbar, allowing you to manage settings.

### Usage

Once installed, AdGuard will automatically start blocking ads on all websites. The extension also provides options for users to:

- **View Blocklist**: View the list of blocked websites.
- **Add Website**: Manually add domains to your blocklist for additional control over which ads are blocked.
- **Pause/Resume Blocking**: Easily disable or re-enable the ad blocker as needed.

## Skills Gained

During the development of this project, our team learned and improved various skills:

- **JavaScript Proficiency**: We enhanced our JavaScript coding skills, particularly in the manipulation of DOM elements to detect and block ads.
- **Chrome Extensions API**: Learned to work with the Chrome Extensions API, particularly the `webRequest` and `webRequestBlocking` permissions to intercept and block network requests efficiently.
- **Asynchronous Programming**: Improved handling of asynchronous operations using promises and `async/await` to dynamically load and update the blocklist.
- **UI/UX Design**: Designed an intuitive, easy-to-use interface that allows users to interact with the extension seamlessly.
- **Local Storage & Syncing**: Learned to use Chrome's local storage to store user preferences and blocklists, ensuring persistence across browser sessions.

## Lessons Learned

Some challenges and lessons we encountered during the development process:

- **Efficient Ad Detection**: Balancing performance with ad detection efficiency was challenging. We optimized our methods to ensure ads are blocked without slowing down the browser.
- **Dynamic Content Handling**: Ads often load dynamically after the main page content, requiring us to monitor and block elements that appear after the initial page load.
- **User Blocklist Management**: Building a robust system to allow users to add and manage their own blocklist was both a technical and design challenge. We learned about data persistence using Chrome's local storage.

## Future Plans

We have several ideas for future development:

- **Chrome Webstore Release**: We plan to release AdGuard on the Chrome Webstore for broader accessibility.
- **Enhanced Blocklist Management**: We aim to allow users to export, import, and share custom blocklists.
- **Custom Ad Filtering Rules**: A feature that enables users to create custom rules for blocking specific ad patterns or types will be implemented in future updates.

## Contributing

Contributions are welcome! If you would like to contribute to AdGuard, please feel free to submit a pull request or report any issues you encounter.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
