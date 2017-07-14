# php-xml2jsom
Crear una matriz asociativa PHP simple desde XML

Ejemplo: 

$xmlNode = simplexml_load_file('example.xml');
$arrayData = xmlToArray($xmlNode);
echo json_encode($arrayData);
