#persist ventures
VideoFileClip Function:
filename:
  The name of the video file, as a string or a path-like object. It can have any extension.
has_mask:
  Set this to ‘True’ if there is a mask included in the videofile.
audio:
  Set to False if the clip doesn’t have any audio or if you do not wish to read the audio.
target_resolution:
  Set to (desired_width, desired_height) to have ffmpeg resize the frames before returning them.
resize_algorithm:
  The algorithm used for resizing. Default: “bicubic.
fps_source:
  The fps value to collect from the metadata. Set by default to ‘fps.
