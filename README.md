# NTLM-Challenge-Decoder
Python script for decoding NTLM Challenge and retrieving metadata.

> :warning: This python script is a fork of this Github gist : https://gist.github.com/aseering/829a2270b72345a1dc42

## Install
````bash
git clone https://github.com/Cyber-Courses/NTLM-Challenge-Decoder.git
cd NTLM-Challenge-Decoder
````

## Use
````bash
echo "TlRMTVNTUAACAAAACgAKADgAAAAFgooCBqqVKFrKPCMAAAAAAAAAAEgASABCAAAABgOAJQAAAA9JAEkAUwAwADEAAgAKAEkASQBTADAAMQABAAoASQBJAFMAMAAxAAQACgBJAEkAUwAwADEAAwAKAEkASQBTADAAMQAHAAgAHwMI0VPy1QEAAAAA" | ./ntlm_challenge_decoder.py
````

## Sample 
````bash
"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"
````
