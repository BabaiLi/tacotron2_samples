## 歡迎來到 Github 網頁

這裡將展示基於 LDE多語者Embedding 和 Voice Conversion Embedding 的 Tacotron2 示例。<br>
目前合成效果還未達到最佳！

# Seen Speaker
## Inside Text
BBE00050001.wav 廣州女大學生登山失聯四天警方找到疑似女屍
<div style="border:1px black solid;width:1002px;">
    
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> LDE Embedding</td>
            <td> VC Embedding</td>
        </tr>
        <tr>
            <td>
                
                <audio controls>
                    <source src="audio/BBE00050001.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    vc
                    <source src="audio/vc_99000_5_廣州女大學生登山失聯四天警方找到疑似女屍.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    lde
                    <source src="audio/lde_99000_5_廣州女大學生登山失聯四天警方找到疑似女屍.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>
## Outside Text
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> LDE Embedding</td>
            <td> VC Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/SSB13020001.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_88000_1302_語音合成是將人類語音用人工的方式所產生.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/76000_1302_語音合成是將人類語音用人工的方式所產生.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

# Uneen Speaker
## Outside Text
語音合成是將人類語音用人工的方式所產生。
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> LDE Embedding</td>
            <td> VC Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/SSB13020001.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_88000_1302_語音合成是將人類語音用人工的方式所產生.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/76000_1302_語音合成是將人類語音用人工的方式所產生.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>
