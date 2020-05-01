# Explore Labs GPS Receiver - ublox MAX-M8Q

<p>The Global Positioning System (GPS) is a satellite-based navigation system made up of a network of 24 or more satellites. Explore Labs GPS Receiver is a 72-channel device based on the uBlox 8th generation chipset that captures those signals and provides accurate location and time information. It has an operating voltage of 3.3V to 5.5V, a high quality ceramic patch antenna on board, and connects to your system via TTL serial broken out on 2.54 cm breadboard compatible pads.</p>

<p><strong>Design Features:</strong></p>
<ul>
    <li>Upto 18 Hz update rate for GPS-only mode.</li>
    <li>40 square mm Ground Plane for better antenna gain and directivity.</li>
    <li>External I2C EEPROM for receiver configuration storage</li>
    <li>Backup battery as Supercapacitor for efficient warm start and storage of settings. Currently provides backup time of approx 10 seconds.</li>
    <li>Power Input: 3.3V to 5.5V Input. Or, If connected to an IMU 9 DOF AHRS, may be powered by a Single-cell Lithium Polymer battery.</li>
    <li>1 TTL UART port @ 3.3V. Use a Logic Level converter in between if using a 5V device like an Arduino Uno.</li>
    <li>Power LED - Red and 1PPS Timepulse LED - Blue</li>
    <li>JST-SH six pin horizontal connector - 1.0mm pitch (EM-406, EM-506 compatibile).</li>
    <li>Dimensions: 40 mm x 40 mm x 8.5 mm</li>
    <li>Weight: 16 gram</li>
    <li>Fully assembled and ready to use.</li>
    <li>Supports direct connection with <a title="Explore Labs IMU 9 DOF AHRS With Pressure / Altitude / Humidity / Temperature Sensor" href="https://github.com/udawat/IMU-9DoF-AHRS" target="_blank">Explore Labs IMU 9 DOF AHRS</a>.</li>
    <li>Code library: <a title="Tiny GPS" href="http://github.com/mikalhart/TinyGPS/" target="_blank">TinyGPS</a>.</li>
</ul>

<p><strong>Technical Specifications:</strong></p>
<ul>
    <li>72-channel u-blox M8 engine</li>
    <li>Tracking & Navigation Sensitivity for GPS & GLONASS: –167 dBm</li>
    <li>Horizontal position accuracy: 2.5m CEP</li>
    <li>Time-To-First-Fix for GPS & GLONASS (Cold Start) : 26s (Open Sky)</li>
    <li>Maximum Navigation Update Rate:
        <ul>
            <li>For GPS & GLONASS: 10Hz</li>
            <li>For GPS only: 18Hz</li>
        </ul>
    </li>
</ul>

<p><strong>Applications:</strong></p>
<ul>
    <li>Can be used in UAVs or Hot Air Balloon (HAB) projects.</li>
    <li>Can be used for evaluating the ublox MAX positioning module.</li>
    <li>Vehicle Tracking System and as Fleet Management for Logistics.</li>
    <li>Geocaching - Treasure Hunt.</li>
</ul>

<p><strong>Documents:</strong></p>
<ul>
    <li>Data Sheet: <a title="u-blox MAX-M8" href="https://www.u-blox.com/sites/default/files/MAX-M8_DataSheet_%28UBX-13004644%29.pdf" target="_blank">u-blox MAX-M8</a></li>
</ul>
