# stoiczfpv
FPV Drone Builds and Betaflight Configuration 
#

## Glide 5 - Freestyle Build 

<img width="500" alt="Glide 5" src="https://github.com/hectorsvill/stoiczfpv/blob/main/images/Glide5.png">

##### Part List 

<table>
	<tr>
		<td>
			Frame
		</td>
		<td>
			HYPERLITE GLIDE 5 INCH FREESTYLE FRAME
		</td>
	</tr>
  <tr>
		<td>
			Flight Controller
		</td>
		<td>
			IFLIGHT SucceX-E mini F4 Flight controller
		</td>
	</tr>
  <tr>
		<td>
			ESCs
		</td>
		<td>
      IFLIGHT SucceX-E mini 35A 4in1 ESC
		</td>
	</tr>
  <tr>
		<td>
			Motors
		</td>
		<td>
      IFLIGHT XING-E 2306 2-6S FPV MOTOR 1700 KV
		</td>
	</tr>
  <tr>
		<td>
			Propellers
		</td>
		<td>
      HQ FREESTYLE PROP 5X4.3X3V2S 
		</td>
	</tr>
  <tr>
		<td>
			FPV Camera
		</td>
		<td>
      CADDX RATEL STARLIGHT HDR OSD 1/1.8" 1200TVL 
		</td>
	</tr>
  <tr>
    <td>
			FPV Transmitter
		</td>
		<td>
      RUSH TANK MINI VTX 5.8G SMART AUDIO 20X20 
		</td>
	</tr>
  <tr>
    <td>
			FPV Transmitter Antenna
		</td>
		<td>
      TBS TRIUMPH PRO (MMCX RHCP) 
		</td>
	</tr>
  <tr>
    <td>
			Receiver
		</td>
		<td>
      TBS CROSSFIRE NANO RX FPV LONG RANGE DRONE RECEIVER 
		</td>
	</tr>
  <tr>
    <td>
			Receiver Antenna
		</td>
		<td>
      TBS CROSSFIRE IMMORTAL T ANTENNA V2
		</td>
	</tr>
</table>


##### RUSH TANK MINI VTX 5.8G SMART AUDIO 20X20 VTX Table to enter in CLI (FCC)
```
vtxtable bands 5
vtxtable channels 8
vtxtable band 1 BOSCAM_A A FACTORY 5865 5845 5825 5805 5785 5765 5745 5725
vtxtable band 2 BOSCAM_B B FACTORY 5733 5752 5771 5790 5809 5828 5847 5866
vtxtable band 3 BOSCAM_E E FACTORY 5705 5685 5665 0 5885 5905 5925 0
vtxtable band 4 FATSHARK F FACTORY 5740 5760 5780 5800 5820 5840 5860 5880
vtxtable band 5 RACEBAND R FACTORY 5658 5695 5732 5769 5806 5843 5880 5917
vtxtable powerlevels 4
vtxtable powervalues 14 23 27 29
vtxtable powerlabels 25 200 500 800
save

```

