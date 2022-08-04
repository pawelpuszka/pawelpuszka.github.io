# COMPUTER STORE DATABASE SCHEMA
### Designed by Paweł Puszka

<html>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1"  width="2114" height="1192">
<defs id="dmw_defs" >
<svg id="fk_sym" viewBox="0 0 48.665 48.665" style="enable-background:new 0 0 48.665 48.665;" >
<g>
<path d="M40.332,31.592c-2.377,0-4.515,1-6.033,2.598l-17.737-8.686c0.061-0.406,0.103-0.82,0.103-1.246    c0-0.414-0.04-0.818-0.098-1.215l17.711-8.589c1.519,1.609,3.666,2.619,6.054,2.619c4.603,0,8.333-3.731,8.333-8.333    c0-4.603-3.73-8.333-8.333-8.333s-8.333,3.73-8.333,8.333c0,0.414,0.04,0.817,0.098,1.215l-17.709,8.589    c-1.519-1.609-3.666-2.619-6.054-2.619C3.73,15.925,0,19.656,0,24.258c0,4.603,3.73,8.333,8.333,8.333    c2.377,0,4.515-1,6.033-2.596l17.736,8.685c-0.062,0.406-0.104,0.82-0.104,1.245c0,4.604,3.73,8.333,8.333,8.333    s8.333-3.729,8.333-8.333C48.665,35.322,44.935,31.592,40.332,31.592z" fill="#13bf3b"/>
</g>
</svg>
<svg id="pk_sym" viewBox="0 0 480.509 480.509" style="enable-background:new 0 0 480.509 480.509;" >
<g>
<path d="M418.119,331.046c4.094,4.374,7.766,8.186,10.996,11.416c3.237,3.238,6.714,6.376,10.427,9.422   c3.71,3.042,6.427,4.568,8.135,4.568c3.241,0,9.517-4.661,18.843-13.99c9.328-9.321,13.989-15.604,13.989-18.842   c0-1.523-2.714-5.421-8.138-11.704c-5.421-6.276-12.364-13.702-20.838-22.271c-8.473-8.565-16.703-16.744-24.694-24.55   c-8.001-7.81-15.8-15.373-23.417-22.703c-7.611-7.327-11.992-11.56-13.135-12.703c-1.902-1.902-4.093-2.853-6.563-2.853   c-3.237,0-9.521,4.661-18.843,13.988c-9.328,9.322-13.989,15.605-13.989,18.843c0,1.711,1.522,4.421,4.568,8.138   c3.046,3.71,6.188,7.187,9.421,10.424c3.23,3.23,7.047,6.899,11.42,10.992c4.377,4.093,6.848,6.423,7.423,6.995l-27.408,27.404   L254.954,222.268c24.94-33.498,37.408-68.236,37.408-104.211c0-31.024-9.761-56.293-29.263-75.801   c-19.512-19.511-44.778-29.265-75.805-29.265c-30.454,0-60.244,9.042-89.363,27.119c-29.121,18.083-52.727,41.686-70.808,70.808   C9.042,140.038,0,169.828,0,200.28c0,31.029,9.753,56.286,29.265,75.803c19.511,19.517,44.777,29.27,75.801,29.27   c35.976,0,70.71-12.467,104.212-37.407l191.574,191.579c5.332,5.328,11.796,7.994,19.417,7.994c7.991,0,15.704-3.72,23.12-11.14   c7.426-7.426,11.143-15.129,11.143-23.127c0-7.617-2.666-14.092-7.994-19.417l-62.811-62.811l27.405-27.404   C411.699,324.195,414.033,326.666,418.119,331.046z M221.556,161.458c-10.656,10.657-23.601,15.987-38.828,15.987   c-7.996,0-15.896-1.812-23.7-5.43c3.617,7.808,5.426,15.706,5.426,23.7c0,15.229-5.327,28.171-15.987,38.828   c-10.66,10.655-23.606,15.986-38.831,15.986c-15.227,0-28.168-5.325-38.828-15.986c-10.657-10.657-15.987-23.599-15.987-38.828   c0-15.227,5.327-28.171,15.987-38.828C81.464,146.23,94.409,140.9,109.636,140.9c7.992,0,15.893,1.809,23.695,5.424   c-3.616-7.804-5.424-15.706-5.424-23.699c0-15.227,5.327-28.171,15.987-38.828c10.66-10.657,23.604-15.987,38.831-15.987   c15.227,0,28.171,5.327,38.828,15.987c10.657,10.66,15.987,23.601,15.987,38.828C237.539,137.852,232.209,150.797,221.556,161.458z   " fill="#ff8345"/>
</g>
</svg>
<svg id="uk_sym" viewBox="0 0 490 490" style="enable-background:new 0 0 490 490;" >
<g>
	<polygon points="236.99,11.41 0,246.348 236.99,478.678 236.99,350.609 129.864,245 236.99,139.391  " fill="#0064fb"/>
