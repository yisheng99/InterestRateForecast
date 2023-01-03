**How to forecast interest rate using Taylor Rule model?**

Developed by economist John Taylor in 1993, the Taylor Rule is a famous formula tying a central bank's policy rate to inflation and economic growth.

The formula looks like this: forecasted_rate = neutral_rate + alpha*inflation_gap + beta*output_gap

The formula adjusts the equilibrium interest rate based on divergence in inflation and real GDP growth from the central bank's targets.

I use Python to test this model on the Fed funds rate. These are the steps I have taken to execute the the model:

Step 1. Import libraries (numpy, pandas, matplotlib) and data.

Step 2. Set the parameters of the model, ie alpha = x, beta = y, neutral_rate = z

Step 3. Calculate the forecasted_rate based on the various data input and parameters

Step 4. Plot the forecasted and actual interest rate to check the model fit (Chart 1)

**Chart 1**

![image](https://user-images.githubusercontent.com/121606452/210389260-2dd8b4c0-0414-4476-9d11-598b29a58da4.png)

Voila! Now you have your forecasted and actual interest rate. Now, note that in this sample i used very simple assumptions on the Fed's neutral rate and the parameters.

Nonetheless, you could also try this code out to forecast the interest rate on your own. Just tweak the parameters to your liking :)
