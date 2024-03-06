# first_repeating_character
t=int(input())
s=input()
for i in range(len(s)):
  if s[i] in s[i+1:]:
    print(s[i])
    break
else:
  print(".")
  
#for different test cases
t=int(input())
for _ in range(t):
  s=input()
  for i in range(len(s)):
    if s[i] in s[i+1:]:
      print(s[i])
      break
  else:
    print(".")
  
