# NC-CW


as on 19 november
still have to figure out how to give in batches.

not able to do binary cross entropy (bce) ...as the predicted output is (1,4,96,96) and the given mask is (1,96,96)

need to have a good theoretical knowledge of what dice loss, cross entropy and binary cross entropy losses are.

as on 20 November

I think we can now give in batches,
different device problem solved,
printing info partially in tqdm and pbar style.

got new dice loss implementation but need to incorporate.

plotting of losses vs step ..shows there is oscillations between loss values ...probable reason to be found out.
![image](https://user-images.githubusercontent.com/33731455/142747032-e15a42d6-4000-446b-9d74-a89e9408da7e.png)
