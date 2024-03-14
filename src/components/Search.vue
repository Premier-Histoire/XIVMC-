<template>
    <div class="title">
        <img src="../assets/img/title.png">
    </div>
    <div class="freesearch">
        <p>FREE SEARCH</p>
        <input class="search-input" type="text">
    </div>
    <div class="main-weapon category-button">
        <p>MAIN ARM/SUB ARM</p>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="片手剣">
                <img src="../assets/img/060102.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="斧">
                <img src="../assets/img/060103.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="両手剣">
                <img src="../assets/img/060170.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="ガンブレード">
                <img src="../assets/img/060181.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="槍">
                <img src="../assets/img/060104.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="両手鎌">
                <img src="../assets/img/060183.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="格闘武器">
                <img src="../assets/img/060101.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="刀">
                <img src="../assets/img/060177.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="双剣">
                <img src="../assets/img/060106.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="弓">
                <img src="../assets/img/060105.png">
            </button>
        </div>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="銃">
                <img src="../assets/img/060172.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="投擲武器">
                <img src="../assets/img/060182.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="呪具">
                <img src="../assets/img/060108.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="魔導書">
                <img src="../assets/img/060109.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="細剣">
                <img src="../assets/img/060176.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="幻具">
                <img src="../assets/img/060107.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="魔導書(学者専用)">
                <img src="../assets/img/060178.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="天球儀">
                <img src="../assets/img/060171.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="賢具">
                <img src="../assets/img/060184.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="木工道具">
                <img src="../assets/img/060112.png">
            </button>
        </div>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="鍛冶道具">
                <img src="../assets/img/060113.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="甲冑道具">
                <img src="../assets/img/060114.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="彫金道具">
                <img src="../assets/img/060115.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="革細工道具">
                <img src="../assets/img/060116.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="裁縫道具">
                <img src="../assets/img/060117.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="錬金道具">
                <img src="../assets/img/060118.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調理道具">
                <img src="../assets/img/060119.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="採掘道具">
                <img src="../assets/img/060120.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="園芸道具">
                <img src="../assets/img/060121.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="漁道具">
                <img src="../assets/img/060122.png">
            </button>
        </div>
        <div class="button-container-last">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="釣り餌">
                <img src="../assets/img/060123.png">
            </button>
        </div>
        <div class="level-selector-container">
            <div class="level-selector">
                <span class="leveltext">Lv</span>
                <input type="text" class="level-input">
                <button class="level-up">+</button>
                <button class="level-down">-</button>
            </div>
        </div>
    </div>
    <div class="main-weapon category-button">
        <p>ARMOR/ACCESSORIES</p>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="盾">
                <img src="../assets/img/060110.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="頭防具">
                <img src="../assets/img/060124.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="胴防具">
                <img src="../assets/img/060126.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="手防具">
                <img src="../assets/img/060129.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="脚防具">
                <img src="../assets/img/060128.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="足防具">
                <img src="../assets/img/060130.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="耳飾り">
                <img src="../assets/img/060133.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="首飾り">
                <img src="../assets/img/060132.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="腕輪">
                <img src="../assets/img/060134.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="指輪">
                <img src="../assets/img/060135.png">
            </button>
        </div>
        <div class="level-selector-container">
            <div class="level-selector">
                <span class="leveltext">Lv</span>
                <input type="text" class="level-input">
                <button class="level-up">+</button>
                <button class="level-down">-</button>
            </div>
        </div>
        <div class="select-job">
            <select class="select-box">
                <option value="ADV">すべて表示</option>
                <option value="PLD">ナイト</option>
                <option value="GLA">剣術士</option>
                <option value="WAR">戦士</option>
                <option value="MRD">斧術士</option>
                <option value="DRK">暗黒騎士</option>
                <option value="GNB">ガンブレイカー</option>
                <option value="WHM">白魔道士</option>
                <option value="CNJ">幻術士</option>
                <option value="SCH">学者</option>
                <option value="AST">占星術師</option>
                <option value="SGE">賢者</option>
                <option value="MNK">モンク</option>
                <option value="PGL">格闘士</option>
                <option value="DRG">竜騎士</option>
                <option value="LNC">槍術士</option>
                <option value="NIN">忍者</option>
                <option value="ROG">双剣士</option>
                <option value="SAM">侍</option>
                <option value="RPR">リーパー</option>
                <option value="BRD">吟遊詩人</option>
                <option value="MCH">機工士</option>
                <option value="DNC">踊り子</option>
                <option value="BLM">黒魔道士</option>
                <option value="THM">呪術士</option>
                <option value="SMN">召喚士</option>
                <option value="ACN">巴術士</option>
                <option value="RDM">赤魔道士</option>
                <option value="BLU">青魔道士</option>
                <option value="CRP">木工師</option>
                <option value="BSM">鍛冶師</option>
                <option value="ARM">甲冑師</option>
                <option value="GSM">彫金師</option>
                <option value="LTW">革細工師</option>
                <option value="WVR">裁縫師</option>
                <option value="ALC">錬金術師</option>
                <option value="CUL">調理師</option>
                <option value="MIN">採掘師</option>
                <option value="BTN">園芸師</option>
                <option value="FSH">漁師</option>
            </select>
        </div>
    </div>
    <div class="main-weapon category-button">
        <p>OTHERS</p>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="薬品">
                <img src="../assets/img/060136.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="食材">
                <img src="../assets/img/060137.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調理品">
                <img src="../assets/img/060146.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="水産物">
                <img src="../assets/img/060138.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="石材">
                <img src="../assets/img/060139.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="金属材">
                <img src="../assets/img/060140.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="木材">
                <img src="../assets/img/060141.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="布材">
                <img src="../assets/img/060142.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="皮革材">
                <img src="../assets/img/060143.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="骨材">
                <img src="../assets/img/060144.png">
            </button>
        </div>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="錬金術材">
                <img src="../assets/img/060145.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="染料">
                <img src="../assets/img/060147.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="部品">
                <img src="../assets/img/060148.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="マテリア">
                <img src="../assets/img/060150.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="クリスタル">
                <img src="../assets/img/060151.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="触媒">
                <img src="../assets/img/060152.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="雑貨">
                <img src="../assets/img/060153.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="雑貨(シーズナル)">
                <img src="../assets/img/060154.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="雑貨(習得/登録系)">
                <img src="../assets/img/060185.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="ミニオン">
                <img src="../assets/img/060155.png">
            </button>
        </div>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="飛空艇・潜水艦部品">
                <img src="../assets/img/060169.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="オーケストリオン関連品">
                <img src="../assets/img/060173.png">
            </button>
        </div>
    </div>
    <div class="main-weapon category-button">
        <p>HOUSING</p>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="外装建材">
                <img src="../assets/img/060160.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="内装建材">
                <img src="../assets/img/060161.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="庭具">
                <img src="../assets/img/060168.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調度品(一般)">
                <img src="../assets/img/060164.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調度品(椅子・寝台)">
                <img src="../assets/img/060165.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="'調度品(台座)">
                <img src="../assets/img/060162.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調度品(卓上)">
                <img src="../assets/img/060163.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調度品(壁掛)">
                <img src="../assets/img/060166.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="調度品(敷物)">
                <img src="../assets/img/060167.png">
            </button>
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="栽培用品">
                <img src="../assets/img/060174.png">
            </button>
        </div>
        <div class="button-container">
            <button class="button" data-bs-toggle="tooltip" data-bs-placement="top"
                data-bs-custom-class="custom-tooltip" data-offset="0, 10" title="絵画">
                <img src="../assets/img/060175.png">
            </button>
        </div>
    </div>
</template>

<script>
import { Tooltip } from 'bootstrap'

export default {
    mounted() {
        new Tooltip(document.body, {
            selector: "[data-bs-toggle='tooltip']",
        })
    },
}
</script>

<style scoped>
.title {
    width: 100%;
    height: 40px;
    display: flex;
    justify-content: center;
}

.title img {
    height: 40px;
}

.freesearch {
    padding: 3px 10px 3px 10px;
    height: fit-content;
}

.freesearch p {
    color: white;
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 0;
}

.search-input {
    flex-grow: 1;
    width: 100%;
    border-radius: 5px;
    height: 25px;
    font-size: 13px;
    background-color: #545454;
    border: solid 1px #454044;
    color: #fff;
}

.category-button {
    width: 100%;
    padding: 3px 10px 3px 10px;
}

.category-button p {
    color: white;
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 0;
}

.button-container {
    display: grid;
    grid-template-columns: repeat(10, 20px);
    gap: 6.6px;
    margin-bottom: 6.6px;
}

.button-container-last {
    display: grid;
    grid-template-columns: repeat(10, 20px);
    gap: 6.6px;
    margin-bottom: 3px;
}

.button {
    width: 20px;
    height: 20px;
    padding: 0;
    font-size: 0;
    background-color: #313031;
    border: none;
    cursor: pointer;
}

/* ホバー時のスタイル */
.button:hover {
    box-shadow: 0 6px 14px rgba(0, 0, 0, 0.24);
    transform: translate(0, -2px);
}

.level-selector-container {
    display: flex;
    justify-content: center;
}

.level-selector {
    display: flex;
    align-items: center;
}

.leveltext {
    color: white;
}

.level-input {
    margin: 0 0 0 10px;
    width: 35px;
    height: 25px;
    color: #fff;
    background-color: #545454;
    border: solid 1px #454044;
    border-radius: 5px;
    text-align: center;
}

.level-up,
.level-down {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #202020;
    color: #000;
    border: solid 1px #151515;
    border-radius: 5px;
    cursor: pointer;
    font-size: 23px;
    width: 25px;
    height: 25px;
    margin-left: 2px;
}

.select-job {
    display: flex;
    justify-content: center;
}

.select-box {
    flex-grow: 1;
    text-align: center;
    margin-top: 5px;
    height: 25px;
    appearance: none;
    color: #fff;
    background: linear-gradient(to bottom, #2F2F2F 0%, #272727 50%, #2F2F2F 100%);
    background-color: #2f2f2f;
    border: 1px solid #222222;
    border-radius: 9999px;
    font-size: 12px;
}
</style>