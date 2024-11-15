# Nodepay.ai
Register to Nodepay.ai : [https://app.nodepay.ai/register](https://app.nodepay.ai/register?ref=XUIidz3KLNqFmmi)

# Features
This script is intended for running on a server using multiple proxy.

## Update 
- each account only can connect 10 proxy
- so the best way to farm right now is to create multi accounts
- the script is support multi account just paste token `np_tokens.txt` each line for 1 account
- make sure your account get **Proof of Humanhood** badge
- Register here [https://app.nodepay.ai/](https://app.nodepay.ai/register?ref=XUIidz3KLNqFmmi)
 

## Obtain Required Information
1. Open the link and log in to [https://app.nodepay.ai/](https://app.nodepay.ai/register?ref=XUIidz3KLNqFmmi)
2. Press F12 to open the console and enter the code (Ctrl + Shift + i for inspection)
3. In the console, enter ``localStorage.getItem('np_token');``
4. The text printed in the console is your NP_TOKEN copy and paste to `np_token.txt`
5. put your proxy in `proxy.txt` file ex: `http://username:pass@ip:port`

## 1. Steps to Run the Code
```bash
git clone https://github.com/earnwitharsu/nodepay.git
```
```bash
cd nodepay
```

## 2. Install Dependencies
```bash
pip install -r requirements.txt
```
## 3. Run The Script
```bash
python3 main.py
```
## (if your are using this scrpit in mobile then run this command)
```bash
python main.py
```

## Expected Output

If running correctly, you will see logs like the following:
```bash
2024-07-30 04:37:18.263 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 88}}
2024-07-30 04:37:48.621 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 90}}
2024-07-30 04:38:18.968 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 94}}
2024-07-30 04:38:59.338 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 98}}

```
# nodepay
