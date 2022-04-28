*Overview*

This is a proposed lightweight knowlegebase for Sprobe. Powered by [Hugo](https://gohugo.io/) and [Clarity theme](https://github.com/chipzoller/hugo-clarity).

*Setup*
1. Ensure hugo is installed. In Ubuntu (tested in WSL2 as well), do it this way:
```
~$ curl -OL https://github.com/gohugoio/hugo/releases/download/v0.96.0/hugo_extended_0.96.0_Linux-64bit.deb
~$ sudo apt-get install ./hugo_extended_0.96.0_Linux-64bit.deb
```
Check the latest Hugo releases from https://github.com/gohugoio/hugo/releases

For installation details, refer to https://gohugo.io/getting-started/installing/

2. Clone the project.
```
~$ git clone --recursive https://github.com/casimpania/sprobekb.git
```

3. Add new notes
```
~$ hugo new posts/your-new-blog-post.md
```

5. Edit your note file in #3

6. Test your changes locally
```
~$ hugo server
```
It will probably be accessible as http://localhost:1313/

7. Commit changes to git

Make sure to configure your name and email for git:
```
~$ git config user.name "Your Name Here"
~$ git config user.email "example@email.com"
```

And commit...
```
~$ git commit "My new awesome note!"
~$ git push
```
