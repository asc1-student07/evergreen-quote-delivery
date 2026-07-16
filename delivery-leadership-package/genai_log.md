## Github Copilot change

1. AI Agent to add testimonials
Prompt:

>in the testimonials section of this html file, can you auto generate two more entries that follow the tone and length of the three provided?  Also, make sure the additional entries retain the same responsive design as what is there now.  If you have any questions, ask me one at a time and don't build anything based on assumption.

Copilot, in one pass, created two more on-tone testimonial cards that matched the style of what was there and kept the responsivess of the site. In testing, no issue where found

2. AI Agent to review CI run errors
Prompt:

>I'm getting these results as part of a github actions workflow (you can read this in .github/workflows/ci.yml):  
Validate site: index.html#L88  
Expected omitted end tag <input> instead of self-closing element <input/>  
Validate site: index.html#L69  
Expected omitted end tag <input> instead of self-closing element <input/>  
Validate site: index.html#L64  
Expected omitted end tag <input> instead of self-closing element <input/>  
Validate site: index.html#L13  
Expected omitted end tag <link> instead of self-closing element <link/>  
Validate site: index.html#L10  
Expected omitted end tag <link> instead of self-closing element <link/>  
Validate site: index.html#L6  
Expected omitted end tag <meta> instead of self-closing element <meta/>  
Validate site: index.html#L5  
Expected omitted end tag <meta> instead of self-closing element <meta/>  
Validate site  
Node.js 20 is deprecated. The following actions target Node.js 20 but are being forced to run on Node.js 24: actions/checkout@v4, actions/setup-node@v4. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/  

Again, in a single prompt, the agent correctly identified and fix all errors from the CI run, including know which version and action to use for Node.