# Belgrade
Belgrade is a Bootstrap subtheme made for Drupal Commerce 2.0.


Any questions or feedback?
[Create an issue on drupal.org](https://www.drupal.org/project/issues/belgrade)


# Getting started with Belgrade

### Enable Drupal debbuging
Need a few words on enabling Drupal debugging

### Working with Gulp

1. [Install Yarn](https://yarnpkg.com/en/docs/install),

2. [Install the Gulp cli tool](https://gulpjs.com/),

3. The package.json file contains all the npm packages you need. To install run:
    ```
    yarn install
    ```

4. Configuration for all gulp tasks is located in ./gulp.js/config.js file.
   To make BrowserSync work edit the line:
    ```
    localUrl = 'http://localhost';
    ```

5. Do start developing run:
    ```
    yarn(or npm) run start
    ```
    Which will start the gulp watch task.

6. To generate icons from a set of svg files with a matching SCSS file, run a npm script:
    ```
    yarn(or npm) run icons
    ```
