## How to get started
set the value for `APP_ID` in `index.html`
```
const APP_ID = '<your-app-id>'; // change it
```
generate server.xml with the following command:
```
openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes
```
run as follows:
```
python simple-https-server.py
```
then in your browser, visit:
```
https://localhost:4443
```
