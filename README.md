# Test_Answer
Based on the logic so i have designed my api and control by admin and normal user.

Some of the function only admin can perform all the function. But for normal user
only can perform certain function. The following function :
- create_user
- login
- check_available_shape
- request_shape

All this function you can test through POSTMAN.

The step for testing this api should be
1. Copy the code in this api.txt and paste into the python file 
2. Change the 'db_location' at line 13 to your db location
3. Create an admin user (function : create_admin)

and then you can start do testing on all the function. Also can use create_user to do
verify on the function that require admin to perform.
