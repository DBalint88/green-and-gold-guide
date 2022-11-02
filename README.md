# green-and-gold-guide
An HTML re-factoring of Hamden High School's student handbook.

A lot needs to go into this project.

The primary purpose of this is to make the student handbook more accessible, both in the sense that students will actually read it and reference it, and also in the sense that student with disabilities will even be ABLE to do so.

In its current form, student handbook exists as a slideshow in Google Slides.  Much of the information is contained in static images and/or rotated sideways just to fit on the page.  This presents a number of difficulties:
    1. The handbook is essentially only accessible on a laptop or desktop computer, and we all know that kids primarily browse things on their phones.
    2. It has to be viewed through Google Slides, a further impediment to mobile access.
    3. Much of the information cannot be highlighted for Copy/Paste.
    4. Much of the information can't be translated to different languages through the typical use of the Google Translate extension.
    5. None of the information can be scaled for vision-impaired users.
    6. ALL of the information is invisible to screen readers but the blind.
    7. The information is not indexed, and so users must search the entire document trying to find the one thing they're looking for.  The result is that they just don't use it.

All of this can be resolved through the creation of a simple webpage with some basic scripting and accessibility-minded styling rules.  In addition to resolving all of the issues above:
    1. Set media queries for access on mobile
    2. Encode the actual information vs static images
    3. Style correctly for accessibility purposes, including proper use of font scaling, color contrast, and screen readers
    properly indix the information

... it would also be helpful to script certain sections of information, particularly the "who's my administrator page and the graduation requirements checklist.  These currently require students to navigate confusing charts, when really they should just be able to input some basic information and get a result.  Again, all on their phone.

    4. Script administrator query
    5. Script graduation requirement checklist.
