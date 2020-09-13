# **Introductory Researching**

---

- press the [Join room](http://#/) button to use the machins in this Stage.

## **Task 1 (Introduction)**

---

### **Read the Introduction**

```txt
No asnwer neede
```

press the [completed](http://#/) button after reading.

## **Task 2 (Example Research Question)**

---

**reading the artical on [Steganography](https://null-byte.wonderhowto.com/how-to/steganography-hide-secret-data-inside-image-audio-file-seconds-0180936/)**

**_Tools in this artical:_**

### steghide (used in linux)

- used like so:

```bash
steghide -ef path_to_file_needed_to_be_hidden -cf path_to_file_to_hide_inside -sf output_file_name-optional -z compression_level_from_1_to_9-If_capital_no_compression_will_be_used -e ecription_type-can_be_none_or_any_seported_encrition-If_omited_then_deafults_to-128bit_AES
```

```txt
you will be asked to set a password for the file.
```

- to extract use the command:

```bash
steghide extract -sf stegoFile -xf outputFile
```

```txt
you will need the password from the encryption procces.
```

- install with the command:

```bash
apt install steghide
```

### Reverse google image search - [link](https://images.google.com/)

### Some more reading

- [hide data in audio files](https://null-byte.wonderhowto.com/how-to/hacks-mr-robot-hide-data-audio-files-0164136/)

- [How to hack forum accounts with password-stealing pictures.](https://null-byte.wonderhowto.com/how-to/hack-forum-accounts-with-password-stealing-pictures-0179953/)

- [Need to go into it](https://0xrick.github.io/lists/stego/)

### **Install the steghide tool (did not do it, need a linux machine):**

```bash
apt install steghide
```

### Questions to fill

1. In the Burp Suite Program that ships with Kali Linux, what mode would you use to manually send a request (often repeating a captured request numerous times)?

```txt

```
