# react_django_demo_app
A demo app for React and Django Deployment

docker-compose down
docker-compose up -d

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**************** # use ngrok for live user contareaeiar or any localport *********************



Ngrok अब बिना अकाउंट के काम नहीं करता। आपको:

एक free ngrok account बनाना पड़ेगा,

फिर वहाँ से एक authtoken कॉपी करके,

अपने सिस्टम में set करना पड़ेगा।

✅ Step-by-step Solution (Authtoken सेट करना)
1. Ngrok अकाउंट बनाएं (अगर नहीं है):
👉 Open this link in browser:
https://dashboard.ngrok.com/signup

Google या Email से Free अकाउंट बना सकते हो।

2. Authtoken कॉपी करें:
Login के बाद यह लिंक खोलें:
https://dashboard.ngrok.com/get-started/your-authtoken

वहाँ आपको ऐसा कुछ दिखेगा:

bash
Copy
Edit
ngrok config add-authtoken <your-token-here>
3. Authtoken को सिस्टम में सेट करें:
Terminal में ये कमांड चलाएँ (अपने token से):

bash
Copy
Edit
ngrok config add-authtoken <your-token-here>
जैसे:

bash
Copy
Edit
ngrok config add-authtoken 1x2y3zABCDefgh456789
4. अब फिर से ngrok चलाएँ:
bash
Copy
Edit
ngrok http 8080
अब ये बिना error के एक URL देगा जैसे:

arduino
Copy
Edit
https://abc1234.ngrok.io
