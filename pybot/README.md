# How to use this image
	
	docker run -v /some/content:/robot ludomeurillon/pybot:2.8.7

It will execute pybot command in /some/content directory

Every arguments supported by pybot can be passed after this command

## Example
	
	docker run -v /some/content:/robot ludomeurillon/pybot:2.8.7 --help