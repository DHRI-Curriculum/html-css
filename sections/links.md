[<<<Back](p_and_h.md) | [Next>>>](images.md)

# Links

Links are the foundation of the world wide web, and so are an important component of most websites. By hyperlinking text, you can move between the different webpages on your site (sometimes in the form of a menu or navigation bar), or connect to other resources or information on other websites.

The `<a>` tag, or **anchor tag**, creates the link to another document. You can use the `<a>` tag to link to other documents or webpages you created for the same site or to documents or webpages created by other web users. 

## Option 1: Relative Links

Relative links take the current page as an origin point and search for files relative to that location. This method is useful for creating links to pages within your own site.

The following appears as a link to the `about.html` page in the same folder as `index.html`:

	<a href="about.html">About</a>

On your webpage it will appear as:

[About](about.html)  

This link is asking the browser to look for a file titled `about.html` in the same folder. If a file named `about.html` is not in the same folder, clicking the link will result in a `404 -Page Not Found` error.

## Option 2: Absolute Links

An absolute link includes information that allows the browser to file resources on other websites. This information includes the site domain—such as `google.com`—and often the protocol—such as `http` or `https`.

	<a href="http://www.google.com">Google</a>

On your webpage it will appear as:

<a href="http://www.google.com">Google </a>

This pathway is directing your browser to look online for this text document at the URL address provided.

## More on Links

Each example above includes an `href` tag. The `href` tag, short for hypertext reference, is an example of an **attribute**. Attributes offer secondary information about an element.

The `<a>` tag, or anchor tag, creates a link. The text within the `<a>` and `</a>` tags, the anchor text, is what a visitor to the site will see and can click on. The `href=` attribute tells the browser where the user should be directed when they click the link.

There is another technical difference between the two options above.

## When to Use Relative Versus Absolute Links

Use relative links when referring to pages on your own site. The main advantage of using relative links to pages on your site is that your site will not break if it is moved to a different folder or environment.

## Activity

1. In your `index.html` file, add a relative link to your About page. 
2. Also add a relative link from your `About page` to your `index.html` page. In your link, call this page `Home` (Reminder: `index.html` is the homepage)
3. Lastly, include an absolute link to a page of your choosing. Remember that an absolute link includes the protocol (for example, `http:`) and also a domain (for example, `cuny.edu`).

	http://cuny.edu/about

4. Re-save your text files and reopen or refresh them in your browser. 

## Check if it worked!
When your pages are updated, you should be able to toggle back and forth between the pages of your website, and navigate to the external webpage. 

[<<<Back](p_and_h.md) | [Next>>>](images.md)