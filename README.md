 ##########################################################

FluidPhp 1 open source project email manager helper

A powerfull framework based on the phptoolcase library.

##########################################################

FluidPhp is a framework based on the PhpToolCase library.

Visit phptoolcase.com for complete guides and examples.

== PROJECT INFO ===================================

== Project Home: http://phptoolcase.com

== Requirements: php version 5.3+

== INSTALLATION WITH COMPOSER ========================
	
	Add the following to your composer.json file:
	
	- WITH FLUIDPHP FRAMEWORK:

		"require": 
		{
			"fluidphp/emailmanager-helper": "~1.0"
		} ,
		"extra": 
		{
			"installer-paths": 
			{
				"./vendor/fluidphp/helpers/EmailManager": ["fluidphp/emailmanager-helper"] ,
				"./vendor/fluidphp/helpers/Translator": ["fluidphp/translator-helper"]
			}
		}