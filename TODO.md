# TODO

* Look for a user-controlled module that is imported/executed and
  converted into values available in the render context. This way
  users can customize themes to include custom computable values.

* How to set ID for the feed and entries such that they remain stable?
  Is canonical URL sufficient?

* File format for short-form posts (yaml with explicit content
  field). Generic approach: if content field is not defined, expect
  the next document in the file to contain the content. If content
  field is defined, then the next document, if present, is a separate
  post.

* Archive view

* Finish support for non-root-path-based installations

* Instrument with Lithoxyl

* Also upload source code/gen source code links

* --clean option (effectively removes any unused files from site/)