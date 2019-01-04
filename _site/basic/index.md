<span class="breadcrumb">
    <img src="{{ site.baseurl }}/assets/images/basic.png">
</span>

<table id="showNumber" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/show_number.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>画面上に数字を表示します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>表示する数字</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <ul>
                <li>2桁以上の数はスクロールして表示されます。</li>
                <li>小数の場合、小数点第3位で四捨五入されます（例: 3.1415 -> 3.14）</li>
            </ul>
        </td>
    </tr>
</table>

<table id="showIcon" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/show_icon.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>画面上に指定したアイコンを表示します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>表示するアイコン（選択）</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし。</td>
    </tr>
</table>

<table id="showLeds" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/show_leds.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>画面上に指定したLEDを表示します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>表示するLED（マス目をクリックすると、ON/OFFが選択可能）</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし。</td>
    </tr>
</table>

<table id="showString" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/show_string.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>画面上に文字列を表示します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>表示する文字列</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <ul>
                <li>2文字以上の文字列はスクロールして表示されます。</li>
                <li>表示できるのは、数字とアルファベットのみです。</li>
                <li>ツールボックス最下部の拡張機能から「katakana」パッケージをインストールするとカタカナの表示が可能です。</li>
            </ul>
        </td>
    </tr>
</table>

<table id="clearScreen" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/clear_screen.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>すべてのLED表示をOFFにします。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし。</td>
    </tr>
</table>

<table id="onStart" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/on_start.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結されたブロックを、プログラム起動時に1回だけ実行します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>他のどのブロックよりも先に実行されます。</td>
    </tr>
</table>

<table id="forever" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/forever.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>中に連結されたブロックを繰り返して実行します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>「ずっと」が複数存在する場合、それぞれが別々に中のブロックを実行します。</td>
    </tr>
</table>

<table id="pause" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/pause.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>指定された時間、ブロックの実行を一時停止します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>一時停止する時間（ミリ秒）</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>一時停止するのは、同じ「最初だけ」「ずっと」などのブロックに連結している直後のブロックのみです。ほかの「ずっと」などの処理は動き続けます。
        </td>
    </tr>
</table>

<table id="showArrow" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/basic/show_arrow.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>画面上に指定した矢印を表示します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>表示する矢印（8方向から選択）</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし。</td>
    </tr>
</table>
