# bits.github.io

NOTE: If you have any problems open an issue in this repo, if you dont know what "opening an issue" is mail me the problem at seth.mridul@gmail.com 

If you are familiar with HTML/CSS and git go ahead and submit a PR for your webpage.
Or if you just want to upload your CV fill this form https://docs.google.com/forms/d/1RKfUWxxeN0bVcmrcjoNOHA0tbHCmf9D_DtA1rZ2IhA0 and you will get a webpage (bitsgoa.github.io/yourname) with your CV.

Or if you are not that techy and want to create a webpage wait for some time :) Trying to make a easy way to do that.

Follow the usual way.

Fork the repo

Clone the repo
```
git clone https://github.com/<your-github-nick>/bitsgoa.github.io
```
make the following changes in your local branch.

Let's suppose your name is Raj Kumar.

If you want a basic html page then click on `Create new file` write whatever html you want and name it rajkumar.html, then add yourself in the list of your respective year (let's say 2015) in 2015.html and you are done.

Sample templates:
* https://bitsgoa.github.io/user7/
* https://bitsgoa.github.io/user6/
* https://bitsgoa.github.io/user5/
* https://bitsgoa.github.io/user4/
* https://bitsgoa.github.io/user3/
* https://bitsgoa.github.io/user2/
* https://bitsgoa.github.io/user1/

If you want a fancy site something like `userX` then copy the folder of whichever template you like and rename it to `rajkumar` and create a `index.html` file inside the folder as your main page and you can add more pages inside the folder and link them through `index.html`.

Once this is done.
Take the usual git way
```
git diff # make sure you didn't change anything else
git add rajkumar.html # or the folder rajkumar
git commit -m 'Added webpage for Raj Kumar'
git push -u origin master # assuming you are working on master
```

then create a PR and I'll merge it  :)
