Drupal NIF/NIE/CIF Validator
============================

Implements additional validations to verify the control digit of NIFs, NIEs and CIFs in your Drupal Webforms.

How to use it
-------------

This module adds some extra validations to Drupal's [Webform Validation](https://drupal.org/project/webform_validation) module. So you better take a look at its documentation.

Once you've installed and activated it, you'll find a few new validation options. To find them, go to your Content menu and edit a webform (or create a new one). Then, go to the Webform tab and open the Form Validation option. There, you'll find new validations for NIFs, NIEs and CIFs.

![New Validations](https://github.com/amnesty/drupal-nif-nie-cif-validator/blob/master/img/Selection_179.png "New Validations")

You must choose one of this validations -let's say Validate NIF, for instance- and, then, specify the field you want to validate.

![Add Rule](https://github.com/amnesty/drupal-nif-nie-cif-validator/raw/master/img/new-rule.png "New Rule")

That's all! :-) Now, if you try to send the form using a non-valid number, Drupal won't accept it.

![Validation](https://github.com/amnesty/drupal-nif-nie-cif-validator/raw/master/img/validation.png "Validation")


How to use "Validate NIF/NIE/CIF Separately"
-------------
If you choose "Validate NIF/NIE/CIF Separately", you have to validate both fields "document type" and "document number". This is because depending on your "document type" option, the system will validate differently the document nummber.

You also need to add CSS classes to the fields "document type" and "document number" just to let the validator distinguish which one is it.

![Fields](https://github.com/amnesty/drupal-nif-nie-cif-validator/blob/master/img/Selection_182.png "Fields")

![Document_type](https://github.com/amnesty/drupal-nif-nie-cif-validator/blob/master/img/Selection_180.png "Document type")

![Document_number](https://github.com/amnesty/drupal-nif-nie-cif-validator/blob/master/img/Selection_181.png "Document number")


Dependencies
------------

* This module needs the [Webform Validation](https://drupal.org/project/webform_validation) module.
* This module uses the validations written for the [Amnesty International's DataQuality](https://github.com/amnesty/dataquality) project.

Related Drupal Modules
----------------------

A similar Drupal Module you may be interested in is the [Field NIF](https://drupal.org/project/field_nif) module.

License
-------

Amnesty / DataQuality functions. Copyright (C) 2013 Amnesty International.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program (see LICENSE.txt). If not, see http://www.gnu.org/licenses/.

