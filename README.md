# Lua Extensions

This adds syntax inspired by Groovy's spread and safe access operators to Lua 5.2.3

for example

local tbl = {{a=1}, {a=2}, {a=3}}
tbl*.a --> {1, 2, 3}

local a = {b="test"}
a?.b --> "test"
a?.c --> nil

