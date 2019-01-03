<span class="breadcrumb">
    <img src="{{ site.url }}/assets/images/advanced_block.png"> → <img src="/assets/images/game.png">
</span>

## スプライト

<table id="create" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/create_sprite.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>新しいスプライトを作成します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">X: </span>スプライトの横向きの位置（X座標）</li>
                <li><span class="param">Y: </span>スプライトの縦向きの位置（Y座標）</li>
            </ul>
            <p>0と4は画面端を表し、2が中心です。</p>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>
            <ul>
                <li>作成されたスプライトは右を向いています。</li>
                <li>0より小さい数字を入れると0、4より大きい数字を入れると4になります。</li>
            </ul>
        </td>
    </tr>
</table>

<table id="delete" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/delete.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>スプライトを削除します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>削除するスプライトの名前</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>削除したスプライトは画面から消えて、他のスプライトと衝突しなくなります。</td>
    </tr>
</table>

<table id="move" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/move.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>スプライトを現在向いている方向に移動します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>移動する距離</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>画面端を超えて移動することはありません。</td>
    </tr>
</table>

<table id="turn" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/turn.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>スプライトを回転させて、向きを変えます</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">向き: </span>右 または 左</li>
                <li><span class="param">角度: </span>スプライトを回転させる角度（45°ごと）</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>45°ごとではない数字を入れると、直前の45°ごとの数字に変換されます。
            <ul>
                <li>例）80° → 45°</li>
                <li>例）179° → 135°</li>
            </ul>
        </td>
    </tr>
</table>

<table id="bounce" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/bounce.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>スプライトが画面端にあり、かつ、画面端の方向を向いていれば、反射させます。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>反射するとスプライトの向きが180°変わります。</td>
    </tr>
</table>

<table id="get" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/get.png"></td>
        </tr>
    <tr>
        <th>機能</th>
        <td>スプライトの様々な情報を取得します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">X: </span>スプライトのX座標（0-4）</li>
                <li><span class="param">Y: </span>スプライトのY座標（0-4）</li>
                <li><span class="param">向き: </span>スプライトの向き（角度）</li>
                <li><span class="param">明るさ: </span>スプライトの明るさ（0-255）</li>
                <li><span class="param">点滅: </span>スプライトの点滅速度（0-10000）</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>パラメータで指定したスプライトの値</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし。</td>
    </tr>
</table>

<table id="set" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/set.png"></td>
        </tr>
    <tr>
        <th>機能</th>
        <td>スプライトの様々な情報を設定します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">X: </span>スプライトのX座標（0-4）</li>
                <li><span class="param">Y: </span>スプライトのY座標（0-4）</li>
                <li><span class="param">向き: </span>スプライトの向き（角度）</li>
                <li><span class="param">明るさ: </span>スプライトの明るさ（0-255）</li>
                <li><span class="param">点滅: </span>スプライトの点滅速度（0-10000）</li>
            </ul>
            <li><span class="param">値: </span>スプライトに設定する新しい数値</li>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>範囲外の値を設定した場合、値が自動的に切り詰められます。</td>
    </tr>
</table>

<table id="change" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/change.png"></td>
        </tr>
    <tr>
        <th>機能</th>
        <td>スプライトの様々な情報を変更します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>
            <ul>
                <li><span class="param">X: </span>スプライトのX座標（0-4）</li>
                <li><span class="param">Y: </span>スプライトのY座標（0-4）</li>
                <li><span class="param">向き: </span>スプライトの向き（角度）</li>
                <li><span class="param">明るさ: </span>スプライトの明るさ（0-255）</li>
                <li><span class="param">点滅: </span>スプライトの点滅速度（0-10000）</li>
            </ul>
            <li><span class="param">値: </span>変更する数値</li>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>範囲外の値を設定した場合、値が自動的に切り詰められます。</td>
    </tr>
</table>

<table id="touching" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/touching.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>スプライトが他のスプライトと同じ位置にあるかどうか調べます。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>同じ位置にあるか調べる相手のスプライト</td>
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
        <td>同じ位置にあるというのは、スプライトが存在していて、X・Y座標がいずれも等しいことです。</td>
    </tr>
</table>

<table id="touchingEdge" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/sprite/touching_edge.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>スプライトが画面端にあるかどうかを調べます。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>
            <ul>
                <li><span class="param">真: </span>スプライトが画面端にある場合</li>
                <li><span class="param">偽: </span>スプライトが画面端にない場合</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>注意</th>
        <td>画面端というのは、X座標またはY座標が0か4のときです。</td>
    </tr>
</table>

## 点数

<table id="addScore" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/score/add_score.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>点数を増やします（アニメーションつき）</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>増減させる点数</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>アニメーションを表示させたくない場合は、「点数を設定する」を使いましょう。</td>
    </tr>
</table>

<table id="score" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/score/score.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>点数を取得します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>戻り値</th>
        <td>現在の点数</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>点数の初期値は0です。</td>
    </tr>
</table>

<table id="setScore" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/score/set_score.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>点数を設定します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>設定する点数</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>マイナスの値は設定できません。</td>
    </tr>
</table>

## ライフ

<table id="setLife" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/life/set_life.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>ライフを設定します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>設定するライフ</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>マイナスの値は設定できません。ライフの初期値は3で、0になるとゲームオーバーです。</td>
    </tr>
</table>

<table id="addLife" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/life/add_life.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>ライフを増やします。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>増やすライフ</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>特になし</td>
    </tr>
</table>

<table id="removeLife" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/life/remove_life.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>ライフを減らします（アニメーション付き）</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>減らすライフ</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>ライフが0になるとゲームオーバーです。</td>
    </tr>
</table>

## ゲームコントロール

<table id="startCountdown" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/control/start_countdown.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>ゲーム開始のアニメーションとともにカウントダウンとを開始します。カウントダウンが0になるとゲームオーバーです。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>カウントダウンの時間（ミリ秒）</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>500ミリ秒より短い時間は設定すると、500ミリ秒になります。</td>
    </tr>
</table>

<table id="gameover" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/control/gameover.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>ゲームオーバーのアニメーションを表示し、点数を表示、を繰り返します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>ゲームオーバーになるとスプライトの表示はなくなりますが、裏側の処理は動き続けています。</td>
    </tr>
</table>

<table id="pause" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/control/pause.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>アニメーションの表示を一時停止にします。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>一時停止中でも、アニメーション以外は動いています。</td>
    </tr>
</table>

<table id="resume" class="block">
    <tr>
        <td colspan="2"><img src="/assets/images/game/control/resume.png"></td>
    </tr>
    <tr>
        <th>機能</th>
        <td>アニメーションの表示を再開します。</td>
    </tr>
    <tr>
        <th>パラメータ</th>
        <td>特になし。</td>
    </tr>
    <tr>
        <th>注意</th>
        <td>再開時に最新のスプライトの状態を描画します。</td>
    </tr>
</table>
