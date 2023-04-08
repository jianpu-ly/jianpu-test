# jianpu-test
Testing a transfer to GitHub Organisation

See https://github.com/ssb22/jianpu-ly/issues/26

* [x] can we still `git clone https://github.com/ssb22/jianpu-test.git` → yes
* [x] can we still `git clone git@github.com:ssb22/jianpu-test.git` → yes
* [ ] can it still appear in [my repositories tab](https://github.com/ssb22?tab=repositories) → doesn't seem so.
  * Minor annoyance for myself: I'm used to being able to find recent commits in that tab.  Will need bookmarks instead.
  * Not sure if anyone else (employers??) check that tab to see what I've done (not terribly important though)
* [ ] can I still arrange for jianpu-ly to appear on [my "popular repositories" list](https://github.com/ssb22) (hard to test that with a second repository!)  or does this not matter?
* [ ] will [git2gmi](https://github.com/ssb22/bits-and-bobs/blob/master/git2gmi.py) still catch any commits I make when it's in an organisation? → No.
  * This means I can't even use my Gemini capsule to check my recent commits across all repositories, and we've already seen above that I can no longer use GitHub's "my repositories" tab to do so.  Ouch.
  * [ ] Can git2gmi be fixed so it counts a user's commits to their organisations' repositories?

# Potential advantages of using a github organisation
* more obvious it's not just the work of one person
* group multiple repositories under the project
