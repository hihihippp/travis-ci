# How to contribute to Travis CI

Found a bug in our code, or have an idea for a feature? Here are some notes on
how to best report them so we can get it fixed as quickly as possible.

## Security Issues

***Any security issues should be submitted directly to
<security@travis-ci.org>***

In order to determine whether you are dealing with a security issue, ask
yourself these two questions:

1. Can I access something that's not mine, or something I shouldn't have access
   to? 
2. Can I disable something for other people?

If the answer to either of those two questions are "yes", then you're probably
dealing with a security issue. Note that even if you answer "no" to both
questions, you may still be dealing with a security issue, so if you're unsure,
just email us at <security@travis-ci.org>.

## Build Failures

Please note that our issue tracker's main purpose is to track bugs and feature
requests for Travis CI. If your build is passing locally, but not on Travis,
please make sure that it's an issue with Travis before reporting it.

Some frequent reasons for builds failing on Travis:

- 3rd party dependencies missing
- Minor differences between OS X and Linux (such as whether the filesystem is
  case-sensitive or not).

Some good places to ask for advice when your build is failing on Travis is [our
mailing list](https://groups.google.com/group/travis-ci/), or [the travis-ci
tag on Stack Overflow](http://stackoverflow.com/questions/tagged/travis-ci).

## Other Issues

Found a bug in Travis CI? Here are some notes on how to report the bug so we
can fix it as fast as possible:

- Explain, as detailed as possible, how to reproduce the issue.
- Include what you expected to happen, as well as what actually happened.
- If it's a bug with the website, please include information on what browser
  version and operating system you are running.
- If it helps, feel free to [attach a
  screenshot](https://github.com/blog/1347-issue-attachments) or video
  illustrating the issue.
- If you're having trouble with a specific build, please include a link to the
  build or job in question.

## Pull Requests

Know how to fix something? We love pull requests! Here's a quick guide:

1. [Check for open issues](https://github.com/travis-ci/travis-ci/issues), or
   open a fresh issue to start a discussion around a feature idea or a bug.
   Opening a separate issue to discuss the change is less important for smaller
   changes, as the discussion can be done in the pull request.
2. Fork the relevant repository on GitHub, and start making your changes.
3. Check out the README for the project for information specific to that
   repository.
3. Push the change (we recommend using a separate branch for your feature).
4. Open a pull request.
5. We try to merge and deploy changes as soon as possible, or at least leave
   some feedback, but if you haven't heard back from us after a couple of days,
   feel free to leave a comment on the pull request.
