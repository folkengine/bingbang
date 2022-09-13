#!/usr/bin/env bash

cmake -S . -B build
cmake --build build --clean-first
cd build || exit
make test
cd ..
