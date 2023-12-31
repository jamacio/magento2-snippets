# Magento 2 Snippets Extension for Visual Studio Code

## Overview

Welcome to the Magento 2 Snippets extension for Visual Studio Code! This extension is designed to streamline the development process in Magento 2 by providing a collection of code snippets that simplify common tasks. Whether you're a beginner or an experienced Magento 2 developer, these snippets will save you time and boost your productivity.

## Installation

1. Open Visual Studio Code.
2. Access the Extensions view by clicking on the square icon in the sidebar or by pressing `Ctrl+Shift+X`.
3. Search for "Magento2 snippets."
4. Click on "Install" to install the extension.
5. Once installed, you can start using the snippets in your Magento 2 projects.

## Usage

Using Magento 2 Snippets is straightforward. Follow these steps to start using the snippets in your code:

1. Open a Magento 2 project in Visual Studio Code.
2. Create or open a PHP, XML, or PHTML file.
3. Type the prefix of a snippet and press `Tab` to trigger the code snippet.

For example, to pick up a product by ID in Magento 2, type `m2.get_product_by_id` and press `Tab`. The extension will automatically generate the code structure for you.

**Trigger:** `m2.get_product_by_id`

**Output:**
```php
$objectManager =  \Magento\Framework\App\ObjectManager::getInstance();
$productId = 1; // Replace with the desired product ID
$product = $objectManager->create('\Magento\Catalog\Model\Product')->load($productId);
echo $product->getName();
// note: Magento does not recommend using ObjectManager in production
```
## Available Snippets

Here is a list of some of the available snippets:

- `m2.routes`: Create a routes file.
- `m2.layout.block`: Create a new block class.
- `m2.logger`: Create a log file.
- `m2.object_manager`: Create an object manager.
- `m2.cls_product`: Factory class for products in Magento.
- `m2.cls_category`: Factory class for categories in Magento.
- `m2.list_carts"`: List all shopping carts.
- `m2.create_order"`: Create a new order.
- `m2.get_order_by_id"`: Get an order by ID.
- And many more!

## Customization

You can customize the extension to match your coding style and preferences. To do so, follow these steps:

1. Go to **File** > **Preferences** > **Settings**.
2. Search for "Magento2 snippets" in the search bar.
3. You can modify existing snippets or add your own.

## Contributions

This extension is open source, and contributions are welcome. If you have snippets or improvements to share, visit our [GitHub repository](https://github.com/jamacio/magento2-snippets) to make a contribution.

## Support

If you encounter issues, have suggestions, or need assistance, please visit the [issue tracker](https://github.com/jamacio/magento2-snippets/issues) on GitHub to report problems or request help.

Happy coding with Magento 2 Snippets in Visual Studio Code!

[GitHub Repository](https://github.com/jamacio/magento2-snippets)
[Report Issues](https://github.com/jamacio/magento2-snippets/issues)
[Support Contact](mailto:jamacio@hotmail.com)
