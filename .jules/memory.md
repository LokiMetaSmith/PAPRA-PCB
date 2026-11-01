## Archived: 2026-10-31

* Repository contains files for the PAPRA Printed Circuit Board Assembly (PCBA).
* Main directories include `pcb/` (containing `PaprControlPCB`) and `Drawings/`.
* Firmware programming is done via a UPDI programmer with Arduino and megaTinyCore library.
* Supported microcontrollers include various ATtiny models (e.g., ATtiny204, ATtiny404, ATtiny804, ATtiny1604, ATtiny214, ATtiny414, ATtiny814, ATtiny1614, ATtiny1624).
* The PCBA requires 12V DC power for bring-up, provides 5V regulator output for UPDI, and controls a DC blower.
* Powered by Milwaukee M12 Red Lithium Battery or 12V DC jack.
* PCBA includes a potentiometer for fan speed adjustment and LEDs for status and boot-up sequence.
