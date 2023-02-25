<?php

// 6162470145:AAH-PO34EcpcvyNeTds9yjJtDB6NmiaHxwo


$id = $_REQUEST['id'];
	$token = $_REQUEST['token'];
	$from = $_REQUEST['from'];
	$to = $_REQUEST['to'];
	$text = $_REQUEST['text'];

	if ($token == "[your_token]") {
		echo "Thank you $from for sending $text";
	} else {
		echo "Incorrect token";
		die;
	}

