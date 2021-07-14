# Welcome!

Here, we show the Multi-speaker TTS system.<br>
We add LDE Speaker Embeddings and Voice Conversion Embeddings in our Tacotron 2.<br>
And, the vocoder is DiffWave which is trained by VCTK Corpus about 500_000 iteration.
<br>
<b>The Tacotron2 system has not yet reached the best! </b>

# Train Parameter
Batch: 64
<br>
Train_iter: 73_000
<br>
Train_speaker: 173 (from a part of aishell3)
<br>
Val_unseen_speaker: 45 (from the other of aishell3)
<br>

# Seen Speaker
## Inside Text

<b>SSB00050001.wav 廣州女大學生登山失聯四天警方找到疑似女屍</b>
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
                    <source src="audio/vc_73000_5_廣州女大學生登山失聯四天警方找到疑似女屍.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_5_廣州女大學生登山失聯四天警方找到疑似女屍.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>SSB00110004.wav 當事人也必須澄清自己的交易行為與内部信息無關</b>
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
                    <source src="audio/SSB00110004.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_99000_11_當事人也必須澄清自己的交易行為與内部信息無關.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_11_當事人也必須澄清自己的交易行為與内部信息無關.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>SSB02730002.wav 不動產登記倒計時對樓市影響幾何</b>
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
                    <source src="audio/SSB02730002.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_99000_273_不動產登記倒計時對樓市影響幾何.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_273_不動產登記倒計時對樓市影響幾何.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>SSB18310044.wav 該電視台就播出了一部電視紀錄片</b>
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
                    <source src="audio/SSB18310044.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_1831_該電視台就播出了一部電視紀錄片.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_1831_該電視台就播出了一部電視紀錄片.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>


## Outside Text
## Speaker 0005
<b>一粒老鼠屎壞了一鍋粥</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_5_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_5_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>住家附近的十字路口突然開始大興土木</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_5_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_5_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

## Speaker 0011
<b>一粒老鼠屎壞了一鍋粥</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_11_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_11_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>住家附近的十字路口突然開始大興土木</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_11_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_11_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

## Speaker 0273
<b>一粒老鼠屎壞了一鍋粥</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_273_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_273_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>住家附近的十字路口突然開始大興土木</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_273_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_273_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

## Speaker 1831
<b>一粒老鼠屎壞了一鍋粥</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_1831_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_1831_一粒老鼠屎壞了一鍋粥.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>住家附近的十字路口突然開始大興土木</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_1831_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_1831_住家附近的十字路口突然開始大興土木.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>


# UnSeen Speaker

<b>SSB17820001.wav 大豆病害有什麼</b>
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
                    <source src="audio/SSB17820001.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_1782_大豆病害有什麼.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_1782_大豆病害有什麼.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>SSB17450016.wav 王先生賠償傷者五千元</b>
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
                    <source src="audio/SSB17450016.wav" type="audio/wav">
                </audio>
            </td>
            <td>
                <audio controls>
                    <source src="audio/vc_73000_1745_王先生賠償傷者五千元.wav" type="audio/wav">
                </audio> 
            </td>
            <td>
                <audio controls>
                    <source src="audio/lde_73000_1745_王先生賠償傷者五千元.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

