# OCMOD pretty URL

Generates nice URLs from information, category, manufacturer and product pages.

There is no need to setup anything in OpenCart other than the install process.

URLs are generated from names (including spaces) and handle duplicate categories (it checks parent ID of each category).

Products have the following format: `{product_id}-{model}`

## Warning
- This replaces the entire default `seo_url.php` file.
- This probably won't be compatible with any other URL related extension.
- I think there might be one sql injection point which I'll fix later (hopefully). I mean ... there might be more of them since OC doesn't use prepared statements(!)

## Installation
- put both `install.xml` and `build.sh` files into one directory
- run `build.sh` (or just create an ocmod zip file and put the `install.xml` in there)
- install like any other extension
- refresh modification cache
- enable `SEO URLs`

## Motivation
I wasn't able to find an extension that would do this. I spent around $60 for the (for me) useless software and I'm not planning to spend more.

## Donations
Bitcoin: bc1qxrt0antzzxf9avj9mnglfeu5rs5pvlel29yacl
