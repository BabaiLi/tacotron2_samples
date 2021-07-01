## 歡迎來到 Github 網頁

這裡將展示基於 LDE多語者Embedding 和 Voice Conversion Embedding 的 Tacotron2 示例。<br>
目前合成效果還未達到最佳！

# Seen Speaker
## Inside Text
SSB00050001.wav 廣州女大學生登山失聯四天警方找到疑似女屍
<div style="border:1px black solid;width:1002px;">
    
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                
                <audio controls>
                    <source src="audio/SSB00050001.wav" type="audio/wav">
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
                    <source src="audio/lde_76000_5_廣州女大學生登山失聯四天警方找到疑似女屍.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>

    SSB00110004.wav 當事人也必須澄清自己的交易行為與内部信息無關    
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                
                <audio controls>
                    <source src="audio/SSB00110004.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    vc
                    <source src="audio/vc_99000_11_當事人也必須澄清自己的交易行為與内部信息無關.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    lde
                    <source src="audio/lde_76000_11_當事人也必須澄清自己的交易行為與内部信息無關.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>
