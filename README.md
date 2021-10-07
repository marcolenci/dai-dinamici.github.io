# dai-dinamici.github.io
The future version of [DAI](https://dinamici.org) website. Now statically generated.

## New posts

If you know how to use git, I recommend to install `hugo` and use `hugo new content/posts/post-title.md` or `hugo new content/dai-seminars/seminar-title.md` to generate the file, then edit its content and submit a pull-request.
This will automate a number of changes and will allow you to preview the changes running `hugo serve`.

If you don't know how to use git, you can use github web interface to add or upload files and can proceed as described below.

### Posts

- Create a new file with `.md` extension into the `content/posts` folter
- Copy the content of [`archetypes/posts.md`](https://github.com/dai-dinamici/dai-dinamici.github.io/raw/main/archetypes/posts.md) into the file
- Edit the content: you need to edit the `title`, `date` (in the form "2016-06-02 10:38:48"), `categories` fields and replace the `<!-- ... -->` part with the post body
- Submit the change as a pull-request

### DAI Seminars

- Create a new file with `.md` extension into the `content/dai-seminars` folter
- Copy the content of [`archetypes/dai-seminars.md`](https://github.com/dai-dinamici/dai-dinamici.github.io/raw/main/archetypes/dai-seminars.md) into the file
- Edit the content following the instructions in the file
- Submit the change as a pull-request
