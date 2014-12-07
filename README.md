```
                                        CLI GitHub
                          A fancy GitHub client for command line.

                                    ..    ..::..    ..
                                  ..  ,,LLCCCCCCLL,,  ..
                                    ,,CCCCCCCCCCCCCC,,
                                    LLCC,,iiiiii,,CCLL
                                  ,,CCCC          CCCC,,
                                  ::CCLL  ......  ffCC::
                                  ,,CCCC    ..    CCCC,,
                                    CCCCLLii  ;;LLCCCC
                                    ;;CCffii  ttCCCC;;
                                  ..  ;;CC11  11CC;;  ..
                                    ..  ....  ....  ..







             :1ffftti,                .:::.    ,:::              :::,
           tCCCCCCCCCL  fCCf   .... . 1CCC1    LCCC,            ,CCCL .
          LCCCCLtttfL; .CCCC. ,CCCf . 1CCCt .. CCCC,            ,CCCL
         1CCCC.         ;ff;  ;CCCL,; 1CCC1    LCCC..;:;.  .;:;.,CCCL,i11;
         LCCC;  ;iiiii, CCCC.CCCCCCCC:iCCCCLLLLCCCC tCCCi  tCCCi.CCCCCCCCCC;
         LCCC:  CCCCCCf CCCC fLCCCCff.1CCCCCCCCCCCC tCCCi  tCCCi.CCCC1itCCCC
         LCCC;  tfLCCCt CCCC  ,CCCL . 1CCCf:;;:CCCC tCCCi  tCCCi.CCCL . LCCC:
         iCCCC.   iCCCt CCCC  :CCCL . 1CCC1    LCCC tCCCi  1CCCi.CCCL . LCCC:
          LCCCCLffLCCCf CCCC  .CCCCi1 1CCC1 .  CCCC tCCCLi1LCCCi.CCCC1itCCCC
           1CCCCCCCCCC1 CCCC   tCCCCC;iCCC1    LCCC..CCCCCCCCCCi.CCCCCCCCCC:
             .;1tt1i:   :;;:    ,i11i..;;;.    :;;;   :1t1i,.;;. ;;:.;111;

```

## Prerequisites

 - [NodeJS](http://nodejs.org/)
 - [ImageMagic](http://www.imagemagick.org/)

   ```sh
   # Ubuntu
   $ sudo apt-get install imagemagick
   # Mac OS X
   $ brew install imagemagick
   ```

## Installation

```sh
$ npm install -g cli-github
```

## Usage

```sh
$ github
```

Use the following key shortcuts to access different GitHub resources:

 - <kbd>SHIFT</kbd> + <kbd>C</kbd>: Create a new repository on GitHub.
 - <kbd>SHIFT</kbd> + <kbd>P</kbd>: Visit GitHub profiles (default: your GitHub profile).
 - <kbd>SHIFT</kbd> + <kbd>I</kbd>: View the open issues that are assigned to you.
 - <kbd>SHIFT</kbd> + <kbd>R</kbd>: View the open pull requests that created by you.
 - <kbd>SHIFT</kbd> + <kbd>←</kbd>: Go back in history
 - <kbd>SHIFT</kbd> + <kbd>→</kbd>: Go forth in history

## Screenshots

### Splashscreen

![](/screenshots/splashscreen.png)

### News Feed

![](/screenshots/news-feed.png)

### Create repository
![](/screenshots/create-repo.png)

### Profile
![](/screenshots/profile.png)

### Issues
![](/screenshots/issues.png)

### Pull Requests
![](/screenshots/pull-requests.png)

## Changelog
### [`1.5.0`](https://github.com/IonicaBizau/cli-github/pull/15)
 - [cli-update@0.0.3](https://github.com/IonicaBizau/node-cli-update)
 - [overlap@1.3.0](https://github.com/IonicaBizau/overlap)
 - [image-to-ascii@1.2.0](https://github.com/IonicaBizau/image-to-ascii)
 - Fixes [#6](https://github.com/IonicaBizau/cli-github/issues/6).

### [`1.4.0`](https://github.com/IonicaBizau/cli-github/pull/14)
 - I rollbacked the manual event description computing from [#5](https://github.com/IonicaBizau/cli-github/pull/5), now using `<user>:<token>`.

### [`1.3.0`](https://github.com/IonicaBizau/cli-github/pull/13)
 - Moved config things in `/lib/conf/index.js`. Fixes [#2](https://github.com/IonicaBizau/cli-github/issues/2). Additional properties are appended on runtime.
 - Moved the title and description in config.
 - Fixed scopes for creating the repository
 - A smarter way to handle tokens.

### `1.2.2`
 - Fixed docs.

### `1.2.1`
 - Handle open source events (fixes [#12](https://github.com/IonicaBizau/cli-github/issues/12)).

### `1.2.0`
 - Use 2FA token if it exists (fixes [#7](https://github.com/IonicaBizau/cli-github/issues/7), see the [pull request](https://github.com/IonicaBizau/cli-github/pull/5)).
 - Fixed comment descriptions (issue comments, commit comments, [#9](https://github.com/IonicaBizau/cli-github/issues/9), [pull request](https://github.com/IonicaBizau/cli-github/pull/11))

### `1.1.0`
 - Added two-factor authentication support (fixes [#4](https://github.com/IonicaBizau/cli-github/issues/4), see the [pull request](https://github.com/IonicaBizau/cli-github/pull/5). Thanks [@remixz](https://github.com/remixz)!.

### `1.0.0`
 - Initial stable release.

### `1.0.0-betax`
 - Unstable prereleases.

## How to contribute

1. File an issue in the repository, using the bug tracker, describing the
   contribution you'd like to make. This will help us to get you started on the
   right foot.
2. Fork the project in your account and create a new branch:
   `your-great-feature`.
3. Commit your changes in that branch.
4. Open a pull request, and reference the initial issue in the pull request
   message.

## License
See the [LICENSE](./LICENSE) file.
