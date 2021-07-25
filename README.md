# Css-File-For-Laravel-Developers --it will help you to bring the design layout when you add Laravel Authentication.
 1. In Login Web Page.
 2. In Sign up Web Page

### How to add:

- First you have to install laravel in your system.
- Second you have to go to the "public" folder, in public folder make a folder by the name of "css" if it exists then just clone the file and paste it there else make a folder and clone css-file and paste it over there. 

Note: this would be useful way when your layout is not working properly when you install the laravel authentication.

## Best way to bring Authentication Graphics layout in your laravel project 6.x or 7.x:


#### Step 1 : Try the following two commands in your normal terminal not of your project directory. The below command will only update the composer.

   ``` composer self-update ```
   
OR use the below command (it will update your dependencies plus your composer)

   ``` composer update ```
   
When you composer gets updated. check the composer by the below command

  ``` composer --version ```
   
#### Step 2 : First go to your project root folder C:\Whatever\Your_project_name>

  ``` composer require laravel/ui ```

Try any of the below command according to your front end framework.
```
   php artisan ui vue --auth
   php artisan ui bootstrap --auth
   php artisan ui react --auth
```
At the end don't forget to run

 ```  npm install ```
   
If your User Interface is not working properly try below command.

   ``` npm run production ```
