def draw(plus):
  t.fd(50+plus)
  t.lt(45)
  t.fd(3)
  t.rt(45)
  for i in range(45):
    t.fd(1)
    t.rt(2)
  t.rt(89)
  t.fd(10)
  t.lt(179)
  t.fd(10)
  t.rt(91)
  for i in range(45):
    t.fd(1)
    t.rt(2)
  t.rt(45)
  t.fd(3)
  t.lt(45)
  t.fd(50+plus)
  t.lt(75)
  for i in range(85):
    t.fd(1)
    t.rt(3)
  t.lt(180)
  for i in range(85):
    t.fd(1)
    t.rt(3)

for i in range(100):
  draw(i)
  t.rt(1)
