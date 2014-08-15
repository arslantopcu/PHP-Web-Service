PHP-Web-Service
===============

Php-NuSoap web service creator


```php

$server->wsdl->addComplexType(
    'CReceiveOrderResultInput',
    'complexType',
    'struct',
    'sequence',
    '',
    array(
        'OrderObjectId' => array('name'=>'OrderObjectId','type'=>'xsd:string'),
        'GSM'		=> array('name'=>'GSM','type'=>'xsd:string', 'minOccurs'=>0),
	'MPAY'		=> array('name'=>'MPAY','type'=>'xsd:string' ,'minOccurs'=>0),
        'SMSContent'	=> array('name'=>'SMSContent','type'=>'xsd:string','minOccurs'=>0),
	'TotalPrice'	=> array('name'=>'TotalPrice','type'=>'xsd:double'),
	'TotalUnitPrice'=> array('name'=>'TotalUnitPrice','type'=>'xsd:double'),
	'State'		=> array('name'=>'State','type'=>'xsd:int'),
	'StatusCode'	=> array('name'=>'StatusCode','type'=>'xsd:int'),
	'ErrorCode'	=> array('name'=>'ErrorCode','type'=>'xsd:string' ,'minOccurs'=>0),
	'ErrorMessage'	=> array('name'=>'ErrorMessage','type'=>'xsd:string' ,'minOccurs'=>0),
	'PaymentDateTime'=> array('name'=>'PaymentDateTime','type'=>'xsd:dateTime'),
	'GsmOperator'	=> array('name'=>'GsmOperator','type'=>'xsd:int'),
	'GsmType'	=> array('name'=>'GsmType','type'=>'xsd:int'),
	'SubscriberId'	=> array('name'=>'SubscriberId','type'=>'xsd:string'),
	'Products'	=> array('name'=>'Products','type'=>'tns:ArrayOfCSaleProduct','minOccurs'=>0),
	'OrderChannelId'=> array('name'=>'OrderChannelId','type'=>'xsd:int'),
	'PaymentTypeId'	=> array('name'=>'PaymentTypeId','type'=>'xsd:int'),	
	'PaymentCategoryId'=> array('name'=>'PaymentCategoryId','type'=>'xsd:int'),	
	'Pin'		=> array('name'=>'Pin','type'=>'xsd:string' ,'minOccurs'=>0),	
    )
);

```

