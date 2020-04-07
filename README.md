# Rad-Libs

Welcome to Rad-Libs, a totally unique and not at all related to MadLibs app to make fun stories with your friends!

This project was completed over the course of a week during my attendance to FlatIron coding academy with my parters Jessica and Maylene.


Sorry this has not been webpacked well, to install and run do the following from root repo

npm install wordpos-web<br>
npm install<br>
open index.html<br>

--currently index.html will not be fully rendered until following stages--


--then go into the RadLibAPI directory and type--

yarn install<br>
rails db:migrate<br>
rails db:seed<br>
rails s<br>


Current bugs known (to be addressed at future date):
<ul>
<li>Create-a-lib needs to be refreshed before use, especially after finishing filling a Lib. Global variable supercedes input</li>
<li>star rating system has no current functionality</li>
<li>User login needed to disuade deleting other peoples completed Radlibs</li>
<li>Need identifier unique completed RadLibs,maybe username-radlibname</li>
<li>need to add required installations to webpack for easier install use</li>
</ul>

And personal code cleanup notes:
<ul>
<li>definitely need code refactor</li>
<li>Incorporate CSS style more (at all) for embedded elements within page</li>
</ul>