<polygon points="253.01,478.59 490,243.651 253.01,11.322 253.01,139.391 360.136,245 253.01,350.609  " fill="#0064fb"/>
</g>
</svg>
<svg id="link_sym" viewBox="0 0 1000 900" style="enable-background:new 0 0 1000 900;" >
<g>
<path fill="black" d="M660.224 422.656c6.976 16.192-0.512 35.008-16.768 42.048-16.128 6.976-34.944-0.448-41.984-16.768-8.448-19.776-20.736-37.696-36.224-53.248-64.64-64.64-177.344-64.64-241.92 0l-145.216 145.28c-66.688 66.688-66.688 175.232 0 241.984 66.688 66.688 175.104 66.752 241.92 0l92.8-92.864c12.48-12.48 32.768-12.48 45.248 0s12.48 32.768 0 45.248l-92.8 92.864c-91.648 91.648-240.832 91.52-332.416 0-91.712-91.648-91.712-240.832 0-332.48l145.216-145.28c44.352-44.416 103.424-68.864 166.272-68.864s121.792 24.448 166.208 68.864c21.248 21.312 38.016 45.952 49.664 73.216zM891.136 401.344l-145.216 145.216c-88.768 88.832-243.712 88.832-332.416 0-21.312-21.312-38.080-45.952-49.728-73.216-7.040-16.256 0.448-35.072 16.704-42.048 16.064-6.784 35.008 0.512 41.984 16.768 8.512 19.776 20.8 37.696 36.288 53.248 64.64 64.64 177.344 64.64 241.92 0l145.216-145.216c66.688-66.688 66.688-175.232 0-241.984-66.752-66.624-175.168-66.688-241.92 0l-92.8 92.864c-12.48 12.48-32.768 12.48-45.248 0s-12.48-32.768 0-45.248l92.8-92.864c45.824-45.824 105.984-68.736 166.208-68.736s120.448 22.912 166.272 68.736c91.584 91.648 91.584 240.768-0.064 332.48z" />
</g>
</svg>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath14_0_">
<rect x="0" y="0" width="268" height="88" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath17_0_">
<rect x="0" y="0" width="254" height="136" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath18_0_">
<rect x="0" y="0" width="314" height="150" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath12_0_">
<rect x="0" y="0" width="221" height="136" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath10_0_">
<rect x="0" y="0" width="248" height="108" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath13_0_">
<rect x="0" y="0" width="262" height="108" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath11_0_">
<rect x="0" y="0" width="257" height="136" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath19_0_">
<rect x="0" y="0" width="298" height="164" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath9_0_">
<rect x="0" y="0" width="358" height="150" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath21_0_">
<rect x="0" y="0" width="250" height="108" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath24_0_">
<rect x="0" y="0" width="280" height="122" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath15_0_">
<rect x="0" y="0" width="249" height="88" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath23_0_">
<rect x="0" y="0" width="234" height="122" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath20_0_">
<rect x="0" y="0" width="239" height="88" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath16_0_">
<rect x="0" y="0" width="231" height="88" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath25_0_">
<rect x="0" y="0" width="214" height="88" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath2_0_">
<rect x="0" y="0" width="254" height="74" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath27_0_">
<rect x="0" y="0" width="282" height="207" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath22_0_">
<rect x="0" y="0" width="266" height="164" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath3_0_">
<rect x="0" y="0" width="229" height="178" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath5_0_">
<rect x="0" y="0" width="230" height="89" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath26_0_">
<rect x="0" y="0" width="354" height="206" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath6_0_">
<rect x="0" y="0" width="268" height="193" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath7_0_">
<rect x="0" y="0" width="252" height="165" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath4_0_">
<rect x="0" y="0" width="223" height="74" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath8_0_">
<rect x="0" y="0" width="342" height="192" />
</clipPath>
<clipPath clipPathUnits="userSpaceOnUse" id="clipPath1_0_">
<rect x="0" y="0" width="261" height="129" />
</clipPath>
</defs>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1883 824 L1841 824" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1883 824 1877 827 1877 821" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1841.0 818.0 L1853.0 824.0 L1841.0 830.0 M1853.5999994277954 818.0 L1853.5999994277954 830.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1644 262 L1644 329" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1644 262 1647 268 1641 268" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1638.0 329.0 L1644.0 317.0 L1650.0 329.0 M1638.0 316.4000005722046 L1650.0 316.4000005722046" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1212 907 L1212 1028" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1212 907 1215 913 1209 913" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1206.0 1028.0 L1212.0 1016.0 L1218.0 1028.0 M1206.0 1015.4000005722046 L1218.0 1015.4000005722046" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1884 928 L1841 928" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1884 928 1878 931 1878 925" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1841.0 922.0 L1853.0 928.0 L1841.0 934.0 M1853.5999994277954 922.0 L1853.5999994277954 934.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M359 800 L309 804" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="359 800 353 803 353 797" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M315.0 798.0 L315.0 810.0 M320.3999996185303 798.0 L320.3999996185303 810.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M948 149 L710 149" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="948 149 942 152 942 146" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M710.0 143.0 L722.0 149.0 L710.0 155.0 M722.5999994277954 143.0 L722.5999994277954 155.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M613 908 L686 940" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="613 908 619 908 617 912" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M684.0 945.0 L676.0 936.0 L688.0 935.0 M673.5 940.8000001907349 L677.5 930.8000001907349" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1688 1019 L1688 950" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1688 1019 1685 1013 1691 1013" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1694.0 950.0 L1688.0 962.0 L1682.0 950.0 M1694.0 962.5999994277954 L1682.0 962.5999994277954" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M613 807 L676 807" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="613 807 619 804 619 810" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M676.0 813.0 L664.0 807.0 L676.0 801.0 M663.4000005722046 813.0 L663.4000005722046 801.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1069 1056 L1000 1056" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1069 1056 1063 1059 1063 1053" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1006.0 1050.0 L1006.0 1062.0 M1011.3999996185303 1050.0 L1011.3999996185303 1062.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1840 347 L1781 347" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1840 347 1834 350 1834 344" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1787.0 341.0 L1787.0 353.0 M1792.3999996185303 341.0 L1792.3999996185303 353.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M554 785 L554 626" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="554 785 551 779 557 779" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M560.0 626.0 L554.0 638.0 L548.0 626.0 M560.0 638.5999994277954 L548.0 638.5999994277954" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1191 819 L1191 730" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1191 819 1188 813 1194 813" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1197.0 730.0 L1191.0 742.0 L1185.0 730.0 M1197.0 742.5999994277954 L1185.0 742.5999994277954" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M481 152 L425 152" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="481 152 475 155 475 149" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M425.0 146.0 L437.0 152.0 L425.0 158.0 M437.5999994277954 146.0 L437.5999994277954 158.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1966 430 L1966 366" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1966 430 1963 424 1969 424" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1972.0 366.0 L1966.0 378.0 L1960.0 366.0 M1972.0 378.5999994277954 L1960.0 378.5999994277954" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M597 446 L597 490" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="597 446 600 452 594 452" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M591.0 490.0 L597.0 478.0 L603.0 490.0 M591.0 477.4000005722046 L603.0 477.4000005722046" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M948 204 L705 324" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="948 204 944 208 942 204" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M703.0 319.0 L715.0 320.0 L707.0 329.0 M713.5 314.80000019073486 L717.5 324.80000019073486" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1966 519 L1966 584" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1966 519 1969 525 1963 525" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1960.0 578.0 L1972.0 578.0 M1960.0 572.6000003814697 L1972.0 572.6000003814697" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1218 473 L1218 538" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1218 473 1221 479 1215 479" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1212.0 538.0 L1218.0 526.0 L1224.0 538.0 M1212.0 525.4000005722046 L1224.0 525.4000005722046" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1088 704 L1034 704" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1088 704 1082 707 1082 701" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1040.0 698.0 L1040.0 710.0 M1045.3999996185303 698.0 L1045.3999996185303 710.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1514 248 L1348 314" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1514 248 1510 252 1508 248" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1346.0 309.0 L1358.0 310.0 L1350.0 319.0 M1356.5 304.80000019073486 L1360.5 314.80000019073486" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M271 211 L271 303" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="271 211 274 217 268 217" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M265.0 297.0 L277.0 297.0 M265.0 291.6000003814697 L277.0 291.6000003814697" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1647 522 L1647 744" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1647 522 1650 528 1644 528" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1641.0 744.0 L1647.0 732.0 L1653.0 744.0 M1641.0 731.4000005722046 L1653.0 731.4000005722046" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1487 753 L1430 723" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1487 753 1481 753 1483 749" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1437.0 720.0 L1433.0 730.0 M1441.5 721.7999999523163 L1437.5 731.7999999523163" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M359 896 L331 896" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="359 896 353 899 353 893" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M337.0 890.0 L337.0 902.0 M342.3999996185303 890.0 L342.3999996185303 902.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1514 168 L1182 168" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1514 168 1508 171 1508 165" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1182.0 162.0 L1194.0 168.0 L1182.0 174.0 M1194.5999994277954 162.0 L1194.5999994277954 174.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M377 785 L377 467" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="377 785 374 779 380 779" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M383.0 467.0 L377.0 479.0 L371.0 467.0 M383.0 479.5999994277954 L371.0 479.5999994277954" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-width="1" d="M1489 950 L1357 1028" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1489 950 1485 955 1483 951" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1359.0 1020.0 L1365.0 1030.0 M1363.5 1017.3000001907349 L1369.5 1027.3000001907349" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M494 990 L494 921" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="494 990 491 984 497 984" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M500.0 921.0 L494.0 933.0 L488.0 921.0 M500.0 933.5999994277954 L488.0 933.5999994277954" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1956 132 L1956 201" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1956 132 1959 138 1953 138" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1950.0 201.0 L1956.0 189.0 L1962.0 201.0 M1950.0 188.4000005722046 L1962.0 188.4000005722046" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g stroke-linecap="butt" >
<path stroke="rgb(0,0,0)" fill="none" stroke-opacity="1.0"  stroke-dasharray="8,8" stroke-width="1" d="M1014 365 L1066 365" />
<polygon stroke="rgb(0,0,0)" stroke-dasharray="none" points="1014 365 1020 362 1020 368" fill="rgb(0,0,0)" stroke-width="1" stroke-opacity="1.0"  />
<path stroke-dasharray="none" d="M1066.0 371.0 L1054.0 365.0 L1066.0 359.0 M1053.4000005722046 371.0 L1053.4000005722046 359.0" fill="white" stroke-width="1" stroke-opacity="1.0" stroke="rgb(0,0,0)" />
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath14_0_)" transform="translate(1554,1019)" >
<rect x="0" y="0" width="267" height="87" />
<text id="00972E8B-22163EAF3574" x="81" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
PAYMENT_METHODS
</text>
<line x1="0" y1="18" x2="266" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
payment_method_ID
</text>
<text x="162" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
payment_method_name
</text>
<text x="162" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (50)
</text>
<line x1="0" y1="52" x2="266" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PaymentMethods_PK (payment_method_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PaymentMethods__UN (payment_method_name)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath17_0_)" transform="translate(359,785)" >
<rect x="0" y="0" width="253" height="135" />
<text id="02EAF620-D322FD4D4885" x="99" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
PRODUCTS
</text>
<line x1="0" y1="18" x2="252" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="113" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
category_ID
</text>
<text x="113" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_name
</text>
<text x="113" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (100)
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
serial_number
</text>
<text x="113" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (50)
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
unit_price
</text>
<text x="113" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (8,2)
</text>
<line x1="0" y1="94" x2="252" y2="94" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PRODUCTS_PK (product_ID)
</text>
<line x1="0" y1="114" x2="252" y2="114" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="121" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#6E947EA9-7010FCC0C4C3" >
<text x="16" y="128" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Products_ProductCategories_FK (category_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath18_0_)" transform="translate(686,935)" >
<rect x="0" y="0" width="313" height="149" />
<text id="11986BB0-F0FF6A43DE86" x="88" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
RECEIPT_PRODUCTS_LISTS
</text>
<line x1="0" y1="18" x2="312" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
receipt_list_ID
</text>
<text x="157" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
receipt_ID
</text>
<text x="157" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="157" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
purchased_product_qty
</text>
<text x="157" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="80" x2="312" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PurchasedProductsList_PK (receipt_list_ID, receipt_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
RECEIPT_PRODUCTS_LISTS__UN (receipt_ID)
</text>
<line x1="0" y1="114" x2="312" y2="114" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="121" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#02EAF620-D322FD4D4885" >
<text x="16" y="128" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PurchasedList_Products_FK (product_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="135" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#2BAD8F12-D460BCDA607E" >
<text x="16" y="142" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
RECEIPT_PRODUCTS_LISTS_RECEIPTS_FK (receipt_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath12_0_)" transform="translate(484,310)" >
<rect x="0" y="0" width="220" height="135" />
<text id="13643C55-FB83B109EA91" x="89" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
ORDERS
</text>
<line x1="0" y1="18" x2="219" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
order_ID
</text>
<text x="125" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
order_nr
</text>
<text x="125" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (20)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
supplier_ID
</text>
<text x="125" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
order_send_date
</text>
<text x="125" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
DATE
</text>
<line x1="0" y1="80" x2="219" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Orders_PK (order_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
ORDERS__UN (order_nr)
</text>
<line x1="0" y1="114" x2="219" y2="114" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="121" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#61CD4A82-6A8010638FD2" >
<text x="16" y="128" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Orders_Suppliers_FK (supplier_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath10_0_)" transform="translate(83,696)" >
<rect x="0" y="0" width="247" height="107" />
<text id="15949D2D-FA14D0BF3767" x="67" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
ONLINE_STOREHOUSE
</text>
<line x1="0" y1="18" x2="246" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="138" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
online_product_qty
</text>
<text x="138" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
deficit_alert
</text>
<text x="138" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="66" x2="246" y2="66" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
StationaryStoreHousev1_PK (product_ID)
</text>
<line x1="0" y1="86" x2="246" y2="86" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="93" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#02EAF620-D322FD4D4885" >
<text x="16" y="100" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
OnlineStoreHouse_Products_FK (product_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath13_0_)" transform="translate(1852,584)" >
<rect x="0" y="0" width="261" height="107" />
<text id="182F8512-9188709DB6B7" x="97" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
PAY_SCALES
</text>
<line x1="0" y1="18" x2="260" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
position_ID
</text>
<text x="99" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
min_wages
</text>
<text x="99" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (8,2)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
max_wages
</text>
<text x="99" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (8,2)
</text>
<line x1="0" y1="66" x2="260" y2="66" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PayScales_PK (position_ID)
</text>
<line x1="0" y1="86" x2="260" y2="86" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="93" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#AA3199E4-1DC02731C40C" >
<text x="16" y="100" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PayScales_EmployeePositions_FK (position_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath11_0_)" transform="translate(480,490)" >
<rect x="0" y="0" width="256" height="135" />
<text id="19D397DF-C1635EBD998C" x="56" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
ORDERED_PRODUCTS_LISTS
</text>
<line x1="0" y1="18" x2="255" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
order_ID
</text>
<text x="139" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="139" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
stationary_store_qty
</text>
<text x="139" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
online_store_qty
</text>
<text x="139" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="80" x2="255" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
OrderedProductsList_PK (order_ID, product_ID)
</text>
<line x1="0" y1="100" x2="255" y2="100" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="107" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#13643C55-FB83B109EA91" >
<text x="16" y="114" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
OrderedProdList_Orders_FK (order_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="121" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#02EAF620-D322FD4D4885" >
<text x="16" y="128" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
OrderedProdList_Products_FK (product_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath19_0_)" transform="translate(1069,1028)" >
<rect x="0" y="0" width="297" height="163" />
<text id="2BAD8F12-D460BCDA607E" x="124" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
RECEIPTS
</text>
<line x1="0" y1="18" x2="296" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
receipt_ID
</text>
<text x="129" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
receipt_no 
</text>
<text x="129" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (20)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
UF
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
transaction_ID
</text>
<text x="129" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
payment_term_id
</text>
<text x="129" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<line x1="0" y1="80" x2="296" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Receipts_PK (receipt_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Receipts_receipt_no_UN (receipt_no )
</text>
<use xlink:href="#uk_sym" x="4" y="115" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="122" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
RECEIPTS_transaction_UN (transaction_ID)
</text>
<line x1="0" y1="128" x2="296" y2="128" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="135" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#B782C578-15B2BE8C94FE" >
<text x="16" y="142" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
RECEIPTS_TRANSACTIONS_FK (transaction_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="149" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#60A2DD24-4A49DBD63449" >
<text x="16" y="156" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
RECEIPTS_PAYMENT_TERMS_FK (payment_term_id)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath9_0_)" transform="translate(676,679)" >
<rect x="0" y="0" width="357" height="149" />
<text id="3D9A0C7D-4A016C5A02EE" x="110" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
INVOICE_PRODUCTS_LISTS
</text>
<line x1="0" y1="18" x2="356" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
invoice_list_ID
</text>
<text x="157" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
income_invoice_ID
</text>
<text x="157" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="157" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
purchased_product_qty
</text>
<text x="157" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="80" x2="356" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
INVOICE_PRODUCTS_LISTS_PK (invoice_list_ID, income_invoice_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
INVOICE_PRODUCTS_LISTS__UN (income_invoice_ID)
</text>
<line x1="0" y1="114" x2="356" y2="114" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="121" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#02EAF620-D322FD4D4885" >
<text x="16" y="128" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
INVOICE_PRODUCTS_LISTS__FK (product_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="135" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#F5B6C60D-0985518B24C0" >
<text x="16" y="142" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
INVOICE_LISTS_INCOME__FK (income_invoice_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath21_0_)" transform="translate(81,850)" >
<rect x="0" y="0" width="249" height="107" />
<text id="5EC759FF-F2DF7CDE3E45" x="55" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
STATIONARY_STOREHOUSE
</text>
<line x1="0" y1="18" x2="248" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="126" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_quantity
</text>
<text x="126" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
deficit_alert
</text>
<text x="126" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="66" x2="248" y2="66" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
StoreHouse_PK (product_ID)
</text>
<line x1="0" y1="86" x2="248" y2="86" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="93" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#02EAF620-D322FD4D4885" >
<text x="16" y="100" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
StationStoreHouse_Products_FK (product_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath24_0_)" transform="translate(145,89)" >
<rect x="0" y="0" width="279" height="121" />
<text id="60658F9E-A607D7875569" x="114" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIES
</text>
<line x1="0" y1="18" x2="278" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
supply_ID
</text>
<text x="122" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
order_nr
</text>
<text x="122" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (20)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
cost_invoice_ID
</text>
<text x="122" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
delivery_date 
</text>
<text x="122" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
DATE
</text>
<line x1="0" y1="80" x2="278" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIERS_PK (supply_ID)
</text>
<line x1="0" y1="100" x2="278" y2="100" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="107" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#A6419ADF-C4F1E307078D" >
<text x="16" y="114" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIES_COST_INVOICES_FK (cost_invoice_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath15_0_)" transform="translate(1088,819)" >
<rect x="0" y="0" width="248" height="87" />
<text id="60A2DD24-4A49DBD63449" x="79" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
PAYMENT_TERMS
</text>
<line x1="0" y1="18" x2="247" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
term_id
</text>
<text x="129" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
term_name
</text>
<text x="129" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (50 CHAR)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
days_to_payment
</text>
<text x="129" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<line x1="0" y1="66" x2="247" y2="66" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
PAYMENT_TERMS_PK (term_id)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath23_0_)" transform="translate(948,82)" >
<rect x="0" y="0" width="233" height="121" />
<text id="61CD4A82-6A8010638FD2" x="88" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIERS
</text>
<line x1="0" y1="18" x2="232" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
supplier_ID
</text>
<text x="119" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
supplier_name 
</text>
<text x="119" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (100)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
address_ID
</text>
<text x="119" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
nip
</text>
<text x="119" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (10)
</text>
<line x1="0" y1="80" x2="232" y2="80" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="87" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="94" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIERS_PKv2 (supplier_ID)
</text>
<line x1="0" y1="100" x2="232" y2="100" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="107" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#FF069ACF-8E027E5B843D" >
<text x="16" y="114" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIERS_ADRESSES_FK (address_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath20_0_)" transform="translate(1833,44)" >
<rect x="0" y="0" width="238" height="87" />
<text id="6605DBEE-981EA5F5FBA3" x="94" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
SECTIONS
</text>
<line x1="0" y1="18" x2="237" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
section_ID
</text>
<text x="113" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
section_name
</text>
<text x="113" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (100 CHAR)
</text>
<line x1="0" y1="52" x2="237" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Sections_PK (section_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Sections__UN (section_name)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath16_0_)" transform="translate(374,990)" >
<rect x="0" y="0" width="230" height="87" />
<text id="6E947EA9-7010FCC0C4C3" x="55" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
PRODUCT_CATEGORIES
</text>
<line x1="0" y1="18" x2="229" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
category_ID
</text>
<text x="120" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
category_name
</text>
<text x="120" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (30)
</text>
<line x1="0" y1="52" x2="229" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
ProductCategories_PK (category_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
ProductCategories__UN (category_name)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath25_0_)" transform="translate(1884,906)" >
<rect x="0" y="0" width="213" height="87" />
<text id="77843BA6-F5A426155699" x="43" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
TRANSACTION_STATUSES
</text>
<line x1="0" y1="18" x2="212" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
status_ID
</text>
<text x="105" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
status_name
</text>
<text x="105" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (30)
</text>
<line x1="0" y1="52" x2="212" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
TransactionStatus_PK (status_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
TransactionStatus__UN (status_name)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath2_0_)" transform="translate(760,321)" >
<rect x="0" y="0" width="253" height="73" />
<text id="79403A64-E88B64240AC6" x="59" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
CLIENTS_LOYALTY_CARDS
</text>
<line x1="0" y1="18" x2="252" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
loyalty_card_id
</text>
<text x="134" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
loyalty_card_label
</text>
<text x="134" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (15 CHAR)
</text>
<line x1="0" y1="52" x2="252" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
LOYALTY_CARD_PK (loyalty_card_id)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath27_0_)" transform="translate(1066,266)" >
<rect x="0" y="0" width="281" height="206" />
<text id="79D38063-425114D0D48F" x="85" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
WHOLESALE_CLIENTS
</text>
<line x1="0" y1="18" x2="280" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
wholesale_client_ID
</text>
<text x="159" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
wholesale_client_name
</text>
<text x="159" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (100)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
loyalty_card_id
</text>
<text x="159" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
address_ID
</text>
<text x="159" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="88" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
nip
</text>
<text x="159" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (10 CHAR)
</text>
<text x="16" y="102" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="102" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="102" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
regon
</text>
<text x="159" y="102" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (9 BYTE)
</text>
<text x="16" y="116" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="116" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
email
</text>
<text x="159" y="116" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (50 CHAR)
</text>
<line x1="0" y1="122" x2="280" y2="122" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="129" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="136" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
CLIENTS_PK (wholesale_client_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="143" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="150" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
WHOLESALE_CLIENTS_REGON_UN (regon)
</text>
<use xlink:href="#uk_sym" x="4" y="157" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="164" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
WHOLESALE_CLIENTS_NIP_UN (nip)
</text>
<line x1="0" y1="170" x2="280" y2="170" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="177" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#79403A64-E88B64240AC6" >
<text x="16" y="184" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
WHOLESALE_CLIENTS_CARDS_FK (loyalty_card_id)
</text></a>
<use xlink:href="#fk_sym" x="4" y="191" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#FF069ACF-8E027E5B843D" >
<text x="16" y="198" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
WHOLESALE_CLIENTS_ADDRESSES_FK (address_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath22_0_)" transform="translate(147,303)" >
<rect x="0" y="0" width="265" height="163" />
<text id="84F5A985-5BD87C02BB36" x="60" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
SUPPLIED_PRODUCTS_LISTS
</text>
<line x1="0" y1="18" x2="264" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
supply_ID
</text>
<text x="133" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
PF
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_ID
</text>
<text x="133" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
product_net_price
</text>
<text x="133" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (10,2)
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
tax
</text>
<text x="133" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (3,2)
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
quantity
</text>
<text x="133" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="94" x2="264" y2="94" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SuppliedProductList_PK (supply_ID, product_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="115" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="122" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SUPP_PROD_LISTS_SUPPLIES_UN (supply_ID)
</text>
<line x1="0" y1="128" x2="264" y2="128" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="135" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#60658F9E-A607D7875569" >
<text x="16" y="142" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SuppliedProdList_Supplies_FK (supply_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="149" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#02EAF620-D322FD4D4885" >
<text x="16" y="156" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
SuppliedProdList_Products_FK (product_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath3_0_)" transform="translate(481,76)" >
<rect x="0" y="0" width="228" height="177" />
<text id="A6419ADF-C4F1E307078D" x="73" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
COST_INVOICES
</text>
<line x1="0" y1="18" x2="227" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
cost_invoice_ID
</text>
<text x="133" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
cost_invoice_nr
</text>
<text x="133" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (30)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
supplier_ID
</text>
<text x="133" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
tota_net_price
</text>
<text x="133" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (12,2)
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
total_tax
</text>
<text x="133" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (12,2)
</text>
<text x="16" y="102" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="102" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
is_paid
</text>
<text x="133" y="102" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
CHAR (1)
</text>
<text x="16" y="116" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="116" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
cost_invoice_date
</text>
<text x="133" y="116" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
DATE
</text>
<line x1="0" y1="122" x2="227" y2="122" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="129" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="136" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
CostInvoices_PK (cost_invoice_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="143" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="150" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
CostInvoices__UN (cost_invoice_nr)
</text>
<line x1="0" y1="156" x2="227" y2="156" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="163" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#61CD4A82-6A8010638FD2" >
<text x="16" y="170" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
CostInvoices_Suppliers_FK (supplier_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath5_0_)" transform="translate(1851,430)" >
<rect x="0" y="0" width="229" height="88" />
<text id="AA3199E4-1DC02731C40C" x="55" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
EMPLOYEE_POSITIONS
</text>
<line x1="0" y1="18" x2="228" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
position_ID
</text>
<text x="116" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
position_name
</text>
<text x="116" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (40)
</text>
<line x1="0" y1="52" x2="228" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EmployeePositions_PK (position_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="73" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="80" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EmployeePositions__UN (position_name)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath26_0_)" transform="translate(1487,744)" >
<rect x="0" y="0" width="353" height="205" />
<text id="B782C578-15B2BE8C94FE" x="138" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
TRANSACTIONS
</text>
<line x1="0" y1="18" x2="352" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
transaction_ID
</text>
<text x="141" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
employee_ID
</text>
<text x="141" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
payment_method_ID
</text>
<text x="141" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
delivery_method_ID
</text>
<text x="141" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
status_ID
</text>
<text x="141" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="102" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="102" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
start_time
</text>
<text x="141" y="102" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
TIMESTAMP
</text>
<text x="16" y="116" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="116" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
end_time
</text>
<text x="141" y="116" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
TIMESTAMP
</text>
<line x1="0" y1="122" x2="352" y2="122" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="129" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="136" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Transactions_PK (transaction_ID)
</text>
<line x1="0" y1="142" x2="352" y2="142" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="149" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#BD7A5F76-6DEE8537F475" >
<text x="16" y="156" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
TRANSACTIONS_RECEIPTS_FKv1 (employee_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="163" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#00972E8B-22163EAF3574" >
<text x="16" y="170" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Transactions_PaymentMethods_FK (payment_method_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="177" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#77843BA6-F5A426155699" >
<text x="16" y="184" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Transactions_TranStatus_FK (status_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="191" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#CDED3FB1-CDB6CF14B2A5" >
<text x="16" y="198" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
TRANSACTIONS_DELIVERY_METHODS_FK (delivery_method_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath6_0_)" transform="translate(1513,329)" >
<rect x="0" y="0" width="267" height="192" />
<text id="BD7A5F76-6DEE8537F475" x="101" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
EMPLOYEES
</text>
<line x1="0" y1="18" x2="266" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
employee_ID
</text>
<text x="142" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
employee_name 
</text>
<text x="142" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (20)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
employee_surname 
</text>
<text x="142" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (30)
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
pesel 
</text>
<text x="142" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (11)
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
email
</text>
<text x="142" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (50 CHAR)
</text>
<text x="16" y="102" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="102" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="102" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
address_ID
</text>
<text x="142" y="102" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="116" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="116" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
UF
</text>
<text x="26" y="116" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
contract_ID
</text>
<text x="142" y="116" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="122" x2="266" y2="122" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="129" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="136" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EMPLOYEES_PK (employee_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="143" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="150" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EMPLOYEES__UN (contract_ID)
</text>
<line x1="0" y1="156" x2="266" y2="156" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="163" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#FF069ACF-8E027E5B843D" >
<text x="16" y="170" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Employees_Adresses_FK (address_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="177" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#C1AE5876-EFEEFA3C09B7" >
<text x="16" y="184" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Employees_EmployeeContracts_FK (contract_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath7_0_)" transform="translate(1840,201)" >
<rect x="0" y="0" width="251" height="164" />
<text id="C1AE5876-EFEEFA3C09B7" x="60" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
EMPLOYEES_CONTRACTS
</text>
<line x1="0" y1="18" x2="250" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
contract_ID
</text>
<text x="101" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
wages 
</text>
<text x="101" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NUMBER (8,2)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
section_ID
</text>
<text x="101" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="2" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
position_ID
</text>
<text x="101" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
hire_date
</text>
<text x="101" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
DATE
</text>
<text x="16" y="102" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="102" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
end_date 
</text>
<text x="101" y="102" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
DATE
</text>
<line x1="0" y1="108" x2="250" y2="108" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="115" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="122" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EmployeeContracts_PK (contract_ID)
</text>
<line x1="0" y1="128" x2="250" y2="128" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="135" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#6605DBEE-981EA5F5FBA3" >
<text x="16" y="142" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EmployeeContracts_Sections_FK (section_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="149" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#AA3199E4-1DC02731C40C" >
<text x="16" y="156" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
EmpContracts_EmpPositions_FK (position_ID)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath4_0_)" transform="translate(1883,787)" >
<rect x="0" y="0" width="222" height="73" />
<text id="CDED3FB1-CDB6CF14B2A5" x="58" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
DELIVERY_METHODS
</text>
<line x1="0" y1="18" x2="221" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
delivery_method_ID
</text>
<text x="158" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
delivery_method_name
</text>
<text x="158" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
SMALLINT
</text>
<line x1="0" y1="52" x2="221" y2="52" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="59" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="66" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Sales_PK (delivery_method_ID)
</text>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath8_0_)" transform="translate(1088,538)" >
<rect x="0" y="0" width="341" height="191" />
<text id="F5B6C60D-0985518B24C0" x="123" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
INCOME_INVOICES
</text>
<line x1="0" y1="18" x2="340" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
income_invoice_ID
</text>
<text x="142" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="46" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
U
</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
income_invoice_no
</text>
<text x="142" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (20)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="60" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
UF
</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
transaction_id
</text>
<text x="142" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
wholesale_client_ID
</text>
<text x="142" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
F
</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
payment_term_id
</text>
<text x="142" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<line x1="0" y1="94" x2="340" y2="94" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
Invoices_PK (income_invoice_ID)
</text>
<use xlink:href="#uk_sym" x="4" y="115" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="122" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
IncomeInvoices_invoice_UN (income_invoice_no)
</text>
<use xlink:href="#uk_sym" x="4" y="129" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="136" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
IncomeInvoices_transaction_UN (transaction_id)
</text>
<line x1="0" y1="142" x2="340" y2="142" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#fk_sym" x="4" y="149" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#79D38063-425114D0D48F" >
<text x="16" y="156" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
InInvoices_WholesaleClients_FK (wholesale_client_ID)
</text></a>
<use xlink:href="#fk_sym" x="4" y="163" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#B782C578-15B2BE8C94FE" >
<text x="16" y="170" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
INCOME_INVOICES_TRANSACTIONS_FK (transaction_id)
</text></a>
<use xlink:href="#fk_sym" x="4" y="177" width="8" height="8" fill-opacity="1.0"/><a xlink:href="#60A2DD24-4A49DBD63449" >
<text x="16" y="184" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
INCOME_INVOICES_PAYMENT_TERMS_FK (payment_term_id)
</text></a>
</g>
<g  fill="rgb(255,255,180)" stroke="rgb(0,0,255)" fill-opacity="1.0" stroke-opacity="1.0" clip-path="url(#clipPath1_0_)" transform="translate(1514,133)" >
<rect x="0" y="0" width="260" height="128" />
<text id="FF069ACF-8E027E5B843D" x="99" y="14" fill="rgb(0,0,255)" font-weight="bold"  fill-opacity="1.0" font-size="10" stroke="none">
ADDRESSES
</text>
<line x1="0" y1="18" x2="259" y2="18" fill="none" stroke="rgb(0,0,255)"/>
<text x="16" y="32" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
*
</text>
<text x="2" y="32" fill="rgb(0,0,255)" fill-opacity="1.0" font-size="10" stroke="none">
P
</text>
<text x="26" y="32" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
address_ID
</text>
<text x="118" y="32" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
INTEGER
</text>
<text x="16" y="46" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="46" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
street 
</text>
<text x="118" y="46" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (100)
</text>
<text x="16" y="60" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="60" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
city
</text>
<text x="118" y="60" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
NVARCHAR2 (50)
</text>
<text x="16" y="74" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="74" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
postal_code
</text>
<text x="118" y="74" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
CHAR (5 CHAR)
</text>
<text x="16" y="88" fill="rgb(255,0,0)" fill-opacity="1.0" font-size="10" stroke="none">

</text>
<text x="26" y="88" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
phone_number
</text>
<text x="118" y="88" fill="rgb(0,128,0)" fill-opacity="1.0" font-size="10" stroke="none">
VARCHAR2 (11 CHAR)
</text>
<line x1="0" y1="94" x2="259" y2="94" fill="none" stroke="rgb(0,0,255)"/>
<use xlink:href="#pk_sym" x="4" y="101" width="8" height="8" fill-opacity="1.0"/>
<text x="16" y="108" fill="rgb(0,0,0)" fill-opacity="1.0" font-size="10" stroke="none">
ADRESSES_PK (address_ID)
</text>
</g>

</svg>
</html>
