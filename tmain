#!/bin/bash

if ! tmux has-session -t main 2>/dev/null; then
    tmux new-session -d -s main
fi
tmux attach -t main
