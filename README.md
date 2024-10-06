target = 35
Kp = 1
Ki = 1
Kd = 1 
value = light sensor 
error = target - value 
integral = error + integrsl 
derivative = error - last_error 


=> (error*Kp) + (integral*Ki) + (derivative*Kd)
