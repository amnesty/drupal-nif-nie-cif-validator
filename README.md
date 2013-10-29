Spanish Ids Validator
=====================

Implements additional validations to verify the control digit of NIFs, NIEs and CIFs in your Drupal Webforms.

How to use it
-------------

Once you've installed and activated it, you'll find a few new validation options.
To find them, go to your Content menu and edit a webform (or create a new one).
Then, go to the Webform tab and open the Form Validation option.
There, you'll find the new validations:

* *Validate NIF/NIE/CIF*: Verifies that a user-entered value matches a NIF/NIE/CIF and verifies it's control digit.
* *Validate NIF*: Verifies that a user-entered value matches a NIF and verifies it's control digit.
* *Validate NIE*: Verifies that a user-entered value matches a NIE and verifies it's control digit.
* *Validate CIF*: Verifies that a user-entered value matches a CIF and verifies it's control digit.

Dependencies
------------

* This module needs the [Webform Validation](https://drupal.org/project/webform_validation) module.
* This module uses the validations written for the [Amnesty International's DataQuality](https://github.com/amnesty/dataquality) project.

License
-------

Amnesty / DataQuality functions. Copyright (C) 2013 Amnesty International.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program (see LICENSE.txt). If not, see http://www.gnu.org/licenses/.

