###Bash Crawl Log
#!/bin/bash
#
# If you are reading this, you have wandered out of bounds
# and are reading the code that drives the game.
#
#                    Congratulations!
#
# Learning Linux is all about curiosity, so read this code and see
# if you can figure out what it does.
#
# When you're ready to continue playing the game, though, stick to
# the scrolls. If you're stuck, go to Gitlab and create an issue.
# We're happy to provide hints.
# 
echo
if ! grep  --quiet --only-matching coins <<< $I; then
    cat << EOF
You have found a stash of **coins**!  They are old and worn
with age,  but they still gleam in the magickal light
emanating from your eyes.

Prefix this item to your inventory:

export I=coins,\$I

Remember, you can check your inventory:

echo \$I

EOF
else
    echo "This treasure has already been taken."
    echo
fi
