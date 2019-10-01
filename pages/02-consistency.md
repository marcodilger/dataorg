---
layout: page
title: Be consistent
description: "Data organization: Be consistent"
---

# Be consistent

The first rule of data organization is *be consistent*.

- **Use consistent codes for categorical variables.** For a
    categorical variable like *sex*, use a single common value for
    males (e.g. "`male`") and a single common value for females
    (e.g. "`female`").

- **Use a single fixed code for any missing values.** Most prefer "NA", but also other possibilities, e.g. "-". Definitely don't use a numeric value like
    `-999` or `999`; Also, don't insert a note in place of the data,
    explaining why it's missing. Rather, make a separate column with
    such notes.

---

- **Use consistent variable IDs.** If sometimes it's "`153`" and
    sometimes "`mouse153`" and sometimes "`mouse-153F`" and sometimes
    "`Mouse153`", there's going to be extra work to figure out who's
    who.

- **Use a common data layout in multiple files.** If your data are in
    multiple files, use the same layout in all files. (More on layout
    [here](rectangle.html).)



- **Be careful about extra spaces within cells.** A blank cell is
    different than a cell that contains a single space. And "`male`"
    is different from "` male `" (that is, with spaces at the
    beginning and end). These can be a headache later on.

