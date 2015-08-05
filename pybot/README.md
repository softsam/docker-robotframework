# How to use this image

## Run pybot on my own test files
	
	docker run -v /some/content:/robot softsam/pybot:2.9

It will execute pybot command in /some/content directory

Every arguments supported by pybot can be passed after this command

## Example
	
	docker run -v /some/content:/robot softsam/pybot:2.9 --help