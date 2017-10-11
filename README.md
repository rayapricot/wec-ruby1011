# wec-ruby1011
##実行ログ
rayapricot:~/workspace $ mkdir wec-ruby1011
rayapricot:~/workspace $ cd wec-ruby1011/
rayapricot:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
rayapricot:~/workspace/wec-ruby1011 $ ^C
rayapricot:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
rayapricot:~/workspace/wec-ruby1011 (master) $ git add README.md
rayapricot:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) daf711f] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
rayapricot:~/workspace/wec-ruby1011 (master) $ git remote add origin https://github.com/rayapricot/wec-ruby1011.git
rayapricot:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com': rayapricot
Password for 'https://rayapricot@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 235 bytes | 235.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/rayapricot/wec-ruby1011.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
rayapricot:~/workspace/wec-ruby1011 (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
rayapricot:~/workspace/wec-ruby1011 (master) $ cd
rayapricot:~ $ cd workspace/
rayapricot:~/workspace $ cd wec-ruby1011/
rayapricot:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.1.gem (100%)
Successfully installed pry-0.11.1
3 gems installed
rayapricot:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> quit
rayapricot:~/workspace/wec-ruby1011 (master) $ sudo gem install bundler
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
1 gem installed
rayapricot:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
rayapricot:~/workspace/wec-ruby1011 (master) $ echo "こんにちは"
こんにちは
rayapricot:~/workspace/wec-ruby1011 (master) $ git stats
git: 'stats' is not a git command. See 'git --help'.

The most similar command is
        status
rayapricot:~/workspace/wec-ruby1011 (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        Gemfile

nothing added to commit but untracked files present (use "git add" to track)
rayapricot:~/workspace/wec-ruby1011 (master) $ ls
Gemfile  README.md
rayapricot:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> puts "hello"
hello
=> nil
[2] pry(main)> quit
rayapricot:~/workspace/wec-ruby1011 (master) $ ls
Gemfile  README.md
rayapricot:~/workspace/wec-ruby1011 (master) $ bundle install
Fetching gem metadata from https://rubygems.org/.............
Fetching version metadata from https://rubygems.org/.
Resolving dependencies...
Using bundler 1.15.4
Fetching mini_portile2 2.3.0
Installing mini_portile2 2.3.0
Fetching nokogiri 1.8.1
Installing nokogiri 1.8.1 with native extensions
Bundle complete! 1 Gemfile dependency, 3 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
rayapricot:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rb 
"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲームクリエイターに強い専門学校"
rayapricot:~/workspace/wec-ruby1011 (master) $ git add *
rayapricot:~/workspace/wec-ruby1011 (master) $ git commit -m '10/11 実行ログ'
[master abfb9a6] 10/11 実行ログ
 3 files changed, 33 insertions(+)
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 nokogiri.rb
rayapricot:~/workspace/wec-ruby1011 (master) $ git push
Username for 'https://github.com': rayapricot
Password for 'https://rayapricot@github.com': 
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 775 bytes | 775.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/rayapricot/wec-ruby1011.git
   daf711f..abfb9a6  master -> master
rayapricot:~/workspace/wec-ruby1011 (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
rayapricot:~/workspace/wec-ruby1011 (master) $ 