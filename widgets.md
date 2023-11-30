## Running bar
The running bar allows publishers to easily display a list of digital assets prices and the (%) daily change, similar to CoinDesk. 
![image](https://user-images.githubusercontent.com/7950236/226941177-0b5a632b-e5bb-4b63-98a6-356ef9aed73a.png)

See example: https://app.finst.com/widgets/running-bar

### Integration
Use the following iframe and place it in the desired position on your website. We recommend placing it above or right below the main navigation.

```html
<iframe 
    src="https://app.finst.com/widgets/running-bar?theme=light&affiliateId=value&tap_a=value&tap_s=value"
    frameborder="0"
    width="100%"
    height="36"
    style="border: 0 none; width: 100%;"></iframe>
```

#### URL parameters
In the URL parameters please replace `value` with the correct attributes specific to your widget implementation. 

| Name            | Required | Description |
| --------------- | -------- | ----------- |
| `affiliateId`   | Yes      | Website Name of the affiliate partner who integrates the widget |
| `promotionCode` | No       | Finst promotion code if applicabl                       |
| `theme`         | No       | Specify the color scheme of the widget `dark` or `light`|
| `tap_a`         | No       | Use the `tap_a` value from your Tapfiliate account      |
| `tap_s`         | No       | Use the `tap_s` value from your Tapfiliate account      |

