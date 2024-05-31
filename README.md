# RTC_timer_4load_control
based on https://github.com/embeddedlab786/Real_Time_Clock_based_4Load_Control

mainly changes than original:
- after restart outputs remain in desired states (read info from EEPROM and check de hour)
- LCD1602 with i2c interface (LCD 1602 can be easy activad instead i2c)
- outputs control can be with normal or inverse logical (normal logical: HIGH = activate output control, LOW = deactivate, inverse/negate logical: HIGH - deactivate, LOW = activate)
  * chinese relay used inverse/negate logical

video: https://youtu.be/BJiRevy1c9w
