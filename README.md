# react-lab

npm init npm install --save react
npm install --save react-dom
npm install --save-dev webpack
npm install webpack-dev-server -g
npm install -g webpack

#If peer dependency error occurs
rm -rf node_modules/
sudo npm update -g npm
npm install

npm install --save-dev babel-loader
npm install --save-dev babel-core
npm install --save-dev babel-preset-es2015
npm install --save-dev babel-preset-react

#start dev-server using
npm run dev

#start compile
npm run start

#webpage is at 0.0.0.0:8082/webpack-dev-server/dist/index.html
