# Tool List

## **steghide**

---

```txt
# This tool is available for linux.
    * Need to check if available for others too.
```

- **Usage:**

_Install on debian based systems:_

```bash
apt install steghide
```

_Hide file:_

```bash
steghide -ef path_to_file_needed_to_be_hidden -cf path_to_file_to_hide_inside -sf output_file_name-optional -z compression_level_from_1_to_9-If_capital_no_compression_will_be_used -e ecription_type-can_be_none_or_any_seported_encrition-If_omited_then_deafults_to-128bit_AES
```

_Export the hidden file:_

```bash
steghide extract -sf stegoFile -xf outputFile
```

## **Reverse Google Image Search**

---

### **Usage:**

Go to this [Link](https://images.google.com/) using your browser.

- Drag the image you want to find to the search box.
- Releese the mouse and let the image upload.
- After the image finished loading, google will give you the search resolts.
