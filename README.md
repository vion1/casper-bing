## Description

Login to a microsoft account and do some bing searches daily


## Requirement

CasperJS

[http://casperjs.org/]


## Install

`npm install`


## Run

`casperjs index.js`


## Log 

`tail myCasper.log -F`


## Log in web

`forever start log.js`

`http://localhost:3000`


## Daily Cron Job

`crontab -e`

Add

`0 6 * * * /PATH/script/dailyscript.sh`


## License

MIT
