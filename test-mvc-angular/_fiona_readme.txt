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
- Configure angular.json (refer to link)
- Import directly in src/style.css or src/style.scss

==========================
