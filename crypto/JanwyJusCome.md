# JanwyJusCome 

![jj](../files/jj.png)

form the challenge discription "What constitutes What?, Why is Why?. Your curiosity never bothers you" we could see that the [file ](https://github.com/hamza34-del/abcctf/blob/main/files/JawnyJusCome)

```
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJmbGFnIjoiSjBueUdldHNUSDNGbDRHIiwidXNlciI6IkhheSBCZWUgQ0NURiIsImV4cCI6MjAwNTAzMzQ5M30.Gn5MzwKtGi4WBpmCyF401el0KVNIP4Lv1UypFEhv_Bo
```

contains some cipher text with some embeddings in it 

using dcode to analyze it we see that its a base64 encoding 

![jj2](../files/jj2.png)

looking further at the decrypted base64 encoding we found out its a jwt (known as javascript web token)

extracting the flag from the token we have **abcctf{J0nyGetsTH3Fl4G}**
