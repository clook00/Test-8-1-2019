# Test-8-1-2019
Testing

# Heading 1 Hello
## Heading 2 Hello
### Heading 3 Hello

**bold**

*italic*

[github](https://github.com/)

```
code
```
Command line (Linux/ Unix)
gitbash --> pwd (print working directory)
cd (change directory)
ls (list all of the files or folders)
mkdir (make directory)
mv (move)
cat (concatenate, displays the contents of its inputs.)


GitBash Lab01

touch test.txt (open a new file)

echo "testing" >> test.txt (type something inside)

cat test.txt (display the file content)

git config --global --list
user.name=clook00
user.email=clook00@mylangara.ca

git clone https://github.com/clook00/Test-8-1-2019.git
Cloning into 'Test-8-1-2019'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 15 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (15/15), done.

cd Test-8-1-2019 --> ls --> README.md

git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

git add README.md

git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

git commit -m "updated readme"
[master a45ae1b] updated readme
 1 file changed, 1 insertion(+)
 
git push origin master
