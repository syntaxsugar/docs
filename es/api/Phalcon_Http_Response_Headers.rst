Class **Phalcon\\Http\\Response\\Headers**
==========================================

*implements* :doc:`Phalcon\\Http\\Response\\HeadersInterface <Phalcon_Http_Response_HeadersInterface>`

This class is a bag to manage the response headers


Methods
-------

public  **set** (*string* $name, *string* $value)

Sets a header to be sent at the end of the request



public *string*  **get** (*string* $name)

Gets a header value from the internal bag



public  **setRaw** (*string* $header)

Sets a raw header to be sent at the end of the request



public  **remove** (*unknown* $header)

Removes a header to be sent at the end of the request



public  **send** ()

Sends the headers to the client



public  **reset** ()

Reset set headers



public  **toArray** ()

Returns the current headers as an array



public static  **__set_state** (*unknown* $data)

Restore a Phalcon\\Http\\Response\\Headers object



