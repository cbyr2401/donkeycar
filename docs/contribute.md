
# Contribute to Donkey

Donkey is an open source project to help accelerate the development of
self driving autos.

## Guiding Development Principles

* **Modularity**: A self driving system is composed of standalone,
independently configurable components that can be combined to make a car.
* **Minimalism**: Each component should be kept short (<100 lines of code).
Each piece of code should be transparent upon first reading. No black magic,
it slows the speed of innovation.
* **Extensibility**: New components should be simple to create by following a
template.
* **Python**: Keep it simple.

***These guidelines are nearly copied from [Keras](http://keras.io),
   because they are so good***

## Add a part

Are you a hardware specialist that can write a donkey part wrapper for a
GPS unit or a data scientist that can write an recursive neural net autopilot?
If so please write a part so other people driving donkeys can use the part.

## Fix or report a bug

If you find a problem with the code and you know how to fix it then please
clone the repo, make your fix, and submit your pull request.

It is recommend that you squish or rebase all your changes into a single commit 
to assist with tracking changes.  To rebase your commit follow the below guide.

**Updating your dev branch

In order to correctly update to the latest dev branch, you must set up the upstream 
for your fork of Donkey Car.  [Reference](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)


From your fork of donkeycar...

1. Checkout the dev local branch
```bash
$ git checkout dev
```

2. Specify a new remote upstream repository that will be synced with the fork.

```bash
$ git remote add upstream  https://github.com/autorope/donkeycar
```

3. Verify the new upstream repository you've specified for your fork.

```bash
$ git remote -v
origin  https://github.com/YOUR_USERNAME/donkeycar (fetch)
origin  https://github.com/YOUR_USERNAME/donkeycar (push)
upstream        https://github.com/autorope/donkeycar (fetch)
upstream        https://github.com/autorope/donkeycar (push)
```

4. Update your local dev branch

```bash
$ git pull upstream dev
```




## Reply to issues

Helping close or triage the issues is a good way to help.

## If You Need An Inspiration

Search the code or docs for `TODO` to find places where you might be able
to find a better solution.

## Improve the documentation

You can fix grammar or provide clarity by clicking the the *Edit on GitHub*
link in the top right corner.
