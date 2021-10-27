# PicoCTF-29649 (Cookies)
No Cookies ? Try to figure out the best one.http://mercury.picoctf.net:29649/

## Overview:
> Web Explotations , Points > 40

## Hint:
(NONE)

## Process : 
> In this link you will see something like this

<img width="1114" alt="Screenshot 2021-10-27 at 4 28 29 PM" src="https://user-images.githubusercontent.com/82142638/139055408-2a9b62e6-f3d0-4275-ac1b-55652fa77e78.png">

> I typed in "snickerdoodle" and entered it.
> I love snickerdoodle cookies!
> Then intercept the request  in BurpSuite for cookies.
> (for auto You can press control + shift to navigate the storage )

<img width="1280" alt="Screenshot 2021-10-27 at 4 58 53 PM" src="https://user-images.githubusercontent.com/82142638/139057225-5b19826a-0c87-4ebc-9ca3-33c7fe82a5db.png">

> Then  I noticed there's a grand total of one cookie with a name of cookie (cookie name ) 0. I changed the value to 1 and refreshed the page.
> I love chocolate chip cookies!

<img width="1163" alt="Screenshot 2021-10-27 at 5 04 48 PM" src="https://user-images.githubusercontent.com/82142638/139058008-3533efc9-1f7c-4271-a8ea-fb33dadb2dd3.png">

> > I kept increasing the numeric value of value by 1 until at 18 :

<img width="1226" alt="Screenshot 2021-10-27 at 5 13 40 PM" src="https://user-images.githubusercontent.com/82142638/139059231-cf47e874-988a-4c2b-a9be-36e76b07c51f.png">

## Flag: 

picoCTF{3v3ry1_l0v3s_c00k135_a1f5bdb7}





