# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": "ee8IdG99UbcKH5a8rDn2+8cfWnt3wkc/DThIMxzeatYn5rukHnG3xqz+qPqoCqFpv2kjdyLqmFwr9oMFs4gVQ4egxzGlMQ58xyM2UHRXabc8ufRjM+dhdSTkCWrIPWo9ZHYsWEpuLxIQWQzIGY3ClgdB04t89/1O/w1cDnyilFU=
",
  "channelSecret": "05abbe457466d9ac2f8f8a5ab2ac9bd8
"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
