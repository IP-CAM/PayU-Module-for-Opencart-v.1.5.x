Step1:
Merge the files and folders in the PayU India module with the Open cart module. In other words, copy the end files/folders in the integration kit sent to you manually according to the files and folder structure.
For e.g.: The file admin/controller/payment/payu.php in the integration kit is pasted in the following directory in the opencart folder – www/opencart/upload/admin/controller/payment.
If you do not find any folder of Payu Plugin then, please paste the whole folder (including file) in that path.
The idea is to transfer files/folders from the last matching folder in the integration kit to the last matching folder in the open cart folder. Please notice that the path admin/controller/payment are same in the above mentioned example.

Step 2:
Please go to your OpenCart Admin panel.

Step 3:
Enter your User Name and Password. On the next page, hover your mouse on “Extensions” tab and click on “Payments”.

Step 4:
Click on Install on PayU India.

Step 5: 
You will notice an “Edit” link appears: Click on the Edit link.

Step 6: 
After You click on “Edit”. You get the next page given below.

Step 7: Enter the following details –
If you want to use the demo –
Merchant ID – gtKFFx
Salt – eCwWELxi
Mode – demo
Total – The value of checkout order total must reach this value before this payment method becomes active. You may leave it empty as well.
Order Status – Its shows the Status of the order. Ideally, you may select processing.
Geo Zone – All zones
Status – Enabled
Sort Order – Sort order determines what order the payment module are displayed in.
# After this click on the Save button.
You may use the following credit card credentials for successful transactions in
Test mode –
Credit Card Number – 5123456789012346
Name on the Card – Any name
Card Expiry – May, 2017
CVV – 123
(b) When you wish to go live –
Merchant ID – Enter the Merchant Key supplied to you.
Salt – Enter the Salt supplied to you.
Mode – live
Total – The value of checkout order total must reach this value before this payment method becomes active.
You may leave it empty as well.
