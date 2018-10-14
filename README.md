# yoho
| 序号 | 接口名称 | 方法 | 参数  | 响应 | 备注 |
| --- | --- | --- | --- | --- | --- |
| 1 | addgoods | post |  {} | {} | - |
| 2 | getgoods | post |  {} | {} | - |
| 3 | searchUser | post | {} | {} | - |
| 4 | getgoodswithuserid |  post | {} | {} | - |
| 5 | updategoods | post |  {gid （必传 ...} | {} | - |
| 6 | undercarriagegoods | post |  {gid （必传 ...} | {} | - |
| 7 | selectgoods | post |  { {bid: , goods:{{gid, count},{gid, count}}}, {bid: , goods:{{gid, count},{gid, count}}} ...} | { {bid, orderid} , {bid, orderid} } | - |
| 8 | canacelgoods |  post | bid/userid | {} | - |
| 9 | ensuregoods |  post | bid | {} | - |
| 10 | 发货 |  post | bid | {} | - |
