unirest-codeigniter
===================

unirest library for codeigniter

==================

Load CI Library 

$this->load->library("unirest");

Request Reference

$response = $this->unirest->get($url, $headers = array());
$response = $this->unirest->post($url, $headers = array(), $body = NULL);
$response = $this->unirest->put($url, $headers = array(), $body = NULL);
$response = $this->unirest->patch($url, $headers = array(), $body = NULL);
$response = $this->unirest->delete($url, $headers = array());
