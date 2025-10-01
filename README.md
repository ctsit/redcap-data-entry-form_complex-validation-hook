# REDCap Complex Validation Hook - ARCHIVED

**This repository has been archived and is no longer actively maintained.**

This project was archived as of October 1, 2025. The project for which it was written is now over. There's no funding to provide further maintenance for other projects. Please don't hesitate to use this code in accordance with the license; however, the authors are unable to offer any additional support.

-----------


Allows for the addition of valid options outside of the min-max range for
a REDCap form field.

For example, if the question were something like "In which month was the
subject born?" The field note could read "1-12, or 88 if unknown." Simply
use the 1-12 range and decorate additional valid options in the Note like
this:

    1-12, or <span class=valid>88</span> if unknown.

