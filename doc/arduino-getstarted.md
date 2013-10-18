Install Arduino IDE
- follow official docs

Download MicroFlo for Arduino
Open in Arduino IDE, examples -> microflo -> standalone.ino
Flash to device
-> should get blinking LED, 300 ms interval

Install MicroFlo

Change the timer interval in examples/blink.fbp to a different value, save
    microflo load examples/blink.fbp
-> LED blink interval should change on device


# FIXME: later

Install NoFlo UI
    npm install noflo-ui
    microflo runtime --port=5367

Set port to ws://localhost:5367
Change interval again, click Load/Play
-> should change on device
