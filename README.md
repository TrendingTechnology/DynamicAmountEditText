# DynamicAmountEditText [![API](https://img.shields.io/badge/API-16%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=16)

Customizable `EditText` with runtime amount formatting. There's nothing extra. Supports different separator's types.

Features:
- Extended from EditText, so you can use it like regular EditText f.e. with TextInputLayout
- Formatting occurs in runtime
- You can change decimal separator, decimal part length, grouping separator
- Cases with insert from clipboard was processed, as a result, you can't paste incorrect values. From pasted data will be select correct parts only 

Project sample is above.

# Work example
![](/images/video-2020-08-23-13-21-13.gif)

# View params.

| Parameter | def. value | description |
| ------------- | ------------- | ------------- |
| `decimalSeparator`  | ',' | Separator of integer and fractional part |
| `decimalPartLength`  | 2  | Max decimal part length |
| `isSeparatorCutInvalidDecimalLength`  | false | If false, input separator in position (string length - decimalPartLength) will be forbid. If true, you can put separator to any string's position, but excess decimal part will be cut off  |
| `GROUPING_SEPARATOR`  |  ' ' | Discharge separator of integer part  |

