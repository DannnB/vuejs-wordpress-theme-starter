<template>
	<footer class="footer">
		<b-container class="bv-example-row">
			<b-row>
				<b-col>
					<pages-widget limit="5">Pages</pages-widget>
				</b-col>
				<b-col>
					<recent-posts-widget limit="5">Recent Posts</recent-posts-widget>
				</b-col>
			</b-row>
		</b-container>
	</footer>
</template>

<script>
import RecentPostsWidget from './../widgets/RecentPosts'
import PagesWidget from './../widgets/Pages'

export default {
  components: {
		RecentPostsWidget,
		PagesWidget
	}
}
</script>
