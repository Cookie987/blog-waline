# Waline Example

This directory is a brief example of a [Waline](https://waline.js.org/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Waline project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/walinejs/waline/tree/main/example)

### How We Created This Example

```js
//index.js
const Waline = require('@waline/vercel');
module.exports = Waline();

//vercel.json
{
  "builds": [
    {
      "src": "index.js",
      "use": "@vercel/node"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "index.js"
    }
  ]
}
```

### Deploying From Your Terminal

You can deploy your new Waline project with a single command from your terminal using [Vercel CLI](https://vercel.com/download):

```shell
$ vercel
```
Update at 2022年11月30日

Update at 2022年12月29日

Update at 2023年3月19日

Update at 2023年11月4日

Update at 2024年2月18日 21点44分

Update Node.js to 18 at 2023年11月4日

Update at 2024年1月20日 18点31分

Update at 2024年4月3日 19点48分
