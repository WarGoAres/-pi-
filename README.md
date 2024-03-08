# -pi-
#程式課問題(如何求pi的近似值)
#你會問說求這要做什麼???
#我不知道也不知道求這要幹嘛
#但有沒有辦法求有(網路上很多神人解法)
#微積分,工數就有很多求pi的方法
#蒙特卡羅法都有

nearpi = 0

for n in range(0, 100000):#級數逼近解法
    nearpi = nearpi + (-1) ** n * 1 / (2 * n + 1)

    pi_approx = 4 * nearpi
    print("Approximation of pi:", pi_approx)


