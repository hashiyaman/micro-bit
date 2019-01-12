左のメニューからブロックを選んでください。ブロックリファレンスは随時更新する予定です。

<!-- 
<div id="blocklyDiv" style="height: 480px; width: 600px;"></div>

<xml id="toolbox" style="display: none">
    <block type="create_sprite"></block>
    <block type="controls_if"></block>
    <block type="controls_repeat_ext"></block>
    <block type="logic_compare"></block>
    <block type="math_number"></block>
    <block type="math_arithmetic"></block>
    <block type="text"></block>
    <block type="text_print"></block>  
</xml>

<script>
    Blockly.Blocks['create_sprite'] = {
        init: function () {
            this.jsonInit({
                "message0": 'スプライトを作成 X:%1 Y:%2',
                "args0": [
                    {
                        "type": "input_value",
                        "name": "VALUE",
                        "check": "Number"
                    },
                    {
                        "type": "input_value",
                        "name": "VALUE",
                        "check": "Number"
                    }
                ],
                "output": "Number",
                "colour": 160,
                "tooltip": "Returns number of letters in the provided text.",
                "helpUrl": "http://www.w3schools.com/jsref/jsref_length_string.asp"
            });
        }
    };

    var workspace = Blockly.inject('blocklyDiv',
        {toolbox: document.getElementById('toolbox')});
</script>

-->