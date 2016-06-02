# testing

#ruby

###Start

1. 安裝 homebrew 
	
		$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
		$ brew -v //檢查安裝
		
1. 安裝 git

		$ brew install git
		$ git —version //檢查安裝
	

1. 安裝 rvm Ruby版本管理工具

	設定 rvm 使用 homebrew
	
		$curl -L get.rvm.io | bash -s stable
		$rvm autolibs homebrew
		
1. 安裝ruby版本號,並使用預設
	
		$ rvm install 2.1.5
		$ rvm use 2.1.5
		$ rvm --default use 2.1.5