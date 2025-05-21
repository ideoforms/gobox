# gobox

Support for the That Little Box [USB Go Box](https://www.thatlittlebox.co.uk/usb-go-box).

## Usage

```python
box = USBGoBox()
def on_press(button_name):
    # button_name will be one of yellow, blue, red, green, left, right
    print("Button pressed: %s" % button_name)
box.on_press = on_press
```
