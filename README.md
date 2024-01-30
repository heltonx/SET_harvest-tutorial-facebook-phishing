# SET_harvest-tutorial-facebook-phishing
Practial guide on how to use SET to do a facebook phishing page

1 ) Open the link of code pen and goto frame of login, right click > This Frame > Open Frame in new Tab (if the browser is Firefox).

original link
https://codepen.io/sanketbodke/pen/abyyPNa

just the frame of the login template:
https://cdpn.io/sanketbodke/fullpage/abyyPNa?anon=true&view=


2 ) Download the page: right click > Save Page as. and save as index.html in /home/kali/


3 ) alter the code of the index: at the form tag, add the parameters name="login" and name="password" at the tags "input text" and "input password", respectively. If you downloaded the index here, dont need to change anything.


4 ) Open set: setoolkit


5 ) Select the options: 1 (Social Engineering Attachs), 2 (Website Attack Vectors), 3 (Credential Harvest Attack Method), 3 (Custom Import)


6 ) For ip, keep the pattern, your local ip (We will change the tutorial after add ngrok in the game)


7 ), for the directory, select /home/kali/ . And select 1, just the index file. Ignore the question "URL of the website you imported", just press Enter.


8 ) THe Application SET will start listening at your port 80. Open the browser, put your IP and test. At the listening terminal, the credentials must appear.
