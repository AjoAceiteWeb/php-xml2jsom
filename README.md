# php-xml2jsom
Crear una matriz asociativa PHP simple desde XML
-------------------------------------------

Ejemplo:

    $xmlNode = simplexml_load_file('example.xml');
    $arrayData = xmlToArray($xmlNode);
    echo json_encode($arrayData);


Respuesta:

{
   "contacts" : {
      "contact" : {
         "@attributes" : {
            "id" : "1"
         }, 
         "name" : "John Doe", 
         "phone" : "123-456-7890", 
         "address" : {
            "street" : "123 JFK Street", 
            "city" : "Any Town", 
            "state" : "Any State", 
            "zipCode" : "12345"
         }
      }
   }
}
