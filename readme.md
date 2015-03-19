jsonp.js work flow

your javascript script request www.other.com  via json ->

it not request www.other.com , but https://jsonp.afeld.me/ like that :
https://jsonp.afeld.me/?callback=jQuery20006250812644138932_1426736844502&url=http://cdn.zhangfortune.com/test_script/jsonp_test.php&_=1426736844503 ->

jsonp.afeld.me receive your request and then it request www.other.com , and return the result from www.other.com ->

you receive your jsonp request result . good luck!

