<template>
	<div>
		<NuxtRouteAnnouncer />
		<NuxtLayout>
			<!-- Header Start -->
			<header>
				<ul>
					<li>
						<nuxt-link to="/">Home</nuxt-link>
						<nuxt-link to="/events">Events</nuxt-link>
					</li>
				</ul>
			</header>
			<!-- Header Ends -->

			<NuxtPage />
		</NuxtLayout>
	</div>
</template>
