# imagechanger-chrome_extension
A chrome extension which changes images randomly and add your focus task

# CHROME EXTENSION

To use This Extension in Chrome, you need to add this extension.

<h3>HOW TO INSTALL A DEVELOPER VERSION</h3>

1. `git clone git@github.com:aman34503/imagechanger-chrome_extension.git`
2. Go to the folder with the Chrome extension. Open the **manifest.json** file and add your website to the **matches** section.


3. In the address bar on a new tab, type **chrome://extensions** to open the Extensions page. Select the **Developer mode** check box to enable loading extensions from a folder.

4. Click **Load unpacked extension** or drag the folder with extension onto the page to load the extension. The new extension will be displayed on the page.

5. **IMPORTANT:** if you want to change **manifest.json** again (for example, add another test server), you should also change the **version** parameter, namely increase its value. Then remove the extension from Chrome and add it again.


<h3>HOW TO MAKE A PRODUCTION VERSION</h3>
You should pass the procedure of publishing your extension in Google Web Store. For details, see the <a href="https://developer.chrome.com/webstore/get_started_simple#step5">official documentation</a>.



https://user-images.githubusercontent.com/77502312/128482136-9e60f32c-c5a2-483a-9dea-5d0e9efd4b22.mp4




## Available Scripts

Check `scripts` section of `package.json`

## Contribute

Thanks for taking time to contribute, this project uses [gatsby](https://github.com/gatsbyjs/gatsby). please checkout [src](src) to understand how things work.

### Reporting Issues

Found a problem? Want a new feature? First of all see if your issue or idea has [already been reported](../../issues).
If don't, just open a [new clear and descriptive issue](../../issues/new).

### Submitting pull requests

Pull requests are the greatest contributions, so be sure they are focused in scope, and do avoid unrelated commits.

- Fork it!
- Clone your fork: `git clone https://github.com/<your-username>/portfolio`
- Navigate to the newly cloned directory: `cd portfolio`
- Create a new branch for the new feature: `git checkout -b my-new-feature`
- Install the tools necessary for development: `yarn`
- Make your changes.
- Commit your changes: `git commit -am 'Add some feature'`
- Push to the branch: `git push origin my-new-feature`
- Submit a pull request with full remarks documenting your changes
