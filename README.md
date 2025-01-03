# Setup
This will download Lab 8 locally, allowing you to work on your scripts and upload (push) them back up to GitHub.

1. Clone your lab repository into your ~/ops445/lab8 directory using SSH:
```bash
git clone <ssh link> ~/ops445/lab8/
```
2. Copy your backed-up work into your new GitHub-linked directory:
```bash
cp ~/old_ops445/lab8/* ~/ops445/lab8/
```

# Submission
1. There is no checking script for this lab.

2. Ensure that `fabfile.py` is in this directory.

3. Commit and push (upload) your lab work:
```bash
git add fabfile.py 
git commit -m "Individual message or note."
git push
```

You can make changes to your scripts and reupload as many times as you like. Make sure you commit+push to do so.

**Note:** Your lab is automatically submitted at the due date and time using the last published code. Any changes you publish after the due date won't be marked or seen by your professor.
