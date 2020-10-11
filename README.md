# typescript-bootstrap

Use the following commands in a new project directory:

```
# Install Yarn
# https://yarnpkg.com/getting-started/install
npm install -g yarn
yarn set version berry
yarn init

# Install TypeScript
yarn add typescript --dev

# Install Prettier
# TODO: use fork
# "git+ssh://git@github.com/btmills/prettier"
yarn add prettier --dev
yarn add @yarnpkg/pnpify --dev
yarn pnpify --sdk vscode

# Install ESLint
yarn add eslint --dev
yarn add eslint-plugin-import --dev
yarn add eslint-import-resolver-node --dev
yarn add eslint-config-airbnb-typescript --dev
yarn add eslint-config-prettier --dev
yarn add @typescript-eslint/eslint-plugin --dev
yarn add @typescript-eslint/parser --dev
