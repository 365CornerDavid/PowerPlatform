#AbbreviationsSampleApp sample App 

Contains demonstration code of how to based on User input create Abbrevations from the first letters of words.
Convering functions:
* Split
* With
* ForAll
* Concat

### [Link to recording](https://youtu.be/WtKTWcMX5Uc)


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
