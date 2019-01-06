# step-product-app

Creating & Starting a node project Using Express generator:


Step 1: Run the following command globally:  
npm install -g express-generator@4

You can run this command at any top level like C:/Administrator or C:/ or whatever you have as a root directory

This command will install express genrator globally


Step 2: To create a node project based on express generator:

express <YOUR_FILE_NAME>

<YOUR_FILE_NAME> - can be anything you want as a project name 

eg: express step_2019_express_project



Step 3: Get in to the new project generated above:

cd express step_2019_express_project


You could now see that the template is created already and you have app.js, package-json(With dependencies) files created already.

folders like route, services and public also created. public will hold all your assets (HTML,CSS,IMAGES ETC.)

routes is where you will have to create modules which handles only routing.

services is where you will have to write service (like connecting to DB)



MongoDB install
npm install mongodb --save

MongoDB on CLoud: www.mlab.com 


Fun with CSS: https://flukeout.github.io/


STATUS CODES

exports.STATUS_CODE = {
    SERVER_ERROR : {
        CODE : 500,
        STATUS : "Server Error",
        MESSAGE : "Some error occured in server"
    },
    DB_ERROR : {
        CODE : 500,
        STATUS : "Database Error",
        MESSAGE : "Some error occured in the database"
    },
    INSUFFICIENT_PARAMS : {
        CODE : 400,
        STATUS : "Bad request",
        MESSAGE : "Insufficient parameters"
    },
    PRODUCT_NOT_FOUND : {
        CODE : 401,
        STATUS : "Not found",
        MESSAGE : "No such product found. Please check again"
    }
};

