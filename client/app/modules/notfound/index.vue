<template lang="pug">
	.container
		h2.title Error page

</template>

<script>
	import { mapActions, mapGetters } from "vuex";

	//import Service from "../../core/service";

	export default {
		/**
		 * Computed getters
		 */


		/**
		 * Page methods
		 */
		methods: {
			/**
			 * Actions from store
			 */


			/**
			 * Increment counter
			 */

		},

		/**
		 * Socket handlers. Every property is an event handler
		 */
		socket: {

			prefix: "/notfound/",

			//namespace: "/counter",

			events: {
				/**
				 * Counter value is changed
				 * @param  {Number} msg Value of counter
				 */

			}
		},

	};

</script>

<style lang="sass" scoped>
</style>
