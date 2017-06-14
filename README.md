This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

This project was inspired by awesome [ssr-create-react-app-v2](github.com/ayroblu/ssr-create-react-app-v2) and powerful [react-redux-universal-hot-example](https://github.com/erikras/react-redux-universal-hot-example)

I recently use [ssr-create-react-app-v2](github.com/ayroblu/ssr-create-react-app-v2) but got stuck in the fact that it's difficult to make customized configurations (and also the repo seems to be not active). So I came up with an idea to develop 'another' boilerplate. And, here it is!

This boilerplate is similar as [ssr-create-react-app-v2](github.com/ayroblu/ssr-create-react-app-v2) which was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). The difference is that I ejected the CRA so I can use my own custom configurations (though it's not recommended).

Install dependencies:
```
yarn install
```

Run SSR in development:
```
yarn run build && yarn run start:server
```

Run SSR in production:
```
yarn run build && yarn run now-start
```

Run in development (No SSR):
```
yarn start
```

PWA
By default, the PWA feature is active. But if you don't want to use it, you can deactivate it in `src/index.js` by removing `registerServiceWorker()` function. 

SSR
SSR is not available in if you run `yarn start`. It's only available if you run `yarn run build && yarn run start:server` or `yarn build && yarn run now-start`.

Hot Reload
Hot reload is only supported if you run `npm start`.

Notice that this boilerplate uses some codes from [ssr-create-react-app-v2](github.com/ayroblu/ssr-create-react-app-v2) and [react-redux-universal-hot-example](https://github.com/erikras/react-redux-universal-hot-example) without any commercial purpose.

But please do let me know if this meets `copyright infringement`!

If you have any idea to improve this boilerplate, especially to solve the limitation that this boilerplate has, please feel free to contribute! Thanks.