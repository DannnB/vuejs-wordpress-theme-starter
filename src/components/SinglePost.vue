<template>
    <b-container class="bv-example-row">
			<b-row>
				<b-col>
                    <!-- will output post content base on this slug -->
					<h1>{{ slug }}</h1>
				</b-col>
			</b-row>
			<b-row>
				<b-col>
					<h2>Heading</h2>
					<p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
				</b-col>
			</b-row>
    </b-container>
</template>

<script>


export default {
    props: ['slug'],
	data() {
		return {
			
		}
	}
}
</script>