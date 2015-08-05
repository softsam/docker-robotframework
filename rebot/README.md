# How to use this image

## Run rebot on my own test files
	
	docker run -v /some/content:/robot softsam/rebot:2.8.7

It will execute rebot command in /some/content directory

Every arguments supported by rebot can be passed after this command

## Example
	
	docker run -v /some/content:/robot softsam/rebot:2.8.7 --help