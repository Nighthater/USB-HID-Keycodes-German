# USB-HID-Keycodes-German
Overview of all USB HID Keycodes of an ISO-105 German Keyboard.  
This is by no means a complete list of all Keycodes, only those that are directly needed 
to create a fully working ISO-105 compatible keyboard with your own microcontroller.

##### I couldn't fully verify every keycode yet. If you have found a discrepancy please open an issue

## Letter Keys
### (A-Z, 0-9, ß, ä, ü, ö, Enter, Bsp, Space)

| Key  | Decimal HID Code | Hex HID Code |
| ------------- | ------------- | ------------- |
| a  | 4  | 0x04 |
| b  | 5  | 0x05 |
| c  | 6  | 0x06 |
| d  | 7  | 0x07 |
| e  | 8  | 0x08 |
| f  | 9  | 0x09 |
| g  | 10  | 0x0A |
| h  | 11  | 0x0B |
| i  | 12  | 0x0C |
| j  | 13  | 0x0D |
| k  | 14  | 0x0E |
| l  | 15  | 0x0F |
| m  | 16  | 0x10 |
| n  | 17  | 0x11 |
| o  | 18  | 0x12 |
| p  | 19  | 0x13 |
| q  | 20  | 0x14 |
| r  | 21  | 0x15 |
| s  | 22  | 0x16 |
| t  | 23  | 0x17 |
| u  | 24  | 0x18 |
| v  | 25  | 0x19 |
| w  | 26  | 0x1A |
| x  | 27  | 0x1B |
| y  | 29  | 0x1D |
| z  | 28  | 0x1C |
| 1  | 30  | 0x1E |
| 2  | 31  | 0x1F |
| 3  | 32  | 0x20 |
| 4  | 33  | 0x21 |
| 5  | 34  | 0x22 |
| 6  | 35  | 0x23 |
| 7  | 36  | 0x24 |
| 8  | 37  | 0x25 |
| 9  | 38  | 0x26 |
| 0  | 39  | 0x27 |
| ß  | 45  | 0x2D |
| ä  | 52  | 0x34 |
| ü  | 47  | 0x2F |
| ö  | 51  | 0x33 |
| Enter  | 40  | 0x28 |
| Backspace  | 42  | 0x2A |
| Space  | 44  | 0x2C |
| Tab  | 43  | 0x2B |
| Caps Lock  | 57  | 0x39 |

## Numpad Keys
### (0-9, /, *, -, +, Enter, NumLock)

| Key  | Decimal HID Code | Hex HID Code |
| ------------- | ------------- | ------------- |
| 1  | 89  | 0x59 |
| 2  | 90  | 0x5A |
| 3  | 91  | 0x5B |
| 4  | 92  | 0x5C |
| 5  | 93  | 0x5D |
| 6  | 94  | 0x5E |
| 7  | 95  | 0x5F |
| 8  | 96  | 0x60 |
| 9  | 97  | 0x61 |
| 0  | 98  | 0x62 |
| ,  | 133  | 0x85 |
| .  | 99  | 0x63 |
| /  | 84  | 0x54 |
| *  | 85  | 0x55 |
| -  | 86  | 0x56 |
| +  | 87  | 0x57 |
| Enter  | 88  | 0x58 |
| NumLock  | 83  | 0x53 |

## Functions Row
### (Esc, F1-F12. Print, Roll, Pause)

| Key  | Decimal HID Code | Hex HID Code |
| ------------- | ------------- | ------------- |
| Esc  | 41  | 0x29 |
| F1  | 58  | 0x3A |
| F2  | 59  | 0x3B |
| F3  | 60  | 0x3C |
| F4  | 61  | 0x3D |
| F5  | 62  | 0x3E |
| F6  | 63  | 0x3F |
| F7  | 64  | 0x40 |
| F8  | 65  | 0x41 |
| F9  | 66  | 0x42 |
| F10  | 67  | 0x43 |
| F11  | 68  | 0x44 |
| F12  | 69  | 0x45 |
| Print Scr.  | 70  | 0x46 |
| Roll Lock  | 71  | 0x47 |
| Pause, Break  | 72  | 0x48 |
| Insert  | 73  | 0x49 |
| Pos 1  | 74  | 0x4A |
| Pg Up  | 75  | 0x4B |
| Del  | 76  | 0x4C |
| End  | 77  | 0x4D |
| Pg Down  | 78  | 0x4E |
| Up  | 82  | 0x52 |
| Down  | 81  | 0x51 |
| Left  | 80  | 0x50 |
| Right  | 79  | 0x4F |



## Modifier Keys
### These are Not standard HID Keycodes to send, instead they are Key Modifiers and must be sent as such.
| Key  | Hex Code |
| ------------- | ------------- |
| Left Control  | 0x01  |
| Left Shift  | 0x02  |
| Left Alt  | 0x04  |
| Left Windows  | 0x08  |
| Right Control  | 0x10 |
| Right Shift  | 0x20  |
| Right Alt  | 0x40  |
| Right Windows  | 0x80  |

## Other Keys
### Keys that were not listed yet

| Key  | Decimal HID Code | Hex HID Code |
| ------------- | ------------- | ------------- |
| ^  | 53  | 0x35 |
| +  | 48  | 0x30 |
| #  | 49  | 0x31 |
| -  | 56  | 0x38 |
| .  | 55  | 0x37 |
| ,  | 54  | 0x36 |
| <  | 3  | 0x03 |
| ´  | 46  | 0x2E |




