Node 14

npm init: initialization for package.json
npm install cypress --save-dev: install cypress
npx cypress open : open cypress dashboard


cypress.json: untuk config
package.json: dependencies
fixtures: jika butuh file sebagai penunjang test (files for upload)
plugins: untuk load cucumber yang dipakai, 
support: 

//Run
npx cypress open

cy.get: dapatkan locator
cy.contains: dapatkan text
cy.root: tag pertama html

//Cucumber
npm install cypress-cucumber-preprocessor --save-dev
npm install multiple-cucumber-html-reporter --save-dev


regextester.com : untuk liat format cucumber
(.+) . semua karakter, + jumlahnya lebih dari 1
(\w+) w worlds, + jumlahnya lebih dari 1
# comment di features file

https://codeshare.io
share code

  "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1"
  },


npm test -- --browser chrome : run semua feature


https://github.com/hanifahatiya/cypress-koligrum.git


