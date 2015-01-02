#AssettoCorsaDevLibs
Some Dev Libraries to aid AC app development.

Adds ac functions into python to aid development in IDEs.



##Installing
Copy acDevLibs into "PythonXX\Lib\site-packages\"


For "import ac" put:
***
	try:
		import ac	
	except ImportError:
		from acDevLibs.acDev import ac as ac
***


	
For "import acsys" put:
***
	try:	
		import acsys	
	except ImportError:
		from acDevLibs.acsysDev import acsys as acsys
***