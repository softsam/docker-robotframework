# How to use this image

## Run junit_merge on my junit results files
	
	docker run -v /some/content:/robot softsam/junit-merge:0.1.2

It will execute pybot command in /some/content directory

Every arguments supported by junit_merge can be passed after this command

## junit_merge Documentation
	
http://www.rubydoc.info/gems/junit_merge/

## Example
	
	docker run -v /some/content:/robot softsam/junit-merge:0.1.2 --help