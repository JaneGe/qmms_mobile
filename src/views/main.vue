<template>
	<div class="l-container">
		<div class="l-header"></div>
		<div class="l-body">
			<div class="l-main">
				<div class="profile"></div>
				<div class="link-list">
					<group>
						<cell title="我的优惠券" is-link></cell>
					</group>
				</div>
			</div>
		</div>
		<div class="l-footer"></div>
	</div>
</template>

<script>
	import { Cell, Group } from 'vux'
	export default { components: { Cell, Group } }
</script>

<style>
	.l-main .profile{ height:290px; }
</style>
