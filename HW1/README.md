
# HW1
All screenshots are saved in text format. To convert them back to images, you can use the following code:

```python
import base64
with open("screen.txt", "r") as txt_file:
    b64_string = txt_file.read()
img_data = base64.b64decode(b64_string)
with open("screen.png", "wb") as img_file:
    img_file.write(img_data)

  
