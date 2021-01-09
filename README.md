All the Documents are written in each and every file 


## Step: 1
application > config > constants.php   ==== Add Access key and Secret Key there

## Step: 2
Hit http://localhost:8888/rpay  ==== 8888 is my port number 

## Step: 3
By Default index() in Register.php is invoked and it drives a registration-form across your browser

## Step: 4
When you hit a submit in the registration-form it invokes pay() which redirect to the RazorPay gateway with some user data's stored in it 

## Step: 5
Select your prefered way of payment where your browser invokes rezorpay.php as a form. 

## Step: 6
Once all the details are add the form submits the data to Register.php > verify()

## Step: 7 
Gather all the data from the user and push it to database with random id generated from the payment