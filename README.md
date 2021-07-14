# email
1. Open php.ini, find [openssl], and overwrite the path of cacert.pem file.
   openssl.cafile="C:\xampp\htdocs\email\cacert.pem"

2. Turn on less secure app access in your Google account settings.

3. Input your email credentials in credentials.php file.

Note: Incase you accidentally deleted cacert.pem, You can download here: https://curl.haxx.se/ca/cacert.pem
