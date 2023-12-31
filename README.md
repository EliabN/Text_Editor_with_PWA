# Text Editor with Progressive Web Applications (PWA) 
A text editor that runs in the browser. The application will be a single-page application that meets the PWA criteria. 

>**Additionally**, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

## Database

To implement methods for getting and storing data to an IndexedDB database a package called `idb` is used; which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like `Google` and `Mozilla`.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Preview

Application is deploy to `Heroku` : [>Click Here< ](https://text-editor-with-pwa-f86237236be0.herokuapp.com/)to try it out.

**Important**: Make sure your submission includes the `.npmrc` file in this starter code.  This will ensure your application will deploy properly to heroku.

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

## License

This project license is under the [MIT](https://opensource.org/licenses/MIT)

## Contribute

Git fork. Pull request

## Resources

* [heroku](https://dashboard.heroku.com/)
* [Express.js](https://www.npmjs.com/package/concurrently)
* [concurrently](https://www.npmjs.com/package/concurrently)
* [Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
* [webpack](https://webpack.js.org/)
