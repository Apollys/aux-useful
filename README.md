# Miscellaneous Useful Snippets

<br/>

<details>
  <summary><b>.bashrc g++ -std=XX aliases</b></summary><p>
  
```bash
# g++ aliases for specific standards
alias g++11='g++ -std=c++11'
alias g++14='g++ -std=c++14'
alias g++17='g++ -std=c++17'
alias g++20='g++ -std=c++20'
```
</p></details><br/>

<br/>

<details>
  <summary><b>.gitconfig "commit all changes" alias</b></summary><p>
  
```
[user]
	email = xxxxx
	name = xxxxx
	
[alias]
      ca = !sh -c 'git add -A && git commit -am \"$1\"' -
```
Usage: `git ca 'Commit message'`
</p></details><br/>

<br/>
