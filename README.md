from random import *
passenger = 0
cnt=0
for passenger in range(1,51):
    time = randint(5,50)
    if 5 <= time <= 15:
        i = 0
        cnt+=1
    else:
        i= " "
    print("[{0}] {1}번째 손님 (소요시간 : {2}분)" .format(i, passenger, time))

print("총 탑승승객 : {}" .format(cnt))
