# Ponic Modules
<p>Start with the basics and extend your aqua- or hydroponics sytem to fully automate and analize your garden or farm. The ponics modules can be used stand alone or in a mesh network.</p>
<p>The controlling part comes from the Arduino Nano, this simple but effective controller is easy to program and there is lots of info online.</p>

<p><strong>We are currently working on the basic controller.</strong></p>

<ul>
    <li>
        <p>
            <strong><a href="/Modpon/mini-controller">Mini Controller</a></strong>
        </p>
        <p>
            This tiny controller simply turns a 3-5v. pump on and off, it uses a mini usb for power.
        </p>
    </li>
    <li>
        <p>
            <strong><a href="/Modpon/basic-controller-hardware">Basic Controller</a></strong>
        </p>
        <p>
            A basic automation controller for hydroponics or aquaponics system. The module works stand-alone.
        Control up to 3 12v. pumps and multiple air and water sensors. 
        </p>
    </li>
    <li>
        <p>
            <strong>Hub</strong>
        </p>
        <p>
            This is the brain, it processes the information from the modules and saves evrything in the database. The controller is connected to your router
            (LAN or Wifi) and is accessible with your computer or mobile device.
        </p>
    </li>
    <li>
        <p>
            <strong>Sub Hub</strong>
        </p>
        <p>
            An arduino hub with lots of inputs for wired connections, see below.
        </p>
    </li>
    <li>
        <p>
            <strong>Fish feeder</strong>
        </p>
        <p>
            Starts a stepper motor on certain times and runs x seconds.
        </p>
    </li>
    <li>
        <p>
            <strong>Pump controller</strong>
        </p>
        <p>
            Triple-mode pump control: always on, time toggle, manual, it pumps water from the fish tank to the grow beds.
        </p>
    </li>
    <li>
        <p>
            <strong>Valve controller</strong>
        </p>
        <p>
            Turns a valve on or off, use for dripping systems
        </p>
    </li>
    <li>
        <p>
            <strong>Analyzers/ Sensors</strong>
        </p>
        <ul>
            <li>
                <p>
                    Water temperature
                </p>
            </li>
            <li>
                <p>
                    Air temperature &amp; humidity
                </p>
            </li>
            <li>
                <p>
                    Light sensor
                </p>
            </li>
            <li>
                <p>
                    PH
                </p>
            </li>
            <li>
                <p>
                    EC (electro conductivity)
                </p>
            </li>
            <li>
                <p>
                    Water quality (Na+, Ca+, F-, Cl-, Br-, I-, Cu2+, K+, Mg2+, NO3-)
                </p>
            </li>
        </ul>
    </li>
    <li>
        <p>
            <strong>Water flow (for the outlet)</strong>
        </p>
        <p>
            Measures the flow of water; to sump tank, plants, etc.
        </p>
    </li>
    <li>
        <p>
            <strong>Overflow sensor</strong>
        </p>
        <p>
            Shuts down the pump when water is flowing over the fish tanks or grow beds.
        </p>
    </li>
    <li>
        <p>
            <strong>Water level check</strong>
        </p>
        <p>
            measures distance between top and water,
        </p>
    </li>
    <li>
        <p>
            <strong>Water heater</strong>
        </p>
        <p>
            Turn water heater on if tank too cold. Check growbed and tank temperature sensors.
        </p>
    </li>
    <li>
        <p>
            <strong>Syphon activity</strong>
        </p>
        <p>
            Checks if water is going through the siphon with vibration or float sensor. Trigger alert if there's no activity.
        </p>
    </li>
    <li>
        <p>
            <strong>Grow lights</strong>
        </p>
        <p>
            Control your 12v. led grow lights, colours and timing.
        </p>
    </li>
</ul>
<p>
    <strong>Additional modules</strong>
</p>
<ul>
    <li>
        <p>
            <strong>
                Power pack
                <br/>
            </strong>
            Stack of batteries to use modules in remote places. These can be charged with solar panels.
        </p>
    </li>
    <li>
        <p>
            <strong>
                Solar panels
                <br/>
            </strong>
            Charge the battery pack.
        </p>
    </li>
    <li>
        <p>
            <strong>Wireless</strong>
            <br/>
            Control and send data from the modules to a hub with RF.
        </p>
    </li>
</ul>
