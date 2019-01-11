<span class="breadcrumb">
    <img src="{{ site.baseurl }}/assets/images/loops.png">
</span>

<table id="repeat" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/loops/repeat.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結したブロックを、指定した回数だけ、くりかえし実行します。</td>
    </tr>
    <tr>
        <th>入力値</th>
        <td>くりかえす回数（1以上の整数）</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし</td>
    </tr>
</table>

<table id="while" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/loops/while.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結したブロックを、指定した条件に当てはまる限り、くりかえし実行します。</td>
    </tr>
    <tr>
        <th>入力値</th>
        <td>くりかえす条件</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <ul>
                <li>条件に<span class="param">真</span>、または、いつも<span class="param">真</span>となるような式（例：1=1）を指定すると、無限ループとなり処理が終わらなくなります。</li>
                <li>条件に<span class="param">偽</span>、または、いつも<span class="param">偽</span>となるような式（例：0=1）を指定すると、中のブロックは一度も実行されません。</li>
            </ul>
        </td>
    </tr>
</table>

<table id="for" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/loops/for.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結したブロックを、0から指定した数になるまで1ずつ増やしながら、くりかえし実行します。</td>
    </tr>
    <tr>
        <th>入力値</th>
        <td>
            <ul>
                <li><span class="param">カウンター: </span>くりかえしが何回目であるかを保存しておく変数</li>
                <li><span class="param">くりかえす回数: </span>くりかえしの回数</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <ul>
                <li>くりかえしは0から始まるため、くりかえす回数で指定された数よりも1回多く中のブロックは実行されます。</li>
                <li><span class="param">カウンター</span>はこのブロックの中でのみ有効な変数です。ブロックの外で<span class="param">カウンター</span>を利用しようとしても、別の変数として扱われます。</li>
            </ul>
        </td>
    </tr>
</table>

<table id="forOf" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/loops/forOf.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結したブロックを、指定された配列の要素の数だけ、くりかえし実行します。配列の要素すべてに対して何かをしたいときに利用します。</td>
    </tr>
    <tr>
        <th>入力値</th>
        <td>
            <ul>
                <li><span class="param">配列: </span>中身についてくりかえして実行したい配列</li>
                <li><span class="param">値: </span>配列の各要素を保存しておく変数</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <li><span class="param">値</span>はこのブロックの中でのみ有効な変数です。ブロックの外で<span class="param">値</span>を利用しよとしても、別の変数として扱われます。</li>
        </td>
    </tr>
</table>