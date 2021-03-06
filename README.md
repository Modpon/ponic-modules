# Ponic Modules
<p>Start with the basics and extend your aqua- or hydroponics sytem to fully automate and analize your garden or farm. The ponics modules can be used stand alone or in a mesh network.</p>
<p>The controlling part comes from the Arduino Nano, this simple but effective controller is easy to program and there is lots of info online.</p>

<p><strong>We are currently working on the basic controller.</strong></p>

<h2>Modules</h2>
<ul>
    <li>
            <strong><a href="https://github.com/Modpon/mini-controller">Mini Controller</a></strong>
        <br>
            This tiny controller simply turns a 3-5v. pump on and off, it uses a mini usb for power.
    </li>
    <li>
            <strong><a href="https://github.com/Modpon/basic-controller-hardware">Basic Controller</a></strong>
        <br>
            A basic automation controller for hydroponics or aquaponics system. The module works stand-alone.
        Control up to 3 12v. pumps and multiple air and water sensors.
    </li>
    <li>
            <strong>Hub</strong>
        <br>
            This is the brain, it processes the information from the modules and saves evrything in the database. The controller is connected to your router
            (LAN or Wifi) and is accessible with your computer or mobile device.
    </li>
    <li>
            <strong>Sub Hub</strong>
        <br>
            An arduino hub with lots of inputs for wired connections, see below.
    </li>
    <li>
            <strong>Fish feeder</strong>
        <br>
            Starts a stepper motor on certain times and runs x seconds.
    </li>
    <li>
            <strong>Pump controller</strong>
<br>
            Triple-mode pump control: always on, time toggle, manual, it pumps water from the fish tank to the grow beds.
    </li>
    <li>
            <strong>Valve controller</strong>
<br>
            Turns a valve on or off, use for dripping systems
    </li>
    <li>
            <strong>Analyzers/ Sensors</strong>
        <ul>
            <li>Water temperature
            </li>
            <li>Air temperature &amp; humidity
            </li>
            <li>Light sensor
            </li>
            <li>PH
            </li>
            <li>EC (electro conductivity)
            </li>
            <li>Water quality (Na+, Ca+, F-, Cl-, Br-, I-, Cu2+, K+, Mg2+, NO3-)
            </li>
        </ul>
    </li>
    <li>
            <strong>Water flow (for the outlet)</strong>
<br>
            Measures the flow of water; to sump tank, plants, etc.
    </li>
    <li>
            <strong>Overflow sensor</strong>
<br>
            Shuts down the pump when water is flowing over the fish tanks or grow beds.
    </li>
    <li>
            <strong>Water level check</strong>
<br>
            measures distance between top and water,
    </li>
    <li>
            <strong>Water heater</strong>
<br>
            Turn water heater on if tank too cold. Check growbed and tank temperature sensors.
    </li>
    <li>
            <strong>Syphon activity</strong>
<br>
            Checks if water is going through the siphon with vibration or float sensor. Trigger alert if there's no activity.
    </li>
    <li>
            <strong>Grow lights</strong>
<br>
            Control your 12v. led grow lights, colours and timing.
    </li>
</ul>
<h3>Additional modules</h3>
<ul>
    <li>
            <strong>
                Power pack
            </strong><br/>
            Stack of batteries to use modules in remote places. These can be charged with solar panels.
    </li>
    <li>
            <strong>
                Solar panels
            </strong><br/>
            Charge the battery pack.
    </li>
    <li>
            <strong>Wireless</strong>
            <br/>
            Control and send data from the modules to a hub with RF.
    </li>
</ul>
