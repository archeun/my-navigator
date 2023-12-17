# Navigate Me
> Navigate me will keep track of your page visits inside a website. It improves your productivity by helping you quickly find your history of page navigations within the website.

This extension will keep track of the web pages you visit within a website. It improves your productivity by allowing you to see the history of all the web pages you visited on a website in one place. 

For eg: when surfing a documentation website, you might visit several pages to read about different topics. After some time, you need to go back to a previous article but do not remember its name/link. **Navigate Me** will help you quickly pick or search it from the listed URLs within the extension. 

This extension has an improved user experience than the standard Chrome History since it allows you to see all the visited pages while you are on the website. It provides simple yet powerful search functionality and sensible configurations.

**Navigate Me** extension stores data locally so you don't have to worry about privacy or data usage. It is minimalistic and has less clutter. 

## Screenshots

![screenshot-5](https://github.com/archeun/navigate-me/assets/5432727/85c09a66-05d5-4210-8d81-308e89c365aa) ![github](https://github.com/archeun/navigate-me/assets/5432727/4fc3bf89-9d49-4ed2-ad07-d3d5995cb569) ![mdn-docs](https://github.com/archeun/navigate-me/assets/5432727/906b35c8-ee60-4f6e-8459-2f6fe0c9ac89) ![settings-page](https://github.com/archeun/navigate-me/assets/5432727/b758a219-5950-4521-909e-b8c4119547e2)

## Features

- Records the web pages you visit within a website
- Lists down the web pages (most recent on top)
- Search and pick previously visited pages
- Remove selected pages from the list
- Setting to enable/disable tracking
- No data usage. The extension stores its data locally. Not synced with any cloud applications - privacy first

## Development

Follow the steps below to set up the extension codebase for development.

1. Clone (or fork and clone) the repository.
1. Navigate inside the root directory of the codebase.
1. Run `npm install && npm run watch`. This will build the extension for development. Build files can be found in the `<root-dir>/build` directory.
1. Then you can follow the instructions below to install the extension locally for testing. 
    1. Open `chrome://extensions`
    1. Switch on the `Developer mode` checkbox (top right corner of the page)
    1. Click on the `Load unpacked` button
    1. Select the `<root-dir>/build` folder and click `Open`.
 
