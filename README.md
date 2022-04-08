# HW_week1_AKW
 Week 1s homework assignment


# 01 HTML, CSS, and Git: Code Refactor

## My Task



**Refactoring** I set out to make this Website more accsessible to those who need it. My goal was to not change the website itself, but make it easier for screen readers to understand what is going on. By adding things like \<navs> and \<headers> into our semantic html, it becomes much easier to navigate webpages with visual or similar impairments. 

### Original HTML

``` html
<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>


### Modified HTML

```

### Modified HTML

``` html

<!-- add header selector -->
    <header>
        <h1>
            <!-- used em selector -->
            Hori<em class="seo">seo</em>n
        </h1>
<!-- add nav selector -->
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
```
This simple change will help show the user where they are on the page and they will probably know they can find helpful links to the rest of the wepage. 

My sources for research include 
- [GitHub Pages](https://pages.github.com/).

- [Mozilla Developer Network ](https://developer.mozilla.org/en-US/).

-  [W3 Schools](https://www.w3schools.com/) 

