# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
<p align="center"> <img src="https://user-images.githubusercontent.com/88862384/143664552-404cf76f-a70b-40bf-9a75-b1e913a6de15.png">
  </p>
The Pr(>|t|) represents whether or not each coefficient contributes random amounts of variance to the multiple linear regression. According to this output, vehicle length and ground clearance are highly unlikely to provide random variance to the regression. The slope is not considered to be zero because the equation still has 3 coefficients that contribute to the equation overall although they may appear small or negative. Because the R squared is .71 or 71%, we consider the model to be  effective.

<br>

## Summary Statistics on Suspension Coils
<p align="center"> <img src="https://user-images.githubusercontent.com/88862384/143664558-33e7de8e-f699-4352-9970-ee2474d629cf.png">
  </p>
<p align="center"> <img src="https://user-images.githubusercontent.com/88862384/143664553-294e562e-d107-4675-98ce-7b3ce6abfae4.png">
  </p>
According to the standards set by the design specifications, as a whole, MechaCar's coils are within the appropriate range of variance. However, the variance from lot 3 is 170 which means they individually are producing faulty coils.

<br>

## T-Tests on Suspension Coils
<p align="center"> <img src="https://user-images.githubusercontent.com/88862384/143664556-5b5233b0-4407-442e-94e8-2b5d9762147e.png">
  </p>
<p align="center"> <img src="https://user-images.githubusercontent.com/88862384/143664554-c1e58305-4c78-461e-b3f2-1a48695c45e3.png">
  </p>
Overall, with a P-Value of .7925, we fail to reject the null hypothesis. Individually though, the results vary. Using random 20 vehicles from each lot sample this time, both lot 1 & 2 provide sufficient evidence to reject the null hypothesis and confirm that there is a significant difference in PSI. Lot 3 on the other hand isn't able to prove this. 
