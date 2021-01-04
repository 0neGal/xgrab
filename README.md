## What is xgrab

Xgrab, is a simple utility which extracts resources and variables from your Xresources. 

## How to?

`git clone https://github.com/0neGuyDev/xgrab && cd xgrab`

`chmod +x xgrab`

And then move `xgrab` into some file that's in your `PATH`

After that make sure `xgrab -m` gets run every so often, it is used to make the cache for `xgrab`, in the future this will be handled automatically by `xgrab`

## Why?

You'd think to just use `xgetres` however as the name suggests it can only get resources and not variables, a big deal breaker due to how my Xresources is set up. So I had to create my own tool.
