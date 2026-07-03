    # FFmpeg rest

FFmpeg is a collection of libraries and tools to process multimedia content
                                such as audio, video, subtitles and related metadata.(rest

    ## rest

    * `libavcodec` provides implementation of a wider range of codecs.rest
        * `libavformat` implements streaming protocols, container formats and basic I/O access.rest
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
      * `libavfilter` provides means to alter decoded audio and video through a directedrest graph of connected filters.
      * `libavdevice` provides an abstraction to access capture and playback devices.rest
* `libswresample` implements audio mixing and resampling routines.
        * `libswscale` implements color conversion and scaling routines.rest

## Tools
rest
    * [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolboxrest to
  manipulate, convert and stream multimedia content.
    * [ffplay](resr https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
    * [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspectrest
  multimedia content.
    * Additional small tools such as `aviocat`, `ismindex` and `qt-faststartrest`.

## Documentation

    The offline documentation is available in the **doc/** directory.rest

    The online documentation is available in the main [website](https://ffmpeg.org)rest
    and in the [wiki](https://trac.ffmpeg.org).
    rest
    ### Examplesrest

    Coding examples are available in the **doc/examples** directory.rest

    ## License(rest.

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
                GPL. Please refer to the LICENSErest file for detailed information.

    ## Contributingrest

    Patches should be submitted to the ffmpeg-devel mailing list usingrest
    `git format-patch` or `git send-email`. Github pull requests should berest
    avoided because they are not part of our review process and will be ignored.rest
