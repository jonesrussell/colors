<script>
export default {
    data() {
  	    return {
            colors: [
                '#004575',
                '#0079FD',
                '#00CA79',
                '#040B0F',
                '#05C6B5',
                '#093FBA',
                '#0A0A0A',
                '#0A1414',
                '#0A2B3C',
                '#0F1B21',
                '#101D23',
                '#161616',
                '#1779BA',
                '#188855',
                '#20172A',
                '#202020',
                '#258AFF',
                '#29ABE2',
                '#2A678C',
                '#2B2237',
                '#2C3438',
                '#2F2E31',
                '#31E32B',
                '#333333',
                '#3395D2',
                '#33ADF6',
                '#34264E',
                '#355071',
                '#3ADB76',
                '#3E0D0D',
                '#4380B8',
                '#49C7FD',
                '#4F00BC',
                '#51AD09',
                '#591007',
                '#6707C1',
                '#6707C1',
                '#75003A',
                '#757575',
                '#767676',
                '#7B8185',
                '#83CEEE',
                '#890CC0',
                '#8D09BA',
                '#912121',
                '#9A0623',
                '#AD0909',
                '#C376FF',
                '#C5C5C5',
                '#CC4B37',
                '#CEA018',
                '#CECECE',
                '#D165F6',
                '#D7ECFA',
                '#E1FAEA',
                '#E9ED36',
                '#EAEAEA',
                '#ED9336',
                '#EEEEEE',
                '#EFCFDF',
                '#EFEFEF',
                '#F1F1F1',
                '#F3F3F3',
                '#F6F6F6',
                '#F7E4E1',
                '#F84076',
                '#FA4F01',
                '#FBFBFB',
                '#FEFEFE',
                '#FF5300',
                '#FF5300',
                '#FFAE00',
                '#FFF3D9',
                '#FFFF00',
                'hsla(0, 0%, 100%, .6)',
                'hsla(0, 0%, 100%, .65)',
                'hsla(0, 0%, 100%, .75)',
                'hsla(0, 0%, 100%, .8)',
                'hsla(0, 0%, 100%, .85)',
                'hsla(0,0%,100%,.6)',
                'hsla(204, 4%, 50%, .5)',
                'hsla(204,4%,50%,.15)',
                'hsla(204,4%,50%,.25)',
                'rgba(0, 0, 0, 0.2)',
                'rgba(0,0,0,0.2)',
                'rgba(0,0,0,0.25)',
                'rgba(0,0,0,0.3)',
                'rgba(0,0,0,0.4)',
                'rgba(0,0,0,0.5)',
                'rgba(10, 10, 10, 0.25)',
                'rgba(10, 20, 20, 0.98)',
                'rgba(141, 9, 186, .85)',
                'rgba(15, 27, 33, .3)',
                'rgba(15, 27, 33, .4)',
                'rgba(15, 27, 33, .5)',
                'rgba(15, 27, 33, .55)',
                'rgba(15, 27, 33, .65)',
                'rgba(15, 27, 33, .75)',
                'rgba(15, 27, 33, .85)',
                'rgba(15,27,33,.15)',
                'rgba(15,27,33,.5)',
                'rgba(15,27,33,.85)',
                'rgba(154, 6, 35, .85)',
                'rgba(157, 160, 168, .85)',
                'rgba(21, 48, 67, .85)',
                'rgba(255, 255, 255, .15)',
                'rgba(255, 255, 255, .3)',
                'rgba(255, 255, 255, 0.5)',
                'rgba(255, 83, 0, .85)',
                'rgba(255,255,255,0.1)',
                'rgba(41, 171, 226, .85)',
                'rgba(41, 171, 226, 0.5)',
                'rgba(44, 52, 56, .85)',
                'rgba(79, 0, 188, .75)',
                'rgba(79, 0, 188, .85)',
                'rgba(79,0,188,.75)',
                'rgba(9, 63, 186, .85)',
            ]
        }
    }   
}
</script>

<template>
	<div>
        <div class="color" v-for="color in colors" :style="{ backgroundColor: color }">
            <div class="color__name">{{ color }}</div>
        </div>
    </div>
</template>

<style scoped>
    .color {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100px;
        width: 100%;
        margin-bottom: 1rem;
    }

    .color__name {
        color: #fff;
        font-size: 1.5rem;
        font-weight: 700;
    }
</style>