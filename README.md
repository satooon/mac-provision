# Mac provisioning

## Environment

MacOSX Yosemite 10.10.4


## Usage

1. Install Xcode
	> sudo xcodebuild -license

2. Install Homebrew
	> ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

3. Install Git
	> brew install git

4. Clone this repository
	> git clone git@github.com:satooon/mac-provision.git
	
## Example Playbook

```
$ cd satooon/mac-provision
$ ansible-playbook -i hosts -vv mac-provision.yml
```

## License

MIT


