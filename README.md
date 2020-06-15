# Your support
<a href="https://www.buymeacoffee.com/Ua0JwY9" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

# Configuration

| Name | Type | Default | Description |
|------|:----:|:-------:|-------------|
| name ***(required)*** | string | | Set a custom name which is displayed beside the icon.
| listen_port ***(required)*** | integer | `8125` | Set port on which to listen for connection
| clientid ***(required)*** | integer | `1234` | Set client id

#### Example:
```yaml
alarm_control_panel:
  - platform: secolink
    name: Home
    listen_port: 8125
    clientid: 1234
```
