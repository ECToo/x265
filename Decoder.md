## Decoder Performance (fps) ##
NOTE:<br>
1. value higher is better<br>
2. the project target is iOS/Android, so I use single thread<br>
3. ffmpeg-20140707-git-head, gcc-4.9.0<br>
4. libde265-20140707-git-head, gcc-4.9.0<br>
<hr />
<table><thead><th> <b>Data</b> </th><th> <b>ffmpeg</b> </th><th> <b>libde265</b> </th><th> <b>x265dec</b> </th></thead><tbody>
<tr><td><code>BasketballDrillText_832x480_50_qp22.bin</code></td><td>104</td><td>114</td><td>--</td></tr>
<tr><td><code>BasketballDrillText_832x480_50_qp27.bin</code></td><td>129</td><td>156</td><td>--</td></tr>
<tr><td><code>BasketballDrillText_832x480_50_qp32.bin</code></td><td>169</td><td>222</td><td>--</td></tr>
<tr><td><code>BasketballDrillText_832x480_50_qp37.bin</code></td><td>196</td><td>283</td><td>--</td></tr>
<tr><td><code>BasketballDrill_832x480_50_qp22.bin</code></td><td>98</td><td>112</td><td>--</td></tr>
<tr><td><code>BasketballDrill_832x480_50_qp27.bin</code></td><td>122</td><td>156</td><td>--</td></tr>
<tr><td><code>BasketballDrill_832x480_50_qp32.bin</code></td><td>163</td><td>231</td><td>--</td></tr>
<tr><td><code>BasketballDrill_832x480_50_qp37.bin</code></td><td>189</td><td>300</td><td>--</td></tr>
<tr><td><code>BasketballDrive_1920x1080_50_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballDrive_1920x1080_50_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballDrive_1920x1080_50_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballDrive_1920x1080_50_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballPass_416x240_50_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballPass_416x240_50_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballPass_416x240_50_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BasketballPass_416x240_50_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BlowingBubbles_416x240_50_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BlowingBubbles_416x240_50_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BlowingBubbles_416x240_50_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BlowingBubbles_416x240_50_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQMall_832x480_60_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQMall_832x480_60_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQMall_832x480_60_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQMall_832x480_60_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQSquare_416x240_60_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQSquare_416x240_60_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQSquare_416x240_60_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQSquare_416x240_60_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQTerrace_1920x1080_60_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQTerrace_1920x1080_60_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQTerrace_1920x1080_60_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>BQTerrace_1920x1080_60_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Cactus_1920x1080_50_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Cactus_1920x1080_50_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Cactus_1920x1080_50_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Cactus_1920x1080_50_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ChinaSpeed_1024x768_30_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ChinaSpeed_1024x768_30_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ChinaSpeed_1024x768_30_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ChinaSpeed_1024x768_30_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>FourPeople_1280x720_60_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>FourPeople_1280x720_60_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>FourPeople_1280x720_60_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>FourPeople_1280x720_60_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Johnny_1280x720_60_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Johnny_1280x720_60_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Johnny_1280x720_60_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Johnny_1280x720_60_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Kimono1_1920x1080_24_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Kimono1_1920x1080_24_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Kimono1_1920x1080_24_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Kimono1_1920x1080_24_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>KristenAndSara_1280x720_60_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>KristenAndSara_1280x720_60_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>KristenAndSara_1280x720_60_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>KristenAndSara_1280x720_60_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>NebutaFestival_2560x1600_60_10bit_crop_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>NebutaFestival_2560x1600_60_10bit_crop_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>NebutaFestival_2560x1600_60_10bit_crop_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>NebutaFestival_2560x1600_60_10bit_crop_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ParkScene_1920x1080_24_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ParkScene_1920x1080_24_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ParkScene_1920x1080_24_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>ParkScene_1920x1080_24_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PartyScene_832x480_50_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PartyScene_832x480_50_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PartyScene_832x480_50_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PartyScene_832x480_50_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PeopleOnStreet_2560x1600_30_crop_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PeopleOnStreet_2560x1600_30_crop_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PeopleOnStreet_2560x1600_30_crop_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>PeopleOnStreet_2560x1600_30_crop_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_416x240_30_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_416x240_30_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_416x240_30_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_416x240_30_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_832x480_30_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_832x480_30_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_832x480_30_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>RaceHorses_832x480_30_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideEditing_1280x720_30_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideEditing_1280x720_30_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideEditing_1280x720_30_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideEditing_1280x720_30_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideShow_1280x720_20_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideShow_1280x720_20_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideShow_1280x720_20_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SlideShow_1280x720_20_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SteamLocomotiveTrain_2560x1600_60_10bit_crop_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SteamLocomotiveTrain_2560x1600_60_10bit_crop_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SteamLocomotiveTrain_2560x1600_60_10bit_crop_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>SteamLocomotiveTrain_2560x1600_60_10bit_crop_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Traffic_2560x1600_30_crop_qp22.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Traffic_2560x1600_30_crop_qp27.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Traffic_2560x1600_30_crop_qp32.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td><code>Traffic_2560x1600_30_crop_qp37.bin</code></td><td>--</td><td>--</td><td>--</td></tr>
<tr><td> <b><i>Average</i></b> </td><td> <b>--</b> </td><td> <b>--</b> </td><td> <b>--</b> </td></tr>