
unirest.io library for codeigniter
==================

Load CI Library
-----------------

	$this->load->library("unirest");


Request Reference
-----------------
	
	$headers = array("X-Mashape-Authorization" => "...");
	$url = "https://testapi.p.mashape.com/model";
	$body = array( 'id' => 1 );
	
	$response = $this->unirest->get($url, $headers = array(), $body = NULL);
	$response = $this->unirest->post($url, $headers = array(), $body = NULL);
	$response = $this->unirest->put($url, $headers = array(), $body = NULL);
	$response = $this->unirest->patch($url, $headers = array(), $body = NULL);
	$response = $this->unirest->delete($url, $headers = array());
	
	$body = $response->body;