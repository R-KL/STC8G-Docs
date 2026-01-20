# Pin Configuration
![Pinout Diagram](pinout.svg)
[Download SVG](pinout.svg)
<table>
<thead>
    <tr>
        <th>Pin</th>
        <th>Name</th>
        <th>Type</th>
        <th>Description</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td rowspan="12">1</td>
        <td><strong>P5.4</strong></td>
        <td>I/O</td>
        <td>Standard I/O port</td>
    </tr>
    <tr>
        <td>RST</td>
        <td>I</td>
        <td>Reset pin</td>
    </tr>
    <tr>
        <td>MCLKO</td>
        <td>O</td>
        <td>Master clock output</td>
    </tr>
    <tr>
        <td>INT2</td>
        <td>I</td>
        <td>External interrupt 2</td>
    </tr>
    <tr>
        <td>T0</td>
        <td>I</td>
        <td>Timer0 external input</td>
    </tr>
    <tr>
        <td>T1CLKO</td>
        <td>O</td>
        <td>Clock out of timer 1</td>
    </tr>
    <tr>
        <td>RxD_3</td>
        <td>I</td>
        <td>Serial input of UART1</td>
    </tr>
    <tr>
        <td>MOSI</td>
        <td>I/O</td>
        <td>Master Output/Slave Input of SPI</td>
    </tr>
    <tr>
        <td>SCL_2</td>
        <td>I/O</td>
        <td>Serial Clock line of I2C</td>
    </tr>
    <tr>
        <td>ADC4</td>
        <td>I</td>
        <td>ADC analog input 4</td>
    </tr>
    <tr>
        <td>CCP2</td>
        <td>I/O</td>
        <td>PCA Capture / High-speed Output</td>
    </tr>
    <tr>
        <td>CCP2_2</td>
        <td>I/O</td>
        <td>PCA Capture / High-speed Output</td>
    </tr>
    <tr>
        <td rowspan="2">2</td>
        <td class="vcc">VCC</td>
        <td>PWR</td>
        <td>Power Supply</td>
    </tr>
    <tr>
        <td class="vcc">AVCC</td>
        <td>PWR</td>
        <td>ADC Power Supply</td>
    </tr>
    <tr>
        <td rowspan="10">3</td>
        <td><strong>P5.5</strong></td>
        <td>I/O</td>
        <td>Standard I/O port</td>
    </tr>
    <tr>
        <td>INT3</td>
        <td>I</td>
        <td>External interrupt 3</td>
    </tr>
    <tr>
        <td>T1</td>
        <td>I</td>
        <td>Timer1 external input</td>
    </tr>
    <tr>
        <td>T0CLKO</td>
        <td>O</td>
        <td>Clock out of timer 0</td>
    </tr>
    <tr>
        <td>TxD_3</td>
        <td>O</td>
        <td>Serial output of UART 1</td>
    </tr>
    <tr>
        <td>SS</td>
        <td>I</td>
        <td>Slave selection of SPI</td>
    </tr>
    <tr>
        <td>SDA_2</td>
        <td>I/O</td>
        <td>Serial data line of I2C</td>
    </tr>
    <tr>
        <td>ADC5</td>
        <td>I</td>
        <td>ADC analog input 5</td>
    </tr>
    <tr>
        <td>ECI / ECI_2</td>
        <td>I</td>
        <td>External pulse input of PCA</td>
    </tr>
    <tr>
        <td>CCP2_3</td>
        <td>I/O</td>
        <td>PCA Capture / High-speed Output</td>
    </tr>
    <tr>
        <td rowspan="2">4</td>
        <td>GND</td>
        <td>GND</td>
        <td>Ground</td>
    </tr>
    <tr>
        <td>AGND</td>
        <td>GND</td>
        <td>ADC Ground</td>
    </tr>
    <tr>
        <td rowspan="4">5</td>
        <td>P3.0</td>
        <td>I/O</td>
        <td>Standard IO port</td>
    </tr>
    <tr>
        <td>RxD</td>
        <td>I</td>
        <td>Serial input of UART1</td>
    </tr>
    <tr>
        <td>INT4</td>
        <td>I</td>
        <td>External interrupt 4</td>
    </tr>
    <tr>
        <td>ADC0</td>
        <td>I</td>
        <td>ADC analog input 0</td>
    </tr>
    <tr>
        <td rowspan="6">6</td>
        <td>P3.1</td>
        <td>I/O</td>
        <td>Standard IO port</td>
    </tr>
    <tr>
        <td>TxD</td>
        <td>O</td>
        <td>Serial output of UART 1</td>
    </tr>
    <tr>
        <td>ADC1</td>
        <td>I</td>
        <td>ADC analog input 1</td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>ECI_3</td>
        <td>I</td>
        <td>External pulse input of PCA</td>
    </tr>
    <tr>
        <td>CCP0_2</td>
        <td>I/O</td>
        <td>Capture of external signal/High-speed Pulse output of PCA</td>
    </tr>
    <tr>
        <td rowspan="8">7</td>
        <td>P3.2</td>
        <td>I/O</td>
        <td>Standard IO port</td>
    </tr>
    <tr>
        <td>INT0</td>
        <td>I</td>
        <td>External interrupt 0</td>
    </tr>
    <tr>
        <td>SCLK</td>
        <td>I/O</td>
        <td>Serial Clock of SPI</td>
    </tr>
    <tr>
        <td>SCL</td>
        <td>I/O</td>
        <td>Serial Clock line of I2C</td>
    </tr>
    <tr>
        <td>RxD_2</td>
        <td>I</td>
        <td>Serial input of UART1</td>
    </tr>
    <tr>
        <td>ADC2</td>
        <td>I</td>
        <td>ADC analog input 2</td>
    </tr>
    <tr>
        <td>CCP0</td>
        <td>I/O</td>
        <td>Capture of external signal/High-speed Pulse output of PCA</td>
    </tr>
    <tr>
        <td>CCP0_3</td>
        <td>I/O</td>
        <td>Capture of external signal/High-speed Pulse output of PCA</td>
    </tr>
    <tr>
        <td rowspan="9">8</td>
        <td>P3.3</td>
        <td>I/O</td>
        <td>Standard IO port</td>
    </tr>
    <tr>
        <td>INT1</td>
        <td>I</td>
        <td>External interrupt 1</td>
    </tr>
    <tr>
        <td>MISO</td>
        <td>I/O</td>
        <td>Master Iutput/Slave Onput of SPI</td>
    </tr>
    <tr>
        <td>SDA</td>
        <td>I/O</td>
        <td>Serial data line of I2C</td>
    </tr>
    <tr>
        <td>TxD_2</td>
        <td>O</td>
        <td>Serial output of UART 1</td>
    </tr>
    <tr>
        <td>ADC3</td>
        <td>I</td>
        <td>ADC analog input 3</td>
    </tr>
    <tr>
        <td>CCP1</td>
        <td>I/O</td>
        <td>Capture of external signal/High-speed Pulse output of PCA</td>
    </tr>
    <tr>
        <td>CCP1_2</td>
        <td>I/O</td>
        <td>Capture of external signal/High-speed Pulse output of PCA</td>
    </tr>
    <tr>
        <td>CCP1_3</td>
        <td>I/O</td>
        <td>Capture of external signal/High-speed Pulse output of PCA</td>
    </tr>
</tbody>
</table>