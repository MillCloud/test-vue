# test-vue

English | [简体中文](./README.zh-Hans.md)

---

A repo for testing vue.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

- Using nvm, node lts, npm lts and yarn is recommended.
  - Install nvm first
    - [nvm for Mac/Linux](https://github.com/nvm-sh/nvm#readme)
    - [nvm-windows](https://github.com/coreybutler/nvm-windows#readme) - [known issue #300](https://github.com/coreybutler/nvm-windows/issues/300)
  - Install node lts in terminal / command line
  - Globally update npm to lts and install yarn

    ```sh
    npm i -g npm@lts
    npm i -g yarn
    ```

  - Mirrors are set by default for Chinese users
- Git is also required.
  - [git for Windows/Linux](https://git-scm.com/downloads)
  - It is recommended to use [Homebrew](https://brew.sh/) to install git on Mac

### Installing

```sh
# clone
git clone git@github.com:MillCloud/test-vue.git

# enter the directory
cd test-vue

# install dependency
yarn

# build for development
yarn dev

# build for staging
yarn build:staging

# build for production
yarn build

# lint scripts, styles and ls
yarn lint

# check deps
yarn run check

# git commit and git push
# git add should be handled by yourself
yarn commit
```

## Running the tests

No tests now. Pull requests are welcome.

## Deployment

- Make sure everything related to [modes and environment variables](https://cli.vuejs.org/guide/mode-and-env.html) is fine.
- Run `yarn build:staging` for staging and run `yarn build` for production, then put the contents of the `dist` folder on the server.
- Report will be generated by default.

## Built With

- [vue](https://vuejs.org)
- [vue-cli](https://cli.vuejs.org/)
- [vue-router](https://router.vuejs.org/)
- [vuex](https://vuex.vuejs.org/)
- [vue-composition-api](https://composition-api.vuejs.org/)
- [vue-i18n](https://kazupon.github.io/vue-i18n/)
- [axios](https://github.com/axios/axios#readme)
- [swrv](https://github.com/Kong/swrv#readme)
- [ress](https://ress-css.surge.sh/)
- [element-ui-eoi](https://github.com/ElemeFE/element/pull/19081)
- [vuetify](https://vuetifyjs.com/en/)
- [tailwindcss](https://tailwindcss.com/)
- [vxe-table](https://github.com/x-extends/vxe-table#readme)
- [vxe-table-plugin-element](https://github.com/x-extends/vxe-table-plugin-element#readme)
- [vue-echarts](https://github.com/ecomfe/vue-echarts#readme)
- [lodash](https://lodash.com/)
- [xe-utils](https://github.com/x-extends/xe-utils#readme)
- [dayjs](https://day.js.org)
- [nprogress](https://ricostacruz.com/nprogress/)
- [mock.js](http://mockjs.com/)
- [vue-clipboard2](https://vue-clipboard2.inndy.tw/)
- [vue-lazyload](https://github.com/hilongjw/vue-lazyload#readme)
- [vue-virtual-scroll-list](https://github.com/tangbc/vue-virtual-scroll-list#readme)
- [portal-vue](https://portal-vue.linusb.org/)
- [screenfull](https://github.com/sindresorhus/screenfull.js/#readme)
- [sass](https://sass-lang.com/) - using [node-sass](https://github.com/sass/node-sass#readme) here
- [commitlint](https://commitlint.js.org/)
- [commitizen](http://commitizen.github.io/cz-cli/)
- [prettier](https://prettier.io/)
- [eslint](https://eslint.org/)
- [stylelint](https://stylelint.io/)
- [ls-lint](https://ls-lint.org/)
- [husky](https://github.com/typicode/husky#readme)
- [lint-staged](https://github.com/okonet/lint-staged#readme)
- [npm-check-updates](https://github.com/raineorshine/npm-check-updates#readme)

## Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) for details on code of conduct, and the process for submitting pull requests.

## Authors

- **Rui Wu** - *Initial work* - [ModyQyW](https://github.com/ModyQyW)

See also the list of [contributors](https://github.com/MillCloud/test-vue/contributors) who participated in this project.
