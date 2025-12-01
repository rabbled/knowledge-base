---
title: Netduma R3 Firmwares
linkTitle: Firmwares
---

The Netduma R3 has an automatic update system which will appear on the DumaOS frontend whenever a new firmware is available for you. If you wish to download a firmware manually or return to an older version, you can download the files below.

The manual upgrade tool can be found in the Troubleshooting section of Settings.

<h2 class="mb-4">Releases</h2>
<div class="grid grid-cols-3 auto-rows-auto border-t-[1px] border-white/20">
  <div class="grid grid-cols-subgrid grid-flow-col col-span-3 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://forum.netduma.com/topic/58012-new-r3-firmware-dumaos-40540/" buttonColor="primary" text="v.4.0.540" >}}
      04/02/2025
    </div>
    <div class="col-span-4 p-6">   
      <ul class="mt-0 text-text-secondary">
          <li>
            <strong>Behavioural Identification</strong> a new feature which identifies traffic based on the way it behaves. This allows us to categorise and prioritise traffic which hasn't yet been added to our DPI database, ensuring day one support for new games. It can also assume and categorise encrypted traffic based on the way that it behaves, which means that, for the first time ever, we can prioritise Gaming, Streaming and Video Calls even while you're using a VPN
          </li>
        	<li>
            <strong>New Themes</strong> have been added to DumaOS, you can now pick from Traditional Red, Gamer Green, Baby Blue or Cherry Pink
          </li>
          <li>
            <strong>WPS Support</strong> has been added. Press the WPS button on the back of your R3 to start pairing mode for 2 minutes.
          </li>
          <li>
            <strong>Translations</strong> have been added to the UI, you can now set your DumaOS to Chinese, Dutch, Spanish, French, Hungarian, Italian, Polish, Portuguese, Turkish and German.
            <ul>
              <li>
                If there are any incorrect translations, you can report them in the change language page.
              </li>
            </ul>
          </li>
          <li>
            <strong>LAN Disconnections</strong> have been fixed, you shouldn’t be getting random drop-outs for wired devices anymore.
          </li>
          <li>
            <strong>Ping Optimiser</strong> has been overhauled and should be quicker and more stable than before.
          </li>
          <li>
            <strong>WiFi Auto Channel Selection</strong> has been improved, you'll get better speeds over WiFi.
          </li>
          <li>
            <strong>PPPoE VLAN compatibility</strong> has been fixed, you can now use both PPPoE login and VLAN tags at the same time and everything will work.
          </li>
          <li>
            <strong>Memory leaks</strong> have been fixed, your unit should no longer have to restart because of memory build up.
          </li>
          <li>
            <strong>LAN IPs</strong> were sometimes not being assigned before, this is fixed now.
          </li>
          <li>
            <strong>Many various frontend fixes.</strong>
          </li>
          <li>
            <strong>Various Stability and Security Fixes</strong>
          </li>
        </ul>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-3 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://forum.netduma.com/topic/57039-new-r3-firmware-dumaos-40290/" buttonColor="primary" text="v.4.0.290" >}}
      02/10/2024
    </div>
    <div class="col-span-4 p-6">   
      <div>Geo-Filter 2.0 improvements</div>
      <ul class="mt-0 text-text-secondary">
        <li>You can now set your Geo-Filter radius using countries through the custom Geo-Filter radius.</li>
        <li>Improved reliability of getting games inside your radius</li>
      </ul>
      <div>Memory usage improvements</div>
      <ul class="mt-0 text-text-secondary">
        <li>Improvements made to fix issues with the UI not loading</li>
      </ul>
      Bugfix for SmartBOOST causing loss of total bandwidth speed over time.<br>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://forum.netduma.com/topic/56107-new-r3-firmware-40236/" buttonColor="primary" text="v.4.0.236" >}}
      09/07/2024
    </div>
    <div class="col-span-3 p-6">   
      <ul class="mt-0 text-text-secondary">
        <li>Improvements to Geo-Filter stability</li>
        <li>SmartBOOST compatibility with VLAN improved</li>
        <li>VLAN stability improved</li>
        <li>YouTube detection fixed</li>
        <li>Memory usage improvements</li>
        <li>Improvements to IPv6 support</li>
        <li>IPv6 disabled by default after Factory Reset</li>
        <li>Steady Ping Expert Mode fixed</li>
        <li>Steady Ping disabled by default after Factory Reset</li>
        <li>Many small frontend improvements</li>
      </ul>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://forum.netduma.com/applications/core/interface/file/attachment.php?id=41720&key=c7ef49cfa27931fba39babdc31adb17f" buttonColor="primary" text="v.4.0.219" >}}
      05/06/2024
    </div>
    <div class="col-span-3 p-6">   
      <ul class="mt-0 text-text-secondary">
        <li>Hybrid-VPN added</li>
        <li>Improved performance of SmartBOOST</li>
        <li>Improved performance of Steady Ping</li>
        <li>Improved performance of Geo-Filter</li>
        <li>Ping graph appears more frequently</li>
        <li>Ping Optimiser reliability improvements</li>
        <li>Chromecast/AirPlay compatibility fixed</li>
        <li>UPnP relay added (no more double NAT)</li>
        <li>Increased maximum speeds</li>
        <li>Improved compatibility with IPv6 and PPPoE</li>
        <li>Optimisations to improve memory usage</li>
        <li>Many other smaller bug fixes</li>
      </ul>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://drive.google.com/file/d/1hoOdOxJ9Ve9JZB1yUOiLcLqRlJnL5-bp/view?usp=sharing" buttonColor="primary" text="v.4.0.21" >}}
      02/01/2024
    </div>
    <div class="col-span-3 p-6">   
      <ul class="mt-0 text-text-secondary">
        <li>VLAN compatibility fixed</li>
      </ul>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://drive.google.com/file/d/19glLDdlx-Nb1k9MB5GifHMIvyvJvfDTn/view?usp=sharing" buttonColor="primary" text="v.4.0.19" >}}
      02/01/2024
    </div>
    <div class="col-span-3 p-6">   
      <ul class="mt-0 text-text-secondary">
        <li>PPPoE Credentials can now be entered in Setup Wizard without issue</li>
        <li>Setup Wizard can now be completed without WAN access</li>
        <li>Small frontend improvements, styling fixes</li>
      </ul>
    </div>
  </div>
  <div class="grid grid-cols-subgrid grid-flow-col col-span-4 divide-x divide-white/20 border-b-[1px] border-white/20">
    <div class="py-6 pr-6 flex flex-col col-span-1 gap-4">
      {{< netduma/button link="https://drive.google.com/file/d/11j913tnodzS5TKASdxtKpBI4KQ_no1ec/view?usp=sharing" buttonColor="primary" text="v.4.0.16" >}}
      02/01/2024
    </div>
    <div class="col-span-3 p-6">   
      <ul class="mt-0 text-text-secondary">
        <li>Launch firmware</li>
      </ul>
    </div>
  </div>
</div>