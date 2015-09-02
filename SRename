#!/bin/bash
# srename

echo "What's the name of the show?: "
read show

echo "What Season of the show is this?: "
read s

FILES=./*
i=1
for f in $FILES
do
	mv "$f" "$show S$(printf %02d $s)E$(printf %02d $i).mkv"
	((i++))
done
