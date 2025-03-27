# ZR Media Content Paragraph Installation Guide

To install the ZR Media Content Paragraph, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Ahead of running `composer require zr/RECIPE_NAME` - ensure the below has been added to the root `composer.json` **installer-paths**
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to execute the ZR Media Content Paragraph installation:

    ```sh
    ddev drush recipe recipes/custom/zr-para-media-content
    ```

This command will execute the ZR Media Content Paragraph installation.
