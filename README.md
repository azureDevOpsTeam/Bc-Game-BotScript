### Bc.Game BotScript - Crash Game


##### You need to get the license to run the bot
[Get License](https://t.me/DevOpsWebSite)

---

#### Go to the [Bc.game](https://bc.game/) website

#### 1- Open the explosion game

#### 2- Press the F12 key

#### 3- Enter the Console

#### 4- Copy the script and paste it in Console

```

//Start Bet After 3 loss => next Green...
var startBetCountRed = 3;    //Payout 2x

//Start Bet After 3 wins => next Red...
var startBetCountGreen = 3; //Payout 1.96x

function _0x1e03(_0x3ca86b,_0x21abea){var _0x365bb8=_0x365b();return _0x1e03=function(_0x1e0303,_0x1dfcab){_0x1e0303=_0x1e0303-0x9a;var _0x479cf6=_0x365bb8[_0x1e0303];return _0x479cf6;},_0x1e03(_0x3ca86b,_0x21abea);}var _0x13cd2f=_0x1e03;function _0x365b(){var _0x5b8978=['tabs-navs','7962591dUVSAz','lastChild','2631330QagmFq','log','recent-list','setItem','1182uzIZeL','click','ui-button\x20button-normal\x20s-gray\x20bet-button\x20type-200','replace','children','button-group','16eqjGNO','5770SlgRQa','MachineId','ui-button\x20button-normal\x20s-gray\x20bet-button\x20type200','8b067ae7ff2d45beb17ed822ac36d3ab','replaceAll','8jifbFa','randomUUID','14050FZoQHG','green\x20button\x20is\x20Started\x20after\x20','color:\x20blue;\x20font-family:serif;\x20font-size:\x2015px','6796539vPVuNY','1892352EHbSLg','className','78734itQllE','textContent','3014NlLTLs','getElementsByClassName','getItem','%TelegramId:\x20@DevOpsWebSite','tabs-nav\x20is-active','firstChild','The\x20activation\x20code\x20is\x20invalid'];_0x365b=function(){return _0x5b8978;};return _0x365b();}(function(_0x56a56d,_0x2b62ad){var _0x4fb23a=_0x1e03,_0x52f02d=_0x56a56d();while(!![]){try{var _0x1d90ba=parseInt(_0x4fb23a(0x9b))/0x1*(-parseInt(_0x4fb23a('0xa9'))/0x2)+-parseInt(_0x4fb23a(0xb5))/0x3+-parseInt(_0x4fb23a(0xa7))/0x4+-parseInt(_0x4fb23a(0xa3))/0x5*(-parseInt(_0x4fb23a('0xb9'))/0x6)+parseInt(_0x4fb23a('0xb3'))/0x7+parseInt(_0x4fb23a(0xa1))/0x8*(parseInt(_0x4fb23a(0xa6))/0x9)+parseInt(_0x4fb23a(0x9c))/0xa*(parseInt(_0x4fb23a(0xab))/0xb);if(_0x1d90ba===_0x2b62ad)break;else _0x52f02d['push'](_0x52f02d['shift']());}catch(_0x704381){_0x52f02d['push'](_0x52f02d['shift']());}}}(_0x365b,0x9869a));var machineId=localStorage[_0x13cd2f(0xad)](_0x13cd2f(0x9d));!machineId&&(machineId=crypto[_0x13cd2f('0xa2')](),localStorage[_0x13cd2f(0xb8)](_0x13cd2f(0x9d),machineId));machineId=machineId[_0x13cd2f(0xa0)]('-','');var activeKey=_0x13cd2f('0x9f');if(machineId==activeKey){var countToMin=0x0,countGreen=0x0,countRed=0x0,firstRole=!![],first_row=parseInt(document[_0x13cd2f('0xac')](_0x13cd2f('0xb7'))[0x0][_0x13cd2f('0xb4')][_0x13cd2f(0xb0)][_0x13cd2f(0xaa)]),first_crash=parseFloat(document[_0x13cd2f(0xac)](_0x13cd2f('0xb7'))[0x0][_0x13cd2f(0xb4)][_0x13cd2f('0xb4')][_0x13cd2f(0xaa)][_0x13cd2f(0xbc)]('x','')),last_row=0x0,last_crash=0x0,selectTrendButton=document[_0x13cd2f(0xac)](_0x13cd2f(0xb2))[0x0][_0x13cd2f('0xb4')][_0x13cd2f(0xa8)];selectTrendButton!=_0x13cd2f('0xaf')&&document[_0x13cd2f(0xac)](_0x13cd2f('0xb2'))[0x0][_0x13cd2f('0xb4')][_0x13cd2f(0xba)]();var myTimeout=null,checkCrashInterval=null;checkCrashInterval=setInterval(checkFunction,0x3e8);function checkFunction(){var _0x12d669=_0x13cd2f;_countToMin=0x0,last_row=parseInt(document[_0x12d669(0xac)](_0x12d669('0xb7'))[0x0][_0x12d669('0xb4')][_0x12d669(0xb0)][_0x12d669('0xaa')]),last_crash=parseFloat(document[_0x12d669('0xac')](_0x12d669('0xb7'))[0x0][_0x12d669('0xb4')][_0x12d669(0xb4)][_0x12d669('0xaa')][_0x12d669(0xbc)]('x',''));if(first_row!=last_row){first_row=last_row,first_crash=last_crash;last_crash>1.99?(countRed=0x0,countGreen++):(countGreen=0x0,countRed++);if(countGreen>=startBetCountGreen)clearInterval(checkCrashInterval),startBet_Red(countGreen,last_row,last_crash);else countRed>=startBetCountRed&&(clearInterval(checkCrashInterval),startBet_Green(countRed,last_row,last_crash));}}function startBet_Red(_0x15f93b,_0x346f35,_0x23954a){var _0x519158=_0x13cd2f;document[_0x519158('0xac')](_0x519158(0xbb))[0x0][_0x519158(0xb4)]['click'](),console[_0x519158(0xb6)](_0x519158('0xa4')+_0x15f93b),new_row=0x0,new_crash=0x0;var _0x26b044=setInterval(function(){var _0x32891a=_0x519158;new_row=parseInt(document[_0x32891a('0xac')](_0x32891a('0xb7'))[0x0][_0x32891a('0xb4')][_0x32891a(0xb0)][_0x32891a(0xaa)]),new_crash=parseFloat(document[_0x32891a(0xac)](_0x32891a(0xb7))[0x0][_0x32891a('0xb4')][_0x32891a(0xb4)][_0x32891a(0xaa)][_0x32891a('0xbc')]('x','')),new_row>_0x346f35&&(_0x346f35=new_row,_0x23954a=new_crash,new_crash<0x2?(clearInterval(_0x26b044),countGreen=0x0,countRed=0x0,!firstRole&&(valueToDefault(countToMin),countToMin=0x0),checkCrashInterval=setInterval(checkFunction,0x3e8)):(document[_0x32891a(0xac)](_0x32891a('0x9a'))[0x0][_0x32891a(0xbd)][0x1][_0x32891a('0xba')](),countToMin++,firstRole=![],setTimeout(function(){var _0x5118ea=_0x32891a;document['getElementsByClassName'](_0x5118ea('0xbb'))[0x0][_0x5118ea(0xb4)][_0x5118ea(0xba)]();},0x1f4),countGreen++));},0x3e8);}function startBet_Green(_0x145652,_0x478081,_0x1eb50d){var _0x549a3a=_0x13cd2f;document[_0x549a3a(0xac)](_0x549a3a(0x9e))[0x0][_0x549a3a('0xb4')][_0x549a3a('0xba')](),console[_0x549a3a(0xb6)]('Red\x20button\x20is\x20Started\x20after\x20'+_0x145652),new_row=0x0,new_crash=0x0;var _0x437e0c=setInterval(function(){var _0x8d6ed9=_0x549a3a;new_row=parseInt(document[_0x8d6ed9('0xac')](_0x8d6ed9(0xb7))[0x0][_0x8d6ed9('0xb4')][_0x8d6ed9(0xb0)]['textContent']),new_crash=parseFloat(document[_0x8d6ed9(0xac)](_0x8d6ed9('0xb7'))[0x0][_0x8d6ed9(0xb4)][_0x8d6ed9(0xb4)]['textContent'][_0x8d6ed9('0xbc')]('x','')),new_row>_0x478081&&(_0x478081=new_row,_0x1eb50d=new_crash,new_crash>1.99?(clearInterval(_0x437e0c),countGreen=0x0,countRed=0x0,!firstRole&&(valueToDefault(countToMin),countToMin=0x0),checkCrashInterval=setInterval(checkFunction,0x3e8)):(document[_0x8d6ed9(0xac)](_0x8d6ed9(0x9a))[0x0]['children'][0x1][_0x8d6ed9(0xba)](),countToMin++,firstRole=![],setTimeout(function(){var _0x141f4c=_0x8d6ed9;document[_0x141f4c(0xac)]('ui-button\x20button-normal\x20s-gray\x20bet-button\x20type200')[0x0][_0x141f4c('0xb4')][_0x141f4c('0xba')]();},0x1f4),countRed++));},0x3e8);}function valueToDefault(_0x14dda2){for(var _0x45c848=0x0;_0x45c848<_0x14dda2;++_0x45c848){doSetTimeout();}_0x14dda2--;}function doSetTimeout(){setTimeout(function(){var _0xd01969=_0x1e03;document[_0xd01969(0xac)](_0xd01969('0x9a'))[0x0][_0xd01969(0xbd)][0x0][_0xd01969('0xba')]();},0x1f4);}}else console[_0x13cd2f(0xb6)](_0x13cd2f('0xb1')),console['log'](_0x13cd2f('0xae'),_0x13cd2f(0xa5));

```
