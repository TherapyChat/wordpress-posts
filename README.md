[![Build status](https://travis-ci.org/TherapyChat/wordpress-posts.svg?branch=master)](https://travis-ci.org/TherapyChat/wordpress-posts)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/therapychat/wordpress-posts)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com)

# \<wordpress-posts\>

Polymer element to show Wordpress posts

Intall:
```bash
bower install -S wordpress-posts
```

Example of use:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wordpress-posts.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wordpress-posts
  url="https://wordpress.org/news"
  max="4"
  category-names="development, documentation"
></wordpress-posts>
```

## Documentation

Checkout the [webcomponents page](https://www.webcomponents.org/element/therapychat/wordpress-posts).

## Changelog

See [CHANGELOG](./CHANGELOG.md) file.

## Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) file to follow good practices.

You will need [NodeJS](https://nodejs.org).

1. Close the repo: `git clone git@github.com:TherapyChat/wordpress-posts.git`
2. Install dependencies: `npm install`
3. Code!
4. Test: `npm test`
5. Create a [Pull Request](https://github.com/therapychat/wordpress-posts/pulls)

### Contributors

- [Alberto Fernandez](http://twitter.com/albertofdzm)

## License

Edge is available under the `Apache License 2.0`. See the [LICENSE](./LICENSE) file for more info.
