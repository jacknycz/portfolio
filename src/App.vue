<template>
  <div id="app">
    <Scene />
    <Header />
    <Intro msg="Jack Nycz"/>
  </div>
</template>

<script>
import Intro from './components/Intro.vue'
import Header from './components/Header.vue'
import Scene from './components/Scene.vue'

export default {
  name: 'App',
  components: {
    Intro,
    Header,
    Scene
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200;300;400;500;523;600;700;800&display=swap');

// COLORS
$black: rgba(32,0,1);

$browndark: rgb(64,15,18);
$browndarkmed: rgb(93,22,18);
$brownlightmed: rgb(20,40,28);
$brownlight: rgb(155,57,26);

$orange: rgb(211,108,27);
$orangelight: rgb(248,151,27);

$yellowdark: rgb(254,196,29);
$yellow: rgb(252,223,97);
$yellowlight: rgb(225,228,114);

body {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Manrope', sans-serif;
  font-size: 16px;
}

// GRID SYSTEM
.container {
	// display: flex;
}

.row {
	display: flex;
	flex-direction: row;
	flex-wrap: nowrap;
	
	@media screen and (max-width: 768px) {
		flex-direction: column;
		
		&-no-mobile {
			flex-direction: row;
		}
	}
	
	&-justify {
		&-reverse {
			flex-direction: row-reverse;
		}

		&-flex-start {
			justify-content: flex-start;
		}
		&-flex-end {
			justify-content: flex-end;
		}
		&-center {
			justify-content: center;
		}
		&-space-between {
			justify-content: space-between;
		}
		&-space-around {
			justify-content: space-around;
		}
		&-space-evenly {
			justify-content: space-evenly;
		}
	}
	
	&-align-items {
		&-flex-start {
			align-items: flex-start;
		}
		&-flex-end {
			align-items: flex-end;
		}
		&-center {
			align-items: center;
		}
		&-stretch {
			align-items: stretch;
		}
		&-baseline {
			align-items: baseline;
		}
	}
	
	&-align-content {
		&-flex-start {
			align-items: flex-start;
		}
		&-flex-end {
			align-items: flex-end;
		}
		&-center {
			align-items: center;
		}
		&-stretch {
			align-items: stretch;
		}
		&-space-between {
			align-items: space-between;
		}
		&-space-around {
			align-items: space-around;
		}
	}
}

// // SAMPLE
// .module {
// 	flex-grow: 1;
// 	height: 60px;
// 	border: 5px solid #ccc;
// 	margin: 5px;
	
// 	&-small {
// 		flex-grow: .2;
// 	}
// }
</style>
