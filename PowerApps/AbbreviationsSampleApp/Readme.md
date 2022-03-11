# AbbreviationsSampleApp sample App 

Contains demonstration code of how to based on User input create Abbrevations from the first letters of words.

### [Link to recording](https://youtu.be/WtKTWcMX5Uc)

### [Link to Sample App](https://github.com/365CornerDavid/PowerPlatform/blob/master/PowerApps/AbbreviationsSampleApp/Abbreviations.msapp)

Convering functions:
* Split
* With
* ForAll
* Concat


 
![Image with PowerApps tip for abbreviations](https://github.com/365CornerDavid/PowerPlatform/blob/master/PowerApps/AbbreviationsSampleApp/Abbreviations.png "Image with PowerApps tip for abbreviations")

Key formula of the whole idea:

```powerapps
With({
        _vWORDS: Split(txtSingle.Text," ")},
    Upper(
        Concat(
            ForAll(
                _vWORDS As WORD,
                First(
                    Split(WORD.Result,"")
                ).Result
            ),
            Value,
            ""
        )
    )
)
```

### [Link to recording](https://youtu.be/WtKTWcMX5Uc)
