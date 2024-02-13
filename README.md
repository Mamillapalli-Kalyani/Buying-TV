# Buying-TV
a,b,c,d=map(int,input().split(" "))
CostOfA=a-(a*(c/100))
CostOfB=b-(b*(d/100))
if CostOfA<CostOfB:
  print("Buy A")
elif CostOfA == CostOfB:
  print("Buy any one")
else:
  print("Buy B")
