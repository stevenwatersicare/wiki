## Checking for Permissions in Ospre

Check if user has permission by specific permission (e.g. jobs_dispensed, jobs_checkin, jobs_dispensed, etc.)

```php 
<?php
    if ( Yii::app()->user->checkPermission('my_custom_permission') ) {
        echo 'current logged in user has my_custom_permission';
    }
?>
```

Check if user has permission by group (e.g. administrator, managment, etc.)

```php 
<?php
    if ( Yii::app()->user->checkUserGroup('my_custom_group') ) {
        echo 'current logged in user is part of the my_custom_group';
    }
?>
```

Check for permission by a user id 

```php 
<?php
    if ( Yii::app()->user->id == '123456' ) {
        echo 'current logged in user has id 123456';
    }
?>
```


