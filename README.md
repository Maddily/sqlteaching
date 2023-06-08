# sqlteaching

### [Re-design](#re-design-1)

SQL Teaching is an interactive tutorial for learning SQL. It is available on http://www.sqlteaching.com

SQL Teaching is MIT licensed - see the LICENSE file for more details.

It's easy to contribute levels to SQL Teaching.

The sqlteaching.js file contains a variable called _levels_.

This variable has the prompts and answers for each level.

It is an array of dictionaries (the order of the levels). In each dictionary, there are the following keys:

- name: name shown on web page
- short_name: identifier added to the URL
- database_type: is passed into the load_database function, in order to determine the tables loaded
- answer: the query that the user writes must return data that matches this value
- prompt: what is shown to the user in that web page

And the following keys are optional:

- required: Extra validation in the form of case-insensitive required strings
- custom_error_message: If the validation fails, show this error message to the user

## Re-design

Alvaro Cervan came across this site as part of an open source Full Stack Web Development course, [The Odin Project](https://www.theodinproject.com/dashboard).

He loved this SQL interactive tutorial; it is by far the best resource that he has found. It is totally interactive and provides query examples with live results.

However, the UI looked **very** dated. In fact, when checking the commits, some are from 9 years ago, which explains this issue.

He then started a project to update the UI, redesign its structure, and add support for smaller devices.

> Updated design using [Pico.css](https://picocss.com/)

> Re-design done by [Alvaro Cervan](https://github.com/JackGraymer)

<details> 
<summary>Screenshots</summary>

### Old version

#### Desktop

![Image of Old Version](/img/Old-version.png "Old version image")

#### Phone

![Image of Old Phone view](/img/Old-phone.png "Old Phone view  image")

### New Version

#### Desktop

![Image of New Version](/img/New-version.png "New version view image")

#### Phone

![Image of New Phone view](/img/New-phone.png "New phone view image")

</details>
