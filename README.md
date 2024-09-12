# helix-eiffel-theme

Eiffel is a light theme for the [Helix editor](https://helix-editor.com/), inspired by the theme of the same name that shipped in Sublime Text 1-3.

## Screenshots

|Visual mode|Insert mode|
|---|---|
|![image](https://github.com/user-attachments/assets/72813baa-4972-4474-9314-77fa99e3904b)|![image](https://github.com/user-attachments/assets/178b3f60-73ea-4a14-a50d-c59b534d010a)|

## Notes

The old Sublime versions were surprisingly bad at applying their own TextMate themes, so I targeted the way that the original Eiffel actually looked in use rather than the way it was defined in [the tmTheme file](https://github.com/SublimeText/LegacyColorSchemes/blob/master/Eiffel.tmTheme). 

It's not possible to get an exact 1:1 mapping to Helix themes so I changed some things to fit. 

Finally, I tweaked the resulting theme to suit my own taste:
* Class definitions now look like class references to help you visually match them.
* Local variables now look like function arguments since they're often semantically indistinguishable.
* Members all look the same since (in languages with first-class functions) methods and member variables are often semantically indistinguishable.
* Only keywords and operators remain bolded (for readability).
