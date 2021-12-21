# important jekyll variables:
1. page.url -- gives the url of current site
2. site.data.navigation -- all navigation elements specified in the _data/navigation.yml
3. site.posts -- has all posts that are written in the _posts/ folder
4. While rendering posts in a blog.html
    - post.url is auto generate dby Jekyll
    - post.title is pulled from the filename/front matter
    - post.excerpt is first para in the content 
5. site.authors -- has all authors in the _authors folder
