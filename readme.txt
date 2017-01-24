Name: Custom User Permissions
Description: Apply permissions to specific users instead of just usergroups.
Website: https://github.com/MattRogowski/Custom-User-Permissions
Author: Matt Rogowski
Authorsite: https://matt.rogow.ski
Version: 1.0.1
Compatibility: 1.6.x, 1.8.x
Files: 3
Database changes: 1 new table, 1 new column to 1 default table.

To Install:
Upload ./inc/plugins/customuserperms.php to ./inc/plugins/
Upload ./admin/modules/user/customuserperms.php to ./admin/modules/user/
Upload ./inc/languages/english/admin/user_customuserperms.lang.php to ./inc/languages/english/admin/
Go to ACP > Plugins > Install and Activate
Go to ACP > Users & Groups > Custom User Permissions.

Information:
This plugin will allow you to give permissions to specific users.

You can set custom general board permissions, and also set permissions for specific forums as well as globally, which will override any other forum permissions.

Change Log:
17/11/10 - v0.1 -> Initial beta release.
03/12/10 - v0.1 -> v0.2 -> Added the ability to set global forum permissions, instead of just permissions for specific forums. To upgrade, reupload ./inc/plugins/customuserperms.php, ./admin/modules/user/customuserperms.php, ./inc/languages/english/admin/user_customuserperms.lang.php
07/02/11 - v0.2 -> v0.2.1 -> Fixed a bug where the count of general permissions would be incorrect. If a user has custom user permissions which are deactivated, the permissions won't be queried for. To upgrade, reupload ./inc/plugins/customuserperms.php and ./admin/modules/user/customuserperms.php
06/04/11 - v0.2.1 -> v0.2.2 -> Fixed a bug where the permissions would not be applied to the Archive mode. Added in a setting for the 'Can only view own threads?' permission. To upgrade, reupload ./inc/plugins/customuserperms.php, ./inc/languages/english/admin/customuserperms.lang.php and ./admin/modules/user/customuserperms.php
25/08/14 - v0.2.2 -> v1.0 -> MyBB 1.8 compatible. Added autocomplete for username field. To upgrade, reupload ./inc/plugins/customuserperms.php and ./admin/modules/user/customuserperms.php.
24/01/17 - v1.0.0 -> v1.0.1 -> Fixed a bug with text not appearing when using PHP 7. To upgrade, reupload ./inc/plugins/customuserperms.php and ./admin/modules/user/customuserperms.php.

Copyright 2017 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.