# Traffic Lights
> Simple multi-device traffic lights for my boy to play with at home

![alt text](https://i.ibb.co/khzw2Xk/Screen-Shot-2019-12-15-at-09-20-01.png "Traffic Lights")

### Instructions
- Load URL on your devices - [https://dangarfield.github.io/traffic-lights](https://dangarfield.github.io/traffic-lights)
- Set the `id` parameter to something specific, eg like a channel, can be any string `?id=123&type=b`
- There are 3 device types: The default setting is button `b`
    - Button - ensure `type` param is set to `b` - `?id=123&type=b`
    - Pedstrian Lights - ensure `type` param is set to `p` - `?id=123&type=p`
    - Car Lights - ensure `type` param is set to `l` - `?id=123&type=l`

### Technology
- Browser only
- Uses `PubNub` to communicate between clients