## Yii 1.1 Sorcery

### Get full table name from model

1. Add this method to the model: 

`public function getOriginalTableName()
{
    return Yii::app()->db->tablePrefix.str_replace(array('{{','}}'),'',$this->tableName());
}`

2. Get the name like this by calling this the above method like so: 

`$model->getOriginalTableName()`

