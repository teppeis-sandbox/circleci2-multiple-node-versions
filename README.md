circleci2-multiple-node-versions
====
Sample project to build with multiple Node.js versions in CircleCI 2.0

[![build status][circleci-image]][circleci-url]
![Node.js Version Support][node-version]

Foo!!!

## How to use

1. [Add your project to CircleCI](https://circleci.com/docs/2.0/first-steps/)
2. Open your project settings in CircleCI
    1. Add a new "API Permissions" (scope: `All`, label: any) and copy the token
    2. Add two new "Environment Variables"
        - name: `CIRCLE_API_TOKEN`, value: added API permission token
        - name: `CIRCLE_CACHE_VERSION`, value: 1
3. Rebuild

## License

MIT License: Teppei Sato &lt;teppeis@gmail.com&gt;

[circleci-image]: https://circleci.com/gh/teppeis-sandbox/circleci2-multiple-node-versions.svg?style=svg
[circleci-url]: https://circleci.com/gh/teppeis-sandbox/circleci2-multiple-node-versions
[node-version]: https://img.shields.io/badge/Node.js%20support-v4,v6,v7-brightgreen.svg
