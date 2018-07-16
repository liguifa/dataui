<template>
	<svg class="data-line" width="100%" height="100%" version="1.1" xmlns="http://www.w3.org/2000/svg">
		<line class="data-line-axis data-line-axis-y" x1="10" x2="10" y1="10" y2="calc(100% - 20)"></line>
		<line class="data-line-axis data-line-axis-y" x1="10" x2="calc(100% - 20)" y1="calc(100% - 20)" y2="calc(100% - 20)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 120)" y2="calc(100% - 120)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 220)" y2="calc(100% - 220)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 320)" y2="calc(100% - 320)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 420)" y2="calc(100% - 420)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 520)" y2="calc(100% - 520)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 620)" y2="calc(100% - 620)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 720)" y2="calc(100% - 720)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 820)" y2="calc(100% - 820)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 920)" y2="calc(100% - 920)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1020)" y2="calc(100% - 1020)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1120)" y2="calc(100% - 1120)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1220)" y2="calc(100% - 1220)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1320)" y2="calc(100% - 1320)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1420)" y2="calc(100% - 1420)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1520)" y2="calc(100% - 1520)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1620)" y2="calc(100% - 1620)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1720)" y2="calc(100% - 1720)"></line>
		<line class="data-line-axis data-line-axis-dotted" x1="10" x2="calc(100% - 20)" y1="calc(100% - 1820)" y2="calc(100% - 1820)"></line>
		<polyline class="data-line-content" points="10,10 110,90 210,250 310,430 410,120"></polyline>
		<circle class="data-line-node" cx="110" cy="90" r="4"/>
		<circle class="data-line-node" cx="210" cy="250" r="4" />
		<circle class="data-line-node" cx="310" cy="430" r="4" />
		<rect class="data-line-rect" x="calc(100% - 200)" y="20"></rect>
		<text class="data-line-rect-text" x="calc(100% - 500)" fill="red" y="20">test</text>
	</svg>
</template>

<script>
export default {
	data(){

	}
}
</script>

<style>
	.data-line-axis{
		stroke:#ebebeb;
		stroke-width:1;
	}

	.data-line-axis-x,.data-line-axis-y{
		stroke: #dedede;
	}

	.data-line-axis-dotted{
		stroke-dasharray: 8 2;
	}

	.data-line-content{
		stroke: #0d84f3;
		stroke-width: 2;
		fill: transparent;
	}

	.data-line-node{
		stroke:#1890ff;
		stroke-width:0px;
		fill:#1890ff;
	}

	.data-line-rect{
		width: 42px;
		height: 20px;
		fill: #0d84f3;
		stroke: 0px;
	}
</style>
