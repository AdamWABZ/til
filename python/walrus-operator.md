# The walrus operator :=

Assigns a value inside an expression. Useful in while loops:

while chunk := f.read(1024):
    process(chunk)

Avoids reading twice or using a separate assignment line.
