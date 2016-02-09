# Level 1: Identity

I: \x x

# Level 2: True, false

T: \x y x

F: \x y y


# Level 3: Not

NOT: \x F T 

# Level 4: Or, And, Xor

OR: \x y (x T (y T F))

AND: \x y (x (y T F) F)

XOR: \x y (x (y F T) (y T F))

# Level 5:

