---
title: Netduma R2 Firmwares
linkTitle: Firmwares
---

<h2 class="mb-4">Releases</h2>
<div class="grid grid-cols-3 auto-rows-auto border-t-[1px] border-white/20">
  <div class="grid grid-cols-subgrid grid-flow-col col-span-3 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://forum.netduma.com/topic/50710-new-r2-firmware-33280/" buttonColor="primary" text="v.3.3.280" >}}
      20/03/2023
    </div>
    <div class="col-span-4 p-6">   
      <ul class="mt-0 text-text-secondary">
        <li>Wider range of games and applications supported by DumaOS (and more to come!).</li>
        <li>Hybrid VPN no longer experiences issues when switching between Wireguard and OpenVPN.</li>
				<li>DNS settings for Hybrid VPN are now retained after reboot.</li>
				<li>Fixed an issue where replacing a faulty config file for Hybrid VPN would cause functionality issues.</li>
				<li>OpenVPN logs are no longer deleted when the VPN is disabled.</li>
				<li>Various other fixes to Hybrid VPN functionality and stability.</li>
				<li>IPv6 traffic is now always categorised by QoS, allowing QoS to interact with it more reliably.</li>
				<li>Ping Heatmap no longer crashes if pinging an empty server group.</li>
				<li>Improvements to overall DumaOS stability, reducing cases where users see random reboots or disconnections.</li>
				<li>Numerous security improvements.</li>
      </ul>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://forum.netduma.com/topic/39522-new-r2-firmware-32453/" buttonColor="primary" text="v3.2.453" >}}
      09/06/2022
    </div>
    <div class="col-span-3 p-6">   
			<div>Mobile View</div>
      <ul class="mt-0 text-text-secondary">
				<li>New priority boost button - lets you temporarily prioritise any traffic type</li>
				<li>New Ping Optimiser feature - which finds the best QoS settings for your home</li>
				<li>Revamped Connection Benchmark to split out into a separate Speedtest and Ping Test</li>
			</ul>
			<ul class="mt-0 text-text-secondary">
				<li>Support for Work From Home protocols</li>
				<li>Added Data History</li>
				<li>Connection Benchmark upload result no longer affected by Congestion Control</li>
				<li>Added Hybrid-VPN fixes</li>
				<li>System-wide websocket improvements</li>
				<li>Setup process uses both desktop and mobile view to automatically configure more of DumaOS</li>
				<li>System-wide improvements to CPU and memory usage</li>
				<li>Ping Heatmap front-end fixes</li>
				<li>Improved stability of back-end processes</li>
				<li>Improved clean-up process system-wide on shutdown</li>
				<li>Improved wireless stability</li>
			</ul>
		</div>
	</div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://www.dropbox.com/s/ctjppykaasmorxp/DumaOS-R2-3.0.394.sig?dl=0" buttonColor="primary" text="v3.0.394" >}}
      02/01/2024
    </div>
    <div class="col-span-3 p-6">   
			<ul class="mt-0 text-text-secondary">
				<li>Added support for Wireguard in Hybrid VPN</li>
				<li>Added ability to use specific IPv4/IPv6 DNS in HybridVPN</li>
				<li>Fixed issue with DHCP service crashing</li>
				<li>Added better backend flash usage monitoring for preventing long-term issues</li>
				<li>Added improved configuration system allowing for faster and more stable integration of new features</li>
				<li>Fixed issue where Wi-Fi password wouldn’t match label after reset</li>
				<li>Multiple security improvements</li>
				<li>Fixed ‘Rapps not loading’ issue (Big thanks to @pollutionblues for all his help troubleshooting this)</li>
				<li>Fixed Hybrid VPN DNS leak issue</li>
				<li>System-wide GUI improvements</li>
				<li>Added cloud gaming and Work From Home categorisations for QoS</li>
				<li>Added VLAN Support</li>
				<li>Added Public IP viewable on Network Status panel - can be toggled on/off</li>
				<li>Added Set Home by address on Geo-Filter</li>
				<li>Added a Report button to the ping panel - use this to report an abnormal ping, incorrect server type, server required for online play or other (e.g. incorrect location) direct from the Geo-Filter</li>
				<li>Added Resync button to Device Manager</li>
				<li>Changed Device Manager Table View panel order</li>
				<li>Network Monitor Category Breakdown viewable by default</li>
			</ul>
		</div>
	</div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://www.dropbox.com/s/49gt1wxva9rxame/DumaOS-R2-3.0.205.sig?dl=0" buttonColor="primary" text="v3.0.205" >}}
      02/01/2024
    </div>
    <div class="col-span-3 p-6">   
			<ul class="mt-0 text-text-secondary">
				<li>System-wide GUI improvements to both cosmetics and Security</li>
				<li>Increase DHCP cache size to 10000 avoiding DHCP being filled up with only 1500 requests</li>
				<li>Improved wireless devices Traffic Prioritisation</li>
				<li>Fixed IPv6 devices not being assigned a DHCP IP sometimes</li>
				<li>Fixes for DumaOS webserver for GUI to operate smoothly</li>
				<li>Improve DPI detection services</li>
				<li>Improved Bandwidth Allocation backend</li>
			</ul>
		</div>
	</div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://www.dropbox.com/s/1krvgqi4peslusv/DumaOS-R2-3.0.179.sig?dl=0" buttonColor="primary" text="v3.0.179" >}}
      02/01/2024
    </div>
    <div class="col-span-3 p-6">
			<div>General Improvements</div>
			<ul class="mt-0 text-text-secondary">
				<li>System-wide GUI improvements.</li>
				<li>Memory usage improvements.</li>
				<li>Added new Copy to Clipboard button for information generated by Rapp Performance and Device Manager > Wi-Fi Scan (also a new addition)</li>
				<li>Fixed initial tour throwing errors if ‘Next’ clicked too early</li>
				<li>Fixed various issues with upgrade process</li>
				<li>Fixed various vulnerabilities</li>
			</ul>
			<div>Wi-Fi Improvements</div>
			<ul class="mt-0 text-text-secondary">
				<li>Improved Wi-Fi band steering</li>
				<li>Improved Wi-Fi range coverage</li>
				<li>Fixed Wi-Fi settings not preserving on firmware upgrades</li>
				<li>Fixed Wi-Fi station details displaying incorrectly if the device is disconnected</li>
				<li>Fixed 5GHz channel not starting correctly when splitting the channels</li>
				<li>Added auto Wi-Fi channel detection, picking the least noisy Wi-Fi channel to achieve better results</li>
				<li>Added Wi-Fi channel width setting for greater control</li>
				<li>Added Wi-Fi region setup to the setup wizard</li>
				<li>Added Wi-Fi radar detection DFS channels</li>
				<li>Added Wi-Fi Performance feature to devices</li>
				<li>Added Wi-Fi Scan feature</li>
				<li>Added more Wi-Fi stations information for better debugging</li>
			</ul>
			<div>Ping Heatmap</div>
			<ul class="mt-0 text-text-secondary">
				<li>Fixed Ping Heatmap displaying multiple graphs when spam-clicking</li>
			</ul>
			<div>QoS</div>
			<ul class="mt-0 text-text-secondary">
				<li>Congestion Control Auto-Setup is now less aggressive - users should see improved results</li>
				<li>Improved QoS Stability</li>
				<li>QoS now loads quicker on start-up</li>
				<li>Fixed QoS not always loading correctly</li>
				<li>Fixed QoS crashes and stability issues</li>
				<li>Fixed Congestion Control Auto-Setup layout issues when zoomed in</li>
				<li>Fixed “Applying Settings” popup appearing when Auto-Setup loads/li>
				<li>Fixed Congestion Control Auto-Setup button</li>
				<li>Fixed Auto-Setup not always setting the slider</li>
				<li>Fixed incorrect padding around auto-setup bars</li>
				<li>Fixed Auto-Setup throttling below 1%</li>
			</ul>
			<div>Connection Benchmark</div>
			<ul class="mt-0 text-text-secondary">
				<li>Fixed issues with Speed Test when WAN is disconnected</li>
				<li>Fixed Ping Under Load test not working correctly</li>
			</ul>
			<div>Device Manager</div>
			<ul class="mt-0 text-text-secondary">
				<li>Device status will update between online and offline much faster</li>
				<li>Fixed Device Manager crashes</li>
				<li>Fixed Device Manager spam messages about device status</li>
				<li>Fixed issue where devices sometimes have no name</li>
				<li>Fixed issue when adding a new device causing Rapps to fail</li>
			</ul>
			<div>Traffic Controller</div>
			<ul class="mt-0 text-text-secondary">
				<li>Fixed Traffic Controller causing DumaOS to fail loading</li>
			</ul>
			<div>Network Settings</div>
			<ul class="mt-0 text-text-secondary">
				<li>Fixed MAC cloning to update the device interface correctly</li>
				<li>Removed MAC address cloning toggle, added reset button</li>
				<li>Added more special characters for Wi-Fi password entry</li>
			</ul>
			<div>Misc</div>
			<ul class="mt-0 text-text-secondary">
				<li>Updated to use new multi-threaded webserver for faster GUI loading</li>
			</ul>
			<div>Installation instructions</div>
			<ul class="mt-0 text-text-secondary">
				<li>Download the file above</li>
				<li>Open DumaOS at 192.168.77.1 or /dumaos/</li>
				<li>Click the three dots in the top right of the interface</li>
				<li>Click Update</li>
				<li>Click ‘Select Upgrade File’ and choose the file you just downloaded</li>
				<li>Click ‘Upgrade’ and wait about 5 minutes for the update to apply</li>
				<li>Do not unplug your unit during this time!</li>
			</ul>
		</div>
	</div>	
</div>