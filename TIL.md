### use a manual deploy wheel in requirements.lock (03/03/25)
- comment out the package you would like to replace
- at the top of the requirements.lock file, add the following
	- `package-name @ <wheel_url>`

