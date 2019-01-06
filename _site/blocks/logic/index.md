<span class="breadcrumb">
    <img src="{{ site.baseurl }}/assets/images/logic.png">
</span>

## 条件判断

<table id="if" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/logic/if.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結したブロックを、指定した条件に当てはまるときに実行します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>実行する条件</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>左下のプラスマークをクリックすることで、条件分岐を増やすことができます。</td>
    </tr>
</table>

<table id="ifElse" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/logic/ifElse.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>この中に連結したブロックを、指定した条件に当てはまるときに実行します。当てはまらない場合は、もう一方の「でなければ」の中に連結されたブロックを実行します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>実行する条件</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <ul>
                <li>左下のプラスマークをクリックすることで、条件分岐を増やすことができます。</li>
                <li>右側のマイナスマークをクリックすることで、条件分岐を減らすことができます。</li>
            </ul>
        </td>
    </tr>
</table>

## くらべる

<table id="equal" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/logic/equal.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>指定された2つの値を比べて、結果を返します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">=: </span>値が同じであるかどうか調べる</li>
                <li><span class="param">&ne;: </span>値が異なるかどうか調べる</li>
                <li><span class="param">&lt;: </span>左側の値が右側より小さいか調べる</li>
                <li><span class="param">&le;: </span>左側の値が右側以下か調べる</li>
                <li><span class="param">&gt;: </span>左側の値が右側より大きいか調べる</li>
                <li><span class="param">&ge;: </span>左側の値が右側以上か調べる</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>
            <ul>
                <li><span class="param">真: </span>比べた結果が正しい場合</li>
                <li><span class="param">偽: </span>比べた結果が正しくない場合</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>数字と文字など、異なる種類の値を比べることはできません。</td>
    </tr>
</table>

## 真偽値

<table id="and" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/logic/and.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>指定された2つの条件をしらべて、結果を返します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">かつ: </span>2つの条件が共に成り立つかどうか調べる</li>
                <li><span class="param">または: </span>2つの条件のどちらか一方が成り立つか調べる</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>真偽値テーブル</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>作成中</td>
    </tr>
</table>


<table id="not" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/logic/not.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>作成中</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param"> </span>作成中</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>
            <ul>
                <li><span class="param">真: </span>2つのスプライトが同じ位置にある場合</li>
                <li><span class="param">偽: </span>2つのスプライトが同じ位置にない場合</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>作成中</td>
    </tr>
</table>

<table id="true" class="block">
    <tr>
        <td colspan="2"><img src="{{ site.baseurl }}/assets/images/logic/true.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>作成中</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param"> </span>作成中</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>
            <ul>
                <li><span class="param">真: </span>2つのスプライトが同じ位置にある場合</li>
                <li><span class="param">偽: </span>2つのスプライトが同じ位置にない場合</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>作成中</td>
    </tr>
</table>

