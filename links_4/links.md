# Links

- Creating links between pages
- Linking to other sites
- Email links

You will commonly come across the following types of links:

- Links from one website to another
- Links from one page to another on the same website
- Links from one part of a web page to another part of the same page
- Links that open in a new browser window
- Links that start up your email program and address a new email to someone

## Writing Links

Links are created using the ```<a></a>``` element. User can click on anything between the opening tag and the closing tag. You specify which page you want to link to using the href attribute.

```
<a href="http://www.imdb.com">IMDB</a>
```

## Linking to other sites

When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL.

### Absolute URLS

URL stands for Uniform Resource Locator. An absolute URL starts with the domain name for that site, and can be followed by the path to a specific page. If no page is specified, the site will display the homepage.

## Linking to other pages on the same site

```
<p>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about-us.html">About</a></li>
        <li><a href="movies.html">Movies</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</p>
```

When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.

### Relative URLS

Help when building a site on the computer because you can create links between pages without having to set up your domain name or hosting.

## Directory Structure