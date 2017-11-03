<template>
    <b-container class="bv-example-row">
			<b-row>
				<b-col>
					<h1>{{ page.title }}</h1>
				</b-col>
			</b-row>
			<b-row>
				<b-col>
					<h2>Heading</h2>
					<p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
					<p><a class="btn btn-secondary" href="#" role="button">View details »</a></p>
				</b-col>
				<b-col>
				</b-col>
				<b-col>
				</b-col>
				<b-col>
				</b-col>
			</b-row>
    </b-container>
</template>

<script>
import RecentPostsWidget from './widgets/RecentPosts'

export default {
	data() {
		return {
			page: {
				title: 'Main Page'
			}
		}
	}
}
</script>

<style lang="scss">
    .jumbotron {
        margin-top: 5%;
    }
</style>