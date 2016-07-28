# React Blog Backend

The React Blog Backend is a REST api created with ruby on rails.  Its main purpose is to rehydrate the blog on load and provide a place to submit posts.  

# Getting started

Clone the repo

```shell
git clone <repo url>
```

Setup a posgresql server on your system however you can... gl :)

`cd` into your freshly cloned repo and run 

```shell
bin/rails db:create db:migrate
```

to create the proper structure in your posgresql db.  You will know the posgresql installation when alright when the above command does not explode into a thousand errors. `._.`

to run the server on localhost:3000 do

```shell
bin/rails s
```

It's all up and running... but how to use it?

## How to Use it

After following the *Getting Started* instructions got to localhost:3000/posts/new

This should be a form.

Enter some post information and submit.

You will be redirected to localhost:3000/posts/1 or something.  nice.

Your a smart person.  You get it.

### Some things to try

- Add some more posts
- Go to localhost:3000/posts
- Go to localhost:3000/posts.json
- Imagine the possibility
