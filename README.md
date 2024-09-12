# helix-eiffel-theme

Eiffel is a light theme for the [Helix editor](https://helix-editor.com/), inspired by the theme of the same name that shipped in Sublime Text 1-3.

|Normal mode|Visual mode|Insert mode|
|---|---|---|
|![image](https://github.com/user-attachments/assets/ef6c30c8-968f-4aff-9aa4-bbe2bb239dfc)|![image](https://github.com/user-attachments/assets/72813baa-4972-4474-9314-77fa99e3904b)|![image](https://github.com/user-attachments/assets/178b3f60-73ea-4a14-a50d-c59b534d010a)|

## Notes

The old Sublime versions were surprisingly bad at applying their own TextMate themes, so I targeted the way that the original Eiffel actually looked in use rather than the way it was defined in [the tmTheme file](https://github.com/SublimeText/LegacyColorSchemes/blob/master/Eiffel.tmTheme). 

Also, beyond fixing tmTheme/helix impedance mismatches I tweaked the theme to suit my own taste:
* Local variables now look like function arguments since they're often semantically indistinguishable.
* Members all look the same since (in languages with first-class functions) methods and member variables are often semantically indistinguishable.
* Only keywords and operators remain bolded (for readability).
