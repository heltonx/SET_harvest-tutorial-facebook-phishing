# SET_harvest-tutorial-facebook-phishing
Practial guide on how to use SET to do a facebook phishing page

1 ) Open the link of code pen and goto frame of login, right click > This Frame > Open Frame in new Tab (if the browser is Firefox).

original link:

https://codepen.io/sanketbodke/pen/abyyPNa

just the frame of the login template:

https://cdpn.io/sanketbodke/fullpage/abyyPNa?anon=true&view=


2 ) Download the page: right click > Save Page as. and save as index.html in /home/kali/


3 ) Do a little change the code of the index: at the form tag, add the parameters name="login" and name="password" at the tags "input text" and "input password", respectively. If you downloaded the index here, dont need to change anything.


4 ) Open set: setoolkit


5 ) Select the options: 1 (Social Engineering Attachs), 2 (Website Attack Vectors), 3 (Credential Harvest Attack Method), 3 (Custom Import)


6 ) For ip, keep the pattern, your local ip (We will change the tutorial after add ngrok in the game)


7 ) For the directory, select /home/kali/ . And select 1, just the index file. Ignore the question "URL of the website you imported", just press Enter.


8 ) The Credential Harvest will start listening at your port 80. Open the browser, insert your IP and test. At the listening terminal, the credentials must appear.


=================================================

Using with Ngrok

=================================================

1 ) Do the previous instructions and open your ngrok account on browser

2 ) Click on Endpoints

3 ) Click on + Start a Tunnel

4 ) If ngrok is not installed, click on Need to install ngrok first?

5 ) Select the option install via Apt, and run the commands as showed.

6 ) The last command will start the tunnel (ngrok http 80)

7 ) get the link at the field forwarding
will be something like:
https://as23-2804-d51-xxxx-a000-bbbb-f3c6-23dc-qqqq.ngrok-free.app

8 ) If the aplication Credential Harvest is still running, this link will be the one you will use to test harvest credentials

=================================================

Using with link shorteners, to mask ngrok alien link

=================================================


1 ) Do the previous ngrok instructions

2 ) login in bit.ly

3 ) Create new (link)

4 ) In Destination Field, paste the original link

5 ) In Custom back-half (optional), insert the custom link

6 ) Click on Create

----------

Alternativelly, do the same in tiny url, but no need account

https://tinyurl.com/app

