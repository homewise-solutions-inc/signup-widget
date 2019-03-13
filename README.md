# Homewise Sign-Up Widget

This documentation covers the integration guide for Homweise Sign-Up widget for 3rd party websites. This is a JavaScript based utility which renders a sign-up widget on host website.

## Installation
### Step 1
Contact us at __hello[at]thinkhomewise.com__ to get your partner referral code.

### Step 2
Place the following library snippet in the `<head/>` section of your page.
```
<script src="https://cdn.thinkhomewise.com/app/js/widget.js"></script>
```
 ### Step 3
 Place following code snippet where you want the widget to render.
 
 ```
<div class="hw_mortgage" data-r=""></div>
```

Refer to the following table for a list of possible HTML5 data attributes to further customize it.

| Parameter | Required| Default | Description |
| ------ | ------ | ------ | ------ |
| `data-r` | Y | `null` | Referral code provided by Homewise.
| `data-w` | N | `800` | Width of the widget. |
| `data-h` | N | `450` | Height of the widget. |
| `data-scroll` | N | `no` | Toggle scrolling. |
| `data-bg_color` | N | `#ffffff` | Background color to use. |
| `data-padding` | N | `1` | Padding to add _outisde_ of the widget. |

## Styling
- You may use CSS query `.hw_mortgage iframe` to perform in-page styling.
- Content inside the widget is responsive.
- Optimal __WxH__ for the large screen size is `800x450` and for small screen size is `300x650`.
 
## Support
Contact Homewise Solutions Inc. for support. Feel free to report any bugs you identiy on GitHub.

Read Homewise [privacy policy](https://thinkhomewise.com/page/privacy) and [terms of agreemnt](https://thinkhomewise.com/page/terms).