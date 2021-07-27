### Troubleshooting failed deployment
Deploying Heroku with Webpack: [https://www.pluralsight.com/guides/deploying-to-heroku-with-webpack](https://www.pluralsight.com/guides/deploying-to-heroku-with-webpack)
Dev mode script conflicts: [https://github.com/Shopify/shopify-node-app/issues/86](https://github.com/Shopify/shopify-node-app/issues/86)

### Node.js deployment tutorials
Deploying Node.js / MongoDB app to Heroku: [https://medium.com/make-school/how-to-deploy-your-node-js-mongodb-app-to-the-web-using-heroku-63d4bccf2675](https://medium.com/make-school/how-to-deploy-your-node-js-mongodb-app-to-the-web-using-heroku-63d4bccf2675)
Official Heroku documentation: [https://devcenter.heroku.com/articles/deploying-nodejs](https://devcenter.heroku.com/articles/deploying-nodejs)
Step by step guide: [https://www.geeksforgeeks.org/deploying-node-applications/](https://www.geeksforgeeks.org/deploying-node-applications/)

### Procedure
1. Ensure you have a `package.json` file
2. Ensure `package.json` contains your app's Node.js version here:
  ```
  "engines": {
    "node": "14.x"
  }
  ```
3. Run your app locally using `heroku local web` to ensure it runs properly
4. Run the command `heroku login` to sign in
5. Run `heroku create` to make a new Heroku repo that will be pushed
6. Push the repo to Heroku with `git push heroku main` (no other branches will work)