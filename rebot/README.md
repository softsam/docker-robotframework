# How to use this image

## Run pybot on my own test files
	
	docker run -v /some/content:/robot ludomeurillon/rebot:2.9

It will execute rebot command in /some/content directory

Every arguments supported by rebot can be passed after this command

## Example
	
	docker run -v /some/content:/robot ludomeurillon/rebot:2.9 --help