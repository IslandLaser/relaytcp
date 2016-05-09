# tcprelay-
python3 module for SainSmart iMatic TCP 8 Channel Relay

import relaytcp
import _thread

examples:
# turn all relays on:
_thread.start_new_thread(relaytcp.TCPrelayDotFour, ("all","on"))
# turn all relays off:
_thread.start_new_thread(relaytcp.TCPrelayDotFour, ("all","off"))
# turn relay 3 on:
_thread.start_new_thread(relaytcp.TCPrelayDotFour, ("3","on"))
# turn relay 3 off:
_thread.start_new_thread(relaytcp.TCPrelayDotFour, ("3","off"))
