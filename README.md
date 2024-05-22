# Likanu Keyboard for Windows

This keyboard layout tries to make it easy to write [Kokanu](https://www.kokanu.com/) in the [Likanu](https://www.kokanu.com/en/docs/likanu) abugida by reusing qwerty muscle memory whenever possible.

---

## Mapping

Consonants characters `ʜ ʌ x ɕ ʋ ɞ ƨ ɤ ɵ` are mapped the the corresponding consonant `p t k w l m n s h`.

Vowel diacritic/character `ȷ ı ʃ ſ` are mapped to the coresponding vowels `e i o u`.

The null consonant `o` is mapped to the "default vowel" `a`.

The coda diacritic `᷆◌` (-n) is added to a consonant by typing `d` after the consonant.

### Example

To type `ʌʋ᷆ſ`, you should type `tldu` 
To type `ʋɛıʌʃ`, you should type `lcito`

---

## How to install

### Using prebuilt setup

- Download the latest release and run `setup.exe`
- You need to logout and login to see the changes (or restart the computer)

### Manually

- Download [Microsoft Keyboard Layout Editor (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
- Open the .klc layout file with MSKLC and select `Project -> Build DLL and Setup Package`, then run the generated `setup.exe`
- You need to logout and login to see the changes (or restart the computer)

---

## How to uninstall


- You can remove it like any other program or by running `setup.exe` and selecting `uninstall`
