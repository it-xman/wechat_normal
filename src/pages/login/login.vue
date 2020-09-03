<template>
	<view>

	</view>
</template>

<script>
	export default {
		data() {
            return {
                form: {
                    name: '',
                    intro: '',
                    sex: ''
                },
                checkboxList: [
                    {
                        name: '苹果',
                        checked: false,
                        disabled: false
                    },
                    {
                        name: '雪梨',
                        checked: false,
                        disabled: false
                    },
                    {
                        name: '柠檬',
                        checked: false,
                        disabled: false
                    }
                ],
                radioList: [
                    {
                        name: '鲜甜',
                        disabled: false
                    },
                    {
                        name: '麻辣',
                        disabled: false
                    }
                ],
                radio: '',
                switchVal: false
            };
		},
		methods: {

		}
	}
</script>

<style>

</style>
