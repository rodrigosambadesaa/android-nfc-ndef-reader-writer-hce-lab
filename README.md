# NFC NDEF Reader / Writer / HCE Lab

Original educational reimplementation of three NFC roles in one app:

- **Reader mode**: discovers tags and decodes NDEF text/URI records.
- **Writer**: writes a small NDEF text record to a writable NDEF tag.
- **Host Card Emulation**: exposes a demo ISO-DEP AID (`F0010203040506`) and answers SELECT APDUs from another NFC reader.

The project uses only Android platform NFC APIs. A physical NFC-capable Android device is required; HCE also depends on device support. Do not use the demo AID/protocol for payment, identity, access control, or secrets.
