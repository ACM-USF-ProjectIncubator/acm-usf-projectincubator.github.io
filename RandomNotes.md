# What is this file for?
This is just an info dump of what I've figured out in the processing of reading the HTML5 Up code. Being able to understand and learn from other people's code is a really important skill, so I thought it'd be useful to document that process as well.

# Info Dump
- What is sass?
    - Syntactically Awesome Style Sheets (SASS)
        - A popular CSS pre-processor (eventually gets compiled to CSS)
        - Easier to maintain than CSS for a multitude of reasons (Eg. nesting that allows it to more closely mirror HTML code)

- What is breakpoints?
    - Since the website is fully responsive, it seems to encode the thresholds of sizes before the new layout is set (Mobile would have a different website layout than desktop)

- Do we need all these files?
    - I'm not sure if I have a use for the dropdown menu, but we'll see!

# Website Planning
- What general properties do I want my website to have?
    - If I'm a student:
        * Personal Projects (Put in boxes)
        * Internships?
        * About Me
        * Contact details (Icon + link to social media)

    - If I'm a club organisation:
        * Upcoming events (Put in boxes)
        * Previous events (Put in boxes)
        * Board members? (Put in boxes)
        * About Us
        * Contact details (Icon + link to social media)

- I don't think I'll be using dropdowns or sidebars? I should remove references to these from the index.html page

# Order of Editing
1. Fix the logos (index.html, no-sidebar.html) to say "ACM USF" instead of Verti
    * Will also change logo colour to be USF green
2. Deleted left-sidebar.html, right-sidebar.html because I won't be using them