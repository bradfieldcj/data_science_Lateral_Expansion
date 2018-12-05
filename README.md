<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">

<head>

<meta charset="utf-8">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="generator" content="pandoc" />
<meta name="viewport" content="width=device-width, initial-scale=1">

<link href="data:text/css;charset=utf-8,%0A%40font%2Dface%20%7B%0Afont%2Dfamily%3A%20octicons%2Dlink%3B%0Asrc%3A%20url%28data%3Afont%2Fwoff%3Bcharset%3Dutf%2D8%3Bbase64%2Cd09GRgABAAAAAAZwABAAAAAACFQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABEU0lHAAAGaAAAAAgAAAAIAAAAAUdTVUIAAAZcAAAACgAAAAoAAQAAT1MvMgAAAyQAAABJAAAAYFYEU3RjbWFwAAADcAAAAEUAAACAAJThvmN2dCAAAATkAAAABAAAAAQAAAAAZnBnbQAAA7gAAACyAAABCUM%2B8IhnYXNwAAAGTAAAABAAAAAQABoAI2dseWYAAAFsAAABPAAAAZwcEq9taGVhZAAAAsgAAAA0AAAANgh4a91oaGVhAAADCAAAABoAAAAkCA8DRGhtdHgAAAL8AAAADAAAAAwGAACfbG9jYQAAAsAAAAAIAAAACABiATBtYXhwAAACqAAAABgAAAAgAA8ASm5hbWUAAAToAAABQgAAAlXu73sOcG9zdAAABiwAAAAeAAAAME3QpOBwcmVwAAAEbAAAAHYAAAB%2FaFGpk3jaTY6xa8JAGMW%2FO62BDi0tJLYQincXEypYIiGJjSgHniQ6umTsUEyLm5BV6NDBP8Tpts6F0v%2Bk%2F0an2i%2BitHDw3v2%2B9%2BDBKTzsJNnWJNTgHEy4BgG3EMI9DCEDOGEXzDADU5hBKMIgNPZqoD3SilVaXZCER3%2FI7AtxEJLtzzuZfI%2BVVkprxTlXShWKb3TBecG11rwoNlmmn1P2WYcJczl32etSpKnziC7lQyWe1smVPy%2FLt7Kc%2B0vWY%2FgAgIIEqAN9we0pwKXreiMasxvabDQMM4riO%2BqxM2ogwDGOZTXxwxDiycQIcoYFBLj5K3EIaSctAq2kTYiw%2Bymhce7vwM9jSqO8JyVd5RH9gyTt2%2BJ%2FyUmYlIR0s04n6%2B7Vm1ozezUeLEaUjhaDSuXHwVRgvLJn1tQ7xiuVv%2FocTRF42mNgZGBgYGbwZOBiAAFGJBIMAAizAFoAAABiAGIAznjaY2BkYGAA4in8zwXi%2BW2%2BMjCzMIDApSwvXzC97Z4Ig8N%2FBxYGZgcgl52BCSQKAA3jCV8CAABfAAAAAAQAAEB42mNgZGBg4f3vACQZQABIMjKgAmYAKEgBXgAAeNpjYGY6wTiBgZWBg2kmUxoDA4MPhGZMYzBi1AHygVLYQUCaawqDA4PChxhmh%2F8ODDEsvAwHgMKMIDnGL0x7gJQCAwMAJd4MFwAAAHjaY2BgYGaA4DAGRgYQkAHyGMF8NgYrIM3JIAGVYYDT%2BAEjAwuDFpBmA9KMDEwMCh9i%2Fv8H8sH0%2F4dQc1iAmAkALaUKLgAAAHjaTY9LDsIgEIbtgqHUPpDi3gPoBVyRTmTddOmqTXThEXqrob2gQ1FjwpDvfwCBdmdXC5AVKFu3e5MfNFJ29KTQT48Ob9%2FlqYwOGZxeUelN2U2R6%2BcArgtCJpauW7UQBqnFkUsjAY%2FkOU1cP%2BDAgvxwn1chZDwUbd6CFimGXwzwF6tPbFIcjEl%2BvvmM%2FbyA48e6tWrKArm4ZJlCbdsrxksL1AwWn%2FyBSJKpYbq8AXaaTb8AAHja28jAwOC00ZrBeQNDQOWO%2F%2FsdBBgYGRiYWYAEELEwMTE4uzo5Zzo5b2BxdnFOcALxNjA6b2ByTswC8jYwg0VlNuoCTWAMqNzMzsoK1rEhNqByEyerg5PMJlYuVueETKcd%2F89uBpnpvIEVomeHLoMsAAe1Id4AAAAAAAB42oWQT07CQBTGv0JBhagk7HQzKxca2sJCE1hDt4QF%2B9JOS0nbaaYDCQfwCJ7Au3AHj%2BLO13FMmm6cl7785vven0kBjHCBhfpYuNa5Ph1c0e2Xu3jEvWG7UdPDLZ4N92nOm%2BEBXuAbHmIMSRMs%2B4aUEd4Nd3CHD8NdvOLTsA2GL8M9PODbcL%2BhD7C1xoaHeLJSEao0FEW14ckxC%2BTU8TxvsY6X0eLPmRhry2WVioLpkrbp84LLQPGI7c6sOiUzpWIWS5GzlSgUzzLBSikOPFTOXqly7rqx0Z1Q5BAIoZBSFihQYQOOBEdkCOgXTOHA07HAGjGWiIjaPZNW13%2F%2Blm6S9FT7rLHFJ6fQbkATOG1j2OFMucKJJsxIVfQORl%2B9Jyda6Sl1dUYhSCm1dyClfoeDve4qMYdLEbfqHf3O%2FAdDumsjAAB42mNgYoAAZQYjBmyAGYQZmdhL8zLdDEydARfoAqIAAAABAAMABwAKABMAB%2F%2F%2FAA8AAQAAAAAAAAAAAAAAAAABAAAAAA%3D%3D%29%20format%28%27woff%27%29%3B%0A%7D%0Abody%20%7B%0A%2Dwebkit%2Dtext%2Dsize%2Dadjust%3A%20100%25%3B%0Atext%2Dsize%2Dadjust%3A%20100%25%3B%0Acolor%3A%20%23333%3B%0Afont%2Dfamily%3A%20%22Helvetica%20Neue%22%2C%20Helvetica%2C%20%22Segoe%20UI%22%2C%20Arial%2C%20freesans%2C%20sans%2Dserif%2C%20%22Apple%20Color%20Emoji%22%2C%20%22Segoe%20UI%20Emoji%22%2C%20%22Segoe%20UI%20Symbol%22%3B%0Afont%2Dsize%3A%2016px%3B%0Aline%2Dheight%3A%201%2E6%3B%0Aword%2Dwrap%3A%20break%2Dword%3B%0A%7D%0Aa%20%7B%0Abackground%2Dcolor%3A%20transparent%3B%0A%7D%0Aa%3Aactive%2C%0Aa%3Ahover%20%7B%0Aoutline%3A%200%3B%0A%7D%0Astrong%20%7B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0Ah1%20%7B%0Afont%2Dsize%3A%202em%3B%0Amargin%3A%200%2E67em%200%3B%0A%7D%0Aimg%20%7B%0Aborder%3A%200%3B%0A%7D%0Ahr%20%7B%0Abox%2Dsizing%3A%20content%2Dbox%3B%0Aheight%3A%200%3B%0A%7D%0Apre%20%7B%0Aoverflow%3A%20auto%3B%0A%7D%0Acode%2C%0Akbd%2C%0Apre%20%7B%0Afont%2Dfamily%3A%20monospace%2C%20monospace%3B%0Afont%2Dsize%3A%201em%3B%0A%7D%0Ainput%20%7B%0Acolor%3A%20inherit%3B%0Afont%3A%20inherit%3B%0Amargin%3A%200%3B%0A%7D%0Ahtml%20input%5Bdisabled%5D%20%7B%0Acursor%3A%20default%3B%0A%7D%0Ainput%20%7B%0Aline%2Dheight%3A%20normal%3B%0A%7D%0Ainput%5Btype%3D%22checkbox%22%5D%20%7B%0Abox%2Dsizing%3A%20border%2Dbox%3B%0Apadding%3A%200%3B%0A%7D%0Atable%20%7B%0Aborder%2Dcollapse%3A%20collapse%3B%0Aborder%2Dspacing%3A%200%3B%0A%7D%0Atd%2C%0Ath%20%7B%0Apadding%3A%200%3B%0A%7D%0A%2A%20%7B%0Abox%2Dsizing%3A%20border%2Dbox%3B%0A%7D%0Ainput%20%7B%0Afont%3A%2013px%20%2F%201%2E4%20Helvetica%2C%20arial%2C%20nimbussansl%2C%20liberationsans%2C%20freesans%2C%20clean%2C%20sans%2Dserif%2C%20%22Apple%20Color%20Emoji%22%2C%20%22Segoe%20UI%20Emoji%22%2C%20%22Segoe%20UI%20Symbol%22%3B%0A%7D%0Aa%20%7B%0Acolor%3A%20%234078c0%3B%0Atext%2Ddecoration%3A%20none%3B%0A%7D%0Aa%3Ahover%2C%0Aa%3Aactive%20%7B%0Atext%2Ddecoration%3A%20underline%3B%0A%7D%0Ahr%20%7B%0Aheight%3A%200%3B%0Amargin%3A%2015px%200%3B%0Aoverflow%3A%20hidden%3B%0Abackground%3A%20transparent%3B%0Aborder%3A%200%3B%0Aborder%2Dbottom%3A%201px%20solid%20%23ddd%3B%0A%7D%0Ahr%3Abefore%20%7B%0Adisplay%3A%20table%3B%0Acontent%3A%20%22%22%3B%0A%7D%0Ahr%3Aafter%20%7B%0Adisplay%3A%20table%3B%0Aclear%3A%20both%3B%0Acontent%3A%20%22%22%3B%0A%7D%0Ah1%2C%0Ah2%2C%0Ah3%2C%0Ah4%2C%0Ah5%2C%0Ah6%20%7B%0Amargin%2Dtop%3A%2015px%3B%0Amargin%2Dbottom%3A%2015px%3B%0Aline%2Dheight%3A%201%2E1%3B%0A%7D%0Ah1%20%7B%0Afont%2Dsize%3A%2030px%3B%0A%7D%0Ah2%20%7B%0Afont%2Dsize%3A%2021px%3B%0A%7D%0Ah3%20%7B%0Afont%2Dsize%3A%2016px%3B%0A%7D%0Ah4%20%7B%0Afont%2Dsize%3A%2014px%3B%0A%7D%0Ah5%20%7B%0Afont%2Dsize%3A%2012px%3B%0A%7D%0Ah6%20%7B%0Afont%2Dsize%3A%2011px%3B%0A%7D%0Ablockquote%20%7B%0Amargin%3A%200%3B%0A%7D%0Aul%2C%0Aol%20%7B%0Apadding%3A%200%3B%0Amargin%2Dtop%3A%200%3B%0Amargin%2Dbottom%3A%200%3B%0A%7D%0Aol%20ol%2C%0Aul%20ol%20%7B%0Alist%2Dstyle%2Dtype%3A%20lower%2Droman%3B%0A%7D%0Aul%20ul%20ol%2C%0Aul%20ol%20ol%2C%0Aol%20ul%20ol%2C%0Aol%20ol%20ol%20%7B%0Alist%2Dstyle%2Dtype%3A%20lower%2Dalpha%3B%0A%7D%0Add%20%7B%0Amargin%2Dleft%3A%200%3B%0A%7D%0Acode%20%7B%0Afont%2Dfamily%3A%20Consolas%2C%20%22Liberation%20Mono%22%2C%20Menlo%2C%20Courier%2C%20monospace%3B%0Afont%2Dsize%3A%2012px%3B%0A%7D%0Apre%20%7B%0Amargin%2Dtop%3A%200%3B%0Amargin%2Dbottom%3A%200%3B%0Afont%3A%2012px%20Consolas%2C%20%22Liberation%20Mono%22%2C%20Menlo%2C%20Courier%2C%20monospace%3B%0A%7D%0A%2Eselect%3A%3A%2Dms%2Dexpand%20%7B%0Aopacity%3A%200%3B%0A%7D%0A%2Eocticon%20%7B%0Afont%3A%20normal%20normal%20normal%2016px%2F1%20octicons%2Dlink%3B%0Adisplay%3A%20inline%2Dblock%3B%0Atext%2Ddecoration%3A%20none%3B%0Atext%2Drendering%3A%20auto%3B%0A%2Dwebkit%2Dfont%2Dsmoothing%3A%20antialiased%3B%0A%2Dmoz%2Dosx%2Dfont%2Dsmoothing%3A%20grayscale%3B%0A%2Dwebkit%2Duser%2Dselect%3A%20none%3B%0A%2Dmoz%2Duser%2Dselect%3A%20none%3B%0A%2Dms%2Duser%2Dselect%3A%20none%3B%0Auser%2Dselect%3A%20none%3B%0A%7D%0A%2Eocticon%2Dlink%3Abefore%20%7B%0Acontent%3A%20%27%5Cf05c%27%3B%0A%7D%0A%2Emarkdown%2Dbody%3Abefore%20%7B%0Adisplay%3A%20table%3B%0Acontent%3A%20%22%22%3B%0A%7D%0A%2Emarkdown%2Dbody%3Aafter%20%7B%0Adisplay%3A%20table%3B%0Aclear%3A%20both%3B%0Acontent%3A%20%22%22%3B%0A%7D%0A%2Emarkdown%2Dbody%3E%2A%3Afirst%2Dchild%20%7B%0Amargin%2Dtop%3A%200%20%21important%3B%0A%7D%0A%2Emarkdown%2Dbody%3E%2A%3Alast%2Dchild%20%7B%0Amargin%2Dbottom%3A%200%20%21important%3B%0A%7D%0Aa%3Anot%28%5Bhref%5D%29%20%7B%0Acolor%3A%20inherit%3B%0Atext%2Ddecoration%3A%20none%3B%0A%7D%0A%2Eanchor%20%7B%0Adisplay%3A%20inline%2Dblock%3B%0Apadding%2Dright%3A%202px%3B%0Amargin%2Dleft%3A%20%2D18px%3B%0A%7D%0A%2Eanchor%3Afocus%20%7B%0Aoutline%3A%20none%3B%0A%7D%0Ah1%2C%0Ah2%2C%0Ah3%2C%0Ah4%2C%0Ah5%2C%0Ah6%20%7B%0Amargin%2Dtop%3A%201em%3B%0Amargin%2Dbottom%3A%2016px%3B%0Afont%2Dweight%3A%20bold%3B%0Aline%2Dheight%3A%201%2E4%3B%0A%7D%0Ah1%20%2Eocticon%2Dlink%2C%0Ah2%20%2Eocticon%2Dlink%2C%0Ah3%20%2Eocticon%2Dlink%2C%0Ah4%20%2Eocticon%2Dlink%2C%0Ah5%20%2Eocticon%2Dlink%2C%0Ah6%20%2Eocticon%2Dlink%20%7B%0Acolor%3A%20%23000%3B%0Avertical%2Dalign%3A%20middle%3B%0Avisibility%3A%20hidden%3B%0A%7D%0Ah1%3Ahover%20%2Eanchor%2C%0Ah2%3Ahover%20%2Eanchor%2C%0Ah3%3Ahover%20%2Eanchor%2C%0Ah4%3Ahover%20%2Eanchor%2C%0Ah5%3Ahover%20%2Eanchor%2C%0Ah6%3Ahover%20%2Eanchor%20%7B%0Atext%2Ddecoration%3A%20none%3B%0A%7D%0Ah1%3Ahover%20%2Eanchor%20%2Eocticon%2Dlink%2C%0Ah2%3Ahover%20%2Eanchor%20%2Eocticon%2Dlink%2C%0Ah3%3Ahover%20%2Eanchor%20%2Eocticon%2Dlink%2C%0Ah4%3Ahover%20%2Eanchor%20%2Eocticon%2Dlink%2C%0Ah5%3Ahover%20%2Eanchor%20%2Eocticon%2Dlink%2C%0Ah6%3Ahover%20%2Eanchor%20%2Eocticon%2Dlink%20%7B%0Avisibility%3A%20visible%3B%0A%7D%0Ah1%20%7B%0Apadding%2Dbottom%3A%200%2E3em%3B%0Afont%2Dsize%3A%202%2E25em%3B%0Aline%2Dheight%3A%201%2E2%3B%0Aborder%2Dbottom%3A%201px%20solid%20%23eee%3B%0A%7D%0Ah1%20%2Eanchor%20%7B%0Aline%2Dheight%3A%201%3B%0A%7D%0Ah2%20%7B%0Apadding%2Dbottom%3A%200%2E3em%3B%0Afont%2Dsize%3A%201%2E75em%3B%0Aline%2Dheight%3A%201%2E225%3B%0Aborder%2Dbottom%3A%201px%20solid%20%23eee%3B%0A%7D%0Ah2%20%2Eanchor%20%7B%0Aline%2Dheight%3A%201%3B%0A%7D%0Ah3%20%7B%0Afont%2Dsize%3A%201%2E5em%3B%0Aline%2Dheight%3A%201%2E43%3B%0A%7D%0Ah3%20%2Eanchor%20%7B%0Aline%2Dheight%3A%201%2E2%3B%0A%7D%0Ah4%20%7B%0Afont%2Dsize%3A%201%2E25em%3B%0A%7D%0Ah4%20%2Eanchor%20%7B%0Aline%2Dheight%3A%201%2E2%3B%0A%7D%0Ah5%20%7B%0Afont%2Dsize%3A%201em%3B%0A%7D%0Ah5%20%2Eanchor%20%7B%0Aline%2Dheight%3A%201%2E1%3B%0A%7D%0Ah6%20%7B%0Afont%2Dsize%3A%201em%3B%0Acolor%3A%20%23777%3B%0A%7D%0Ah6%20%2Eanchor%20%7B%0Aline%2Dheight%3A%201%2E1%3B%0A%7D%0Ap%2C%0Ablockquote%2C%0Aul%2C%0Aol%2C%0Adl%2C%0Atable%2C%0Apre%20%7B%0Amargin%2Dtop%3A%200%3B%0Amargin%2Dbottom%3A%2016px%3B%0A%7D%0Ahr%20%7B%0Aheight%3A%204px%3B%0Apadding%3A%200%3B%0Amargin%3A%2016px%200%3B%0Abackground%2Dcolor%3A%20%23e7e7e7%3B%0Aborder%3A%200%20none%3B%0A%7D%0Aul%2C%0Aol%20%7B%0Apadding%2Dleft%3A%202em%3B%0A%7D%0Aul%20ul%2C%0Aul%20ol%2C%0Aol%20ol%2C%0Aol%20ul%20%7B%0Amargin%2Dtop%3A%200%3B%0Amargin%2Dbottom%3A%200%3B%0A%7D%0Ali%3Ep%20%7B%0Amargin%2Dtop%3A%2016px%3B%0A%7D%0Adl%20%7B%0Apadding%3A%200%3B%0A%7D%0Adl%20dt%20%7B%0Apadding%3A%200%3B%0Amargin%2Dtop%3A%2016px%3B%0Afont%2Dsize%3A%201em%3B%0Afont%2Dstyle%3A%20italic%3B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0Adl%20dd%20%7B%0Apadding%3A%200%2016px%3B%0Amargin%2Dbottom%3A%2016px%3B%0A%7D%0Ablockquote%20%7B%0Apadding%3A%200%2015px%3B%0Acolor%3A%20%23777%3B%0Aborder%2Dleft%3A%204px%20solid%20%23ddd%3B%0A%7D%0Ablockquote%3E%3Afirst%2Dchild%20%7B%0Amargin%2Dtop%3A%200%3B%0A%7D%0Ablockquote%3E%3Alast%2Dchild%20%7B%0Amargin%2Dbottom%3A%200%3B%0A%7D%0Atable%20%7B%0Adisplay%3A%20block%3B%0Awidth%3A%20100%25%3B%0Aoverflow%3A%20auto%3B%0Aword%2Dbreak%3A%20normal%3B%0Aword%2Dbreak%3A%20keep%2Dall%3B%0A%7D%0Atable%20th%20%7B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0Atable%20th%2C%0Atable%20td%20%7B%0Apadding%3A%206px%2013px%3B%0Aborder%3A%201px%20solid%20%23ddd%3B%0A%7D%0Atable%20tr%20%7B%0Abackground%2Dcolor%3A%20%23fff%3B%0Aborder%2Dtop%3A%201px%20solid%20%23ccc%3B%0A%7D%0Atable%20tr%3Anth%2Dchild%282n%29%20%7B%0Abackground%2Dcolor%3A%20%23f8f8f8%3B%0A%7D%0Aimg%20%7B%0Amax%2Dwidth%3A%20100%25%3B%0Abox%2Dsizing%3A%20content%2Dbox%3B%0Abackground%2Dcolor%3A%20%23fff%3B%0A%7D%0Acode%20%7B%0Apadding%3A%200%3B%0Apadding%2Dtop%3A%200%2E2em%3B%0Apadding%2Dbottom%3A%200%2E2em%3B%0Amargin%3A%200%3B%0Afont%2Dsize%3A%2085%25%3B%0Abackground%2Dcolor%3A%20rgba%280%2C0%2C0%2C0%2E04%29%3B%0Aborder%2Dradius%3A%203px%3B%0A%7D%0Acode%3Abefore%2C%0Acode%3Aafter%20%7B%0Aletter%2Dspacing%3A%20%2D0%2E2em%3B%0Acontent%3A%20%22%5C00a0%22%3B%0A%7D%0Apre%3Ecode%20%7B%0Apadding%3A%200%3B%0Amargin%3A%200%3B%0Afont%2Dsize%3A%20100%25%3B%0Aword%2Dbreak%3A%20normal%3B%0Awhite%2Dspace%3A%20pre%3B%0Abackground%3A%20transparent%3B%0Aborder%3A%200%3B%0A%7D%0A%2Ehighlight%20%7B%0Amargin%2Dbottom%3A%2016px%3B%0A%7D%0A%2Ehighlight%20pre%2C%0Apre%20%7B%0Apadding%3A%2016px%3B%0Aoverflow%3A%20auto%3B%0Afont%2Dsize%3A%2085%25%3B%0Aline%2Dheight%3A%201%2E45%3B%0Abackground%2Dcolor%3A%20%23f7f7f7%3B%0Aborder%2Dradius%3A%203px%3B%0A%7D%0A%2Ehighlight%20pre%20%7B%0Amargin%2Dbottom%3A%200%3B%0Aword%2Dbreak%3A%20normal%3B%0A%7D%0Apre%20%7B%0Aword%2Dwrap%3A%20normal%3B%0A%7D%0Apre%20code%20%7B%0Adisplay%3A%20inline%3B%0Amax%2Dwidth%3A%20initial%3B%0Apadding%3A%200%3B%0Amargin%3A%200%3B%0Aoverflow%3A%20initial%3B%0Aline%2Dheight%3A%20inherit%3B%0Aword%2Dwrap%3A%20normal%3B%0Abackground%2Dcolor%3A%20transparent%3B%0Aborder%3A%200%3B%0A%7D%0Apre%20code%3Abefore%2C%0Apre%20code%3Aafter%20%7B%0Acontent%3A%20normal%3B%0A%7D%0Akbd%20%7B%0Adisplay%3A%20inline%2Dblock%3B%0Apadding%3A%203px%205px%3B%0Afont%2Dsize%3A%2011px%3B%0Aline%2Dheight%3A%2010px%3B%0Acolor%3A%20%23555%3B%0Avertical%2Dalign%3A%20middle%3B%0Abackground%2Dcolor%3A%20%23fcfcfc%3B%0Aborder%3A%20solid%201px%20%23ccc%3B%0Aborder%2Dbottom%2Dcolor%3A%20%23bbb%3B%0Aborder%2Dradius%3A%203px%3B%0Abox%2Dshadow%3A%20inset%200%20%2D1px%200%20%23bbb%3B%0A%7D%0A%2Epl%2Dc%20%7B%0Acolor%3A%20%23969896%3B%0A%7D%0A%2Epl%2Dc1%2C%0A%2Epl%2Ds%20%2Epl%2Dv%20%7B%0Acolor%3A%20%230086b3%3B%0A%7D%0A%2Epl%2De%2C%0A%2Epl%2Den%20%7B%0Acolor%3A%20%23795da3%3B%0A%7D%0A%2Epl%2Ds%20%2Epl%2Ds1%2C%0A%2Epl%2Dsmi%20%7B%0Acolor%3A%20%23333%3B%0A%7D%0A%2Epl%2Dent%20%7B%0Acolor%3A%20%2363a35c%3B%0A%7D%0A%2Epl%2Dk%20%7B%0Acolor%3A%20%23a71d5d%3B%0A%7D%0A%2Epl%2Dpds%2C%0A%2Epl%2Ds%2C%0A%2Epl%2Ds%20%2Epl%2Dpse%20%2Epl%2Ds1%2C%0A%2Epl%2Dsr%2C%0A%2Epl%2Dsr%20%2Epl%2Dcce%2C%0A%2Epl%2Dsr%20%2Epl%2Dsra%2C%0A%2Epl%2Dsr%20%2Epl%2Dsre%20%7B%0Acolor%3A%20%23183691%3B%0A%7D%0A%2Epl%2Dv%20%7B%0Acolor%3A%20%23ed6a43%3B%0A%7D%0A%2Epl%2Did%20%7B%0Acolor%3A%20%23b52a1d%3B%0A%7D%0A%2Epl%2Dii%20%7B%0Abackground%2Dcolor%3A%20%23b52a1d%3B%0Acolor%3A%20%23f8f8f8%3B%0A%7D%0A%2Epl%2Dsr%20%2Epl%2Dcce%20%7B%0Acolor%3A%20%2363a35c%3B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0A%2Epl%2Dml%20%7B%0Acolor%3A%20%23693a17%3B%0A%7D%0A%2Epl%2Dmh%2C%0A%2Epl%2Dmh%20%2Epl%2Den%2C%0A%2Epl%2Dms%20%7B%0Acolor%3A%20%231d3e81%3B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0A%2Epl%2Dmq%20%7B%0Acolor%3A%20%23008080%3B%0A%7D%0A%2Epl%2Dmi%20%7B%0Acolor%3A%20%23333%3B%0Afont%2Dstyle%3A%20italic%3B%0A%7D%0A%2Epl%2Dmb%20%7B%0Acolor%3A%20%23333%3B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0A%2Epl%2Dmd%20%7B%0Abackground%2Dcolor%3A%20%23ffecec%3B%0Acolor%3A%20%23bd2c00%3B%0A%7D%0A%2Epl%2Dmi1%20%7B%0Abackground%2Dcolor%3A%20%23eaffea%3B%0Acolor%3A%20%2355a532%3B%0A%7D%0A%2Epl%2Dmdr%20%7B%0Acolor%3A%20%23795da3%3B%0Afont%2Dweight%3A%20bold%3B%0A%7D%0A%2Epl%2Dmo%20%7B%0Acolor%3A%20%231d3e81%3B%0A%7D%0Akbd%20%7B%0Adisplay%3A%20inline%2Dblock%3B%0Apadding%3A%203px%205px%3B%0Afont%3A%2011px%20Consolas%2C%20%22Liberation%20Mono%22%2C%20Menlo%2C%20Courier%2C%20monospace%3B%0Aline%2Dheight%3A%2010px%3B%0Acolor%3A%20%23555%3B%0Avertical%2Dalign%3A%20middle%3B%0Abackground%2Dcolor%3A%20%23fcfcfc%3B%0Aborder%3A%20solid%201px%20%23ccc%3B%0Aborder%2Dbottom%2Dcolor%3A%20%23bbb%3B%0Aborder%2Dradius%3A%203px%3B%0Abox%2Dshadow%3A%20inset%200%20%2D1px%200%20%23bbb%3B%0A%7D%0A%2Etask%2Dlist%2Ditem%20%7B%0Alist%2Dstyle%2Dtype%3A%20none%3B%0A%7D%0A%2Etask%2Dlist%2Ditem%2B%2Etask%2Dlist%2Ditem%20%7B%0Amargin%2Dtop%3A%203px%3B%0A%7D%0A%2Etask%2Dlist%2Ditem%20input%20%7B%0Amargin%3A%200%200%2E35em%200%2E25em%20%2D1%2E6em%3B%0Avertical%2Dalign%3A%20middle%3B%0A%7D%0A%3Achecked%2B%2Eradio%2Dlabel%20%7B%0Az%2Dindex%3A%201%3B%0Aposition%3A%20relative%3B%0Aborder%2Dcolor%3A%20%234078c0%3B%0A%7D%0A%2EsourceLine%20%7B%0Adisplay%3A%20inline%2Dblock%3B%0A%7D%0Acode%20%2Ekw%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Edt%20%7B%20color%3A%20%23ed6a43%3B%20%7D%0Acode%20%2Edv%20%7B%20color%3A%20%23009999%3B%20%7D%0Acode%20%2Ebn%20%7B%20color%3A%20%23009999%3B%20%7D%0Acode%20%2Efl%20%7B%20color%3A%20%23009999%3B%20%7D%0Acode%20%2Ech%20%7B%20color%3A%20%23009999%3B%20%7D%0Acode%20%2Est%20%7B%20color%3A%20%23183691%3B%20%7D%0Acode%20%2Eco%20%7B%20color%3A%20%23969896%3B%20%7D%0Acode%20%2Eot%20%7B%20color%3A%20%230086b3%3B%20%7D%0Acode%20%2Eal%20%7B%20color%3A%20%23a61717%3B%20%7D%0Acode%20%2Efu%20%7B%20color%3A%20%2363a35c%3B%20%7D%0Acode%20%2Eer%20%7B%20color%3A%20%23a61717%3B%20background%2Dcolor%3A%20%23e3d2d2%3B%20%7D%0Acode%20%2Ewa%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Ecn%20%7B%20color%3A%20%23008080%3B%20%7D%0Acode%20%2Esc%20%7B%20color%3A%20%23008080%3B%20%7D%0Acode%20%2Evs%20%7B%20color%3A%20%23183691%3B%20%7D%0Acode%20%2Ess%20%7B%20color%3A%20%23183691%3B%20%7D%0Acode%20%2Eim%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Eva%20%7Bcolor%3A%20%23008080%3B%20%7D%0Acode%20%2Ecf%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Eop%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Ebu%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Eex%20%7B%20color%3A%20%23000000%3B%20%7D%0Acode%20%2Epp%20%7B%20color%3A%20%23999999%3B%20%7D%0Acode%20%2Eat%20%7B%20color%3A%20%23008080%3B%20%7D%0Acode%20%2Edo%20%7B%20color%3A%20%23969896%3B%20%7D%0Acode%20%2Ean%20%7B%20color%3A%20%23008080%3B%20%7D%0Acode%20%2Ecv%20%7B%20color%3A%20%23008080%3B%20%7D%0Acode%20%2Ein%20%7B%20color%3A%20%23008080%3B%20%7D%0A" rel="stylesheet">
<style>
body {
  box-sizing: border-box;
  min-width: 200px;
  max-width: 980px;
  margin: 0 auto;
  padding: 45px;
  padding-top: 0px;
}
</style>

</head>

<body>

<h1 id="project-1-capstone-proposals">Project 1: Capstone Proposals</h1>
<p>Clinton Bradfield<br />
20181204</p>
<h1 id="project-1-capstone-proposals-n5">Project 1: Capstone Proposals (n=5)</h1>
<h2 id="financial-analysis-of-competitive-space-in-markets">Financial Analysis of Competitive Space in Markets</h2>
<ul>
<li>Development of Api chunking from SEC, Google, and Yahoo finance</li>
<li>Pie graph assessment</li>
<li>Specific Examples only</li>
<li>Growth and competition time-regression analysis and forecasting</li>
</ul>
<h2 id="google-analytics-kaggle">Google Analytics <a href="https://www.kaggle.com/bigquery/google-analytics-sample">Kaggle</a></h2>
<h4 id="session-browsing-data">Session Browsing Data</h4>
<ul>
<li>ID Customer base</li>
<li>Analyze who purchases high Profit/item merchandise</li>
<li>Assess if customer origin or site behaviour is linked with subtypes of purchases</li>
<li>Analyze if marketing type dictates key sales</li>
<li>Pairwise analysis and machine-learning models</li>
</ul>
<h2 id="honey-bee-pollen-ecology-kaggle">Honey-bee Pollen Ecology <a href="https://www.kaggle.com/ivanfel/honey-bee-pollen">Kaggle</a></h2>
<ul>
<li>Image Analysis</li>
<li>CNN detection, segmentation, and quantification</li>
<li>Rate of pollen acquisition</li>
<li>Projected impact on surrounding agriculture (cross-pollination)</li>
<li>Economic impact of Bee Efficiency</li>
</ul>
<h2 id="coursera-reviews-kaggle">Coursera Reviews <a href="https://www.kaggle.com/septa97/100k-courseras-course-reviews-dataset">Kaggle</a></h2>
<ul>
<li>Subset based on NLP word categories</li>
<li>Score based on NLP common words</li>
<li>Rank based on NLP Model</li>
<li>compare ratings with NLP scores</li>
</ul>
<h2 id="analyzing-art-kaggle">Analyzing Art <a href="https://www.kaggle.com/thedownhill/art-images-drawings-painting-sculpture-engraving/home">Kaggle</a></h2>
<ul>
<li>Seems like a perfect use for <em>GANs</em></li>
<li>Detect Image Type, Genre, and potentially artist depending on DB content</li>
<li>Assess content of images</li>
</ul>

</body>
</html>
