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
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
        <div class="button-container">
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
        <div class="button-container">
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
        <div class="button-container-last">
            <button class="button"></button>
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
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
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
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
        <div class="button-container">
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
        <div class="button-container">
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
    </div>
    <div class="main-weapon category-button">
        <p>HOUSING</p>
        <div class="button-container">
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
            <button class="button"></button>
        </div>
        <div class="button-container">
            <button class="button"></button>
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
    background-color: #007bff;
    border: none;
    cursor: pointer;
}

/* ホバー時のスタイル */
.button:hover {
    background-color: #0056b3;
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