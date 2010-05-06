Caution is needed when openning a MS Access .mdb file. It should be considered an executable since macros may run at startup.  These can be temporarily disabled by holding [SHIFT] during startup.

This ContatManager MS Access database is for tracking constituents and communication with them.  It requires MS Access.  It is a MS Windows client software.  It can't be used as an online system.


This is free software.

MIT LICENSE - http://en.wikipedia.org/wiki/MIT_License

 Permission is hereby granted, free of charge, to any person
 obtaining a copy of this software and associated documentation
 files (the "Software"), to deal in the Software without
 restriction, including without limitation the rights to use,
 copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the
 Software is furnished to do so, subject to the following
 conditions:

 The above copyright notice and this permission notice shall be
 included in all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
 EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
 OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
 NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
 HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
 WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
 FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
 OTHER DEALINGS IN THE SOFTWARE.



GIT NOTES

Global setup:

 Download and install Git
  git config --global user.name "Scott Mitchell"
  git config --global user.email scotty.mitchell@gmail.com
        

Next steps:

  mkdir ContactManager
  cd ContactManager
  git init
  touch README
  git add README
  git commit -m 'first commit'
  git remote add origin git@github.com:ScottMitchell/ContactManager.git
  git push origin master
      

Existing Git Repo?

  cd existing_git_repo
  git remote add origin git@github.com:ScottMitchell/ContactManager.git
  git push origin master
      

Importing a Subversion Repo?

  Click here
      

When you're done:

  Continue

