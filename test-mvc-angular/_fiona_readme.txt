# test-core2.1-mvc-angular6

1)Project settings:
- .NET Core 2.1 + API 
- Refer to this tutorial: http://www.talkingdotnet.com/how-to-create-an-angular-6-app-with-visual-studio-2017/

——————————————————————————————————————————————————————
Updates:

==========================
#(1) Add component [navbar]
#(1.1)
@CMD ==> C:\projects\test-mvc-angular\test-mvc-angular
>ng generate component navbar

==========================
#(2) Add Bootstrap
Reference: https://loiane.com/2017/08/how-to-add-bootstrap-to-an-angular-cli-project/

#(2.1) Installing Bootstrap from NPM
@CMD
>npm i bootstrap@latest

//You can check the latest version of package before install
> npm show <package> version
> npm show bootstrap version

#(2.2) Importing the CSS
- Configure angular.json (refer to link), OR
- Import directly in src/style.css or src/style.scss

==========================
#(3) Add Font-Awesome
npm package: https://www.npmjs.com/package/@fortawesome/fontawesome
Office URL: https://fontawesome.com/how-to-use/on-the-web/setup/getting-started?using=web-fonts-with-css
installation reference: https://stackoverflow.com/questions/48184079/include-fortawesome-fontawesome-to-angular-cli-project

#(3.1) Installing Webpack from NPM
@CMD
>npm i @fortawesome/fontawesome-free

#(3.2) Importing the CSS
- Configure angular.json (refer to link), OR
- Import directly in src/style.css or src/style.scss

==========================
#(4) Add component [Product] & [Home]
#(4.1)
@CMD ==> C:\projects\test-mvc-angular\test-mvc-angular
>ng generate component product
>ng generate component home

==========================
