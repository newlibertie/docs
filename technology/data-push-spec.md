# Spec of data sent by app


Authentic video data:
    Event data:
        Mac address
        Carrier
        Device name, make, model
        Authenticated Owner/Operator ID
    Sensory data:
        Video output from all camera + microphone from a recording device (iOs and Android devices).
        Periodic sensory data:
            GPS location (latitude, longitude, altitude)
            Bluetooth neighborhood (hex-id, decibel level, is-streaming)
            Device orientation using internal compass
            Temperature
            Humidity
            Atmospheric pressure
            Time of day
            Radiation level?

