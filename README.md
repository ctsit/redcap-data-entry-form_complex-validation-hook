# REDCap Complex Validation Hook

Allows for the addition of valid options outside of the min-max range for
a REDCap form field.

For example, if the question were something like "In which month was the
subject born?" The field note could read "1-12, or 88 if unknown." Simply
use the 1-12 range and decorate additional valid options in the Note like
this:

    1-12, or <span class=valid>88</span> if unknown.

