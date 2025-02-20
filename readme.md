# Design 

Here is a complate flow chart:

```mermaid
graph TB;
    Register-->Login;
    Login-->Home;
    Home-->My;
    Home-->Recharge;
    Recharge-->Recharge_History;
    Home-->Withdraw;
    Withdraw-->Withdraw_History;
    Home-->Team;
    Team-->Team_Detail;
    Home-->VIP;
    VIP-->VIP_Detail;
    My-->Recharge_History;
    My-->Withdraw_History;
    My-->History;
    My-->Bank_Setting;
    My-->Password_Change;
    My-->Logout;
```

### Preview Design

![image info](./readme/login.png)

#
![image info](./readme/register.png)

#
![image info](./readme/mine.png)

#
![image info](./readme/vip.png)

#
![image info](./readme/team.jpg)

#
![image info](./readme/recharge.png)
