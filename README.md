# Piteas Widget Generator

This repository provides an easy-to-use HTML-based tool to generate a fully customizable iframe for integrating the Piteas widget into your website. The widget allows users to perform ERC20 token swaps seamlessly.

## Features
- Configure the widget with input and output currencies.
- Set an exact input amount for token swaps.
- Light and dark theme options.
- Fully responsive preview with adjustable width and height.
- Copy the iframe HTML code snippet directly for integration.
- Automatically incorporates `exactField` when an exact input amount is provided.

## How to Use
1. Open the `index.html` file in your browser.
2. Fill in the configuration fields:
   - **Input Currency**: Enter the symbol or address of the token to swap from (e.g., `PLS` - PLS is default).
   - **Output Currency**: Enter the symbol or address of the token to swap to (e.g., `0x...`).
   - **Exact Amount**: Optionally specify the amount of the input token to swap.
   - **Theme**: Choose between `light` and `dark` themes.
   - **Height and Width**: Adjust the iframe size.
3. Copy the generated HTML code snippet and embed it into your website.

## Example
```html
<iframe
    src="https://widget.piteas.io/#/swap?inputCurrency=PLS&outputCurrency=0x2A06a971fE6ffa002fd242d437E3db2b5cC5B433&theme=dark&exactField=input&exactAmount=1000000"
    height="720px"
    width="100%"
    style="border: 0; margin: 0 auto; display: block; max-width: 960px; min-width: 300px;">
</iframe>
```

## Documentation
For detailed information about the widget API, including supported query parameters and preloaded token symbols, please refer to the official [Piteas Widget API documentation](https://docs.piteas.io/widget-api).

## License
This project is licensed under the MIT License. See the LICENSE file for details.
