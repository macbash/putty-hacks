## How to setup default ppk file in putty which help you to avoid selecting the ppk file every time

OS : Windows 10

1) Open Registry Editor
   Start -> Run -> regedit

2) Navigate to the Location => HKEY_CURRENT_USER\SOFTWARE\SimonTatham\PuTTY\Sessions

3) Below the keys you will find lot of keys if you have multiple sessions, if not there will only one like "Default%20Settings", click this key and navigate to right side window.

4) In the right side window, find the Name "PublicKeyFile", Double click it, Add your .ppk file complete path. ( Example : c:\Users\Foo\my_key.ppk )

Ref: How to create ppk file -> https://my.bluehost.com/hosting/help/putty
