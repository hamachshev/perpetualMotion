Note:
When copying in the values folder's files, please ensure that you end up in your project with only one copy of the string:
    <string name="dp_level">base</string>

Depending on what you have, you might have this string in either or both of strings.xml or dimens.xml.
Please make sure it's in only one of those.

Also, if you copy in the colors.xml then you will lose your colors. The themes, however, is generic.

Finally, since the template includes the fab_margin dimension, please make sure you have that in your regular values folder.
As in:
     <dimen name="fab_margin">16dp</dimen>
