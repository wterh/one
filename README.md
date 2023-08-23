# One - The single file Blog

"One" consists of one single file that contains everything you need to create and manage your blog. Imagine you want a simple blog, without extra features, settings and fiddly stuff,
a homepage, a list of posts, likes, views or anything like that - and you just want to share information. Then One is the perfect option for you. "One" is a blog and a dashboard in one.

Note that "One" is mostly an experimental tool designed to make it quick and easy to organize the distribution of information.

## Features
- [x] Administration panel
- [ ] SEO friendly
- [ ] Large configurations
- [ ] Import / Export posts
- [ ] Endless post viewer
- [ ] Supports multiple methods of information storage
- [ ] Localization
- [ ] Views
- [ ] Likes
- [ ] Comments
- [ ] Share

## Technology & requirements

"One" is a website that contains some PHP and JavaScript code that allows you to create, manage and view blog posts.

### Server requirements

- PHP 5+
- Write permisions for PHP on the file (0755)

### Client requirements

- Any Web browser (Desktop, Tablet, Phone)

## Installation

To install "One", simply copy it to a directory at the root of your site.

After that, launch "One" (https://sitename.com/).

Now you see the Home Page with your simple and personalized blog. To open the admin panel, just go to:

`Apache` - https://sitename.com/?admin

`Nginx` - https://sitename.com/admin

For Nginx you need to specify a location leading all requests to "One"
```nginx
location / {
         index index.php index.html;
         try_files $uri $uri/ /index.php?$args;
}
```

On first launch you will see the "One" configurator, it will help you customize your blog to your needs.
