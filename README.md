# ExcelDownload

Welcome everybody! 
This code snippet will help you export CSV in a laravel project without using any package. 
For backend I assume you are using Laravel or any other PHP framework.

For frontend you should have plain Javascript or VueJS or Angular. It will work find for any javascript framework.

First of all add an action to your button. 

<button class="btn btn-success" onClick="ExportCSV()">Export</button>

inside your controller you have to put the code which is inside app/http/controllers

As I used it as a __invoke method.__

I have also shared my web.php file to see how to make a call in the routes.

Note: You can use your own model names and table columns as per your requirements.

Make calculations as per your model and you're done! 
