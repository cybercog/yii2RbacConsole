#This is controller to Yii2 Rbac module

##Posible action:

Assign user.

    yii rbac/assign rolename username
Revoke user.

    yii rbac/revoke rolename username
Show all roles of user.

    yii rbac/show-role username
Show all permission from user or role.
  
    yii rbac/show-permission name [--by=role]
Remove permission child from user or role.

    yii rbac/remove-child-permission parentName childName[--by=role]
Remove role child from role.

    yii rbac/remove-child-role parentName childName
Add child role to role.

    yii rbac/add-child-role parentName childName
Add child premission to user or role.

    yii rbac/add-child-permission parentName childName [--by=role]
Create role.

    yii rbac/create-role name
Create permission

    yii rbac/create-permission name
Remove role.

    yii rbac/remove-role
Remove permission.
    yii rbac/remove-permission



