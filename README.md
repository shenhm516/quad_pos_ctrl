# quad pos ctrl
this is a position controller for quadrotor
## topic
### subscribe
/mocap_data_rigid

~/state
### publish
~/setpoint_raw/target_attitude

更改记录：
1 增加take-off和land中，arm和disarm的判据
2 取消连续刷3次起飞指令
