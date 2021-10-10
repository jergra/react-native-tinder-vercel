October 9, 2021

C:\webdev\react-native-tinder-vercel>

This is from a tutorial by Esteban Codes:
    Build a Tinder clone with React Native and Expo
    https://www.youtube.com/watch?v=QfaV2AfQysE&ab_channel=EstebanCodes

C:\webdev\react-native-tinder is deployed at:
    https://expo.dev/@jergra43/react-native-tinder
It was Expo that took care of this deployment.  But using the app 
is a two-stage process where we go to the above url then click again or alternatively
read a QR code on that page, so that the app can then function on a phone.

we want a deployment that opens, on a phone (that has Expo on it), 
with one click, the following link:
    exp://exp.host/@jergra43/react-native-tinder

deployment on vercel makes this possible.

to start locally:
    double cick on index.html in Windows Explorer
    a blank blue page will open
    in the console will be the message:
        Prevented navigation to 
        “exp://exp.host/@jergra43/react-native-tinder” due to an unknown protocol.

deployed (open on a phone that has Expo installed):
    https://react-native-tinder-vercel.vercel.app

update:
    git add . 
    git commit -m "message" 
    git push
