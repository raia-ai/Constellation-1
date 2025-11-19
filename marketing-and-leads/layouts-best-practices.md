# Layouts Best Practices | Constellation1 Customer Hub

**Best Practice: Make JavaScript and CS:S external:**

1\. Reusability: When the code is separated out, it can be reused by other layouts/code files if applicable. This makes the code reusable which leads to less overall code.

2\. Maintainability: When the code is referenced, it tends to be easier to maintain since the code is stand alone. With duplicate code in multiple layouts, you have to deal with double the maintenance if a change needs to occur. 3. Decreased page size: When you link to a CSS/JS file versus including that raw markup in the layout, you reduce the overall page size where the layout is rendered. A smaller page size is recommended from an SEO standpoint.

4\. Faster Load time: Related to #3, any time the page size is smaller, you’ll see a faster page load time. This is important for user experience and SEO.

**Validate markup syntax:**

Description: When adding new HTML/JS/CSS to a layout, make sure you validate the syntax and structure of the code using a validator tool. This will ensure you conforming to the w3c best practices. Example: [http://validator.w3.org/#validate\_by\_input](http://validator.w3.org/#validate_by_input)

**Best Practice: (JS/CSS) - Link to local repository version of source code:**

&#x20;      Often times, you may have the need to embed an open source JavaScript/CSS file into the layouts. This is quite common as there are a number of open source frameworks available to the public to make the development of custom controls a little bit easier. An example of this can be seen when using jQuery/Twitter Bootstrap framework files. Many times, these files come from publicly accessible repositories like GitHub. Rather than linking directly to the public network source code file, the best practice here is to take a copy of the source code found at that time, upload it as a content file in the website admin tool, and link to this file in the layouts. The primary reason to do this is because the open source development community can often make code changes to these public files that could have a negative impact on the client who is consuming the code. This could result in a breaking change. For more instruction on how to add content files and reference them in layouts, please refer to the section on “How to: Make JavaScript and CSS external.”

**Best Practice: Create a new Version:**

Anytime you modify a layout, make sure you create a new version of the layout first. This will allow you to preserve history and also rollback to a previous version should a change cause unforeseen errors.

**Best Practice: Document change history:**

When you’re modifying an existing layout or creating a new version, it’s a good practice to get in the habit of documenting the change history of what is being changed. Use the description field to note what the change was, who changed it, and the date it changed.
