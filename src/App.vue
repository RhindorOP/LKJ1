<template>
	<v-app>
		<v-app-bar color="indigo darken-4" dark app hide-on-scroll>
			<v-card
				style="width:100vw"
				class="d-flex justify-space-between align-center text-h4"
				color="transparent"
				flat
			>
				<v-menu offset-y>
					<template v-slot:activator="{ on, attrs }">
						<v-btn icon v-bind="attrs" v-on="on">
							<v-icon>mdi-menu</v-icon>
						</v-btn>
					</template>
					<v-list>
						<v-list-item class="pa-0">
							<v-btn href="https://rhindorop.github.io/LKJ1/" text>LKJ 1</v-btn>
						</v-list-item>
						<v-list-item class="pa-0">
							<v-btn href="https://rhindorop.github.io/LKJ2/" text>LKJ 2</v-btn>
						</v-list-item>
						<v-list-item class="pa-0">
							<v-btn href="https://rhindorop.github.io/LKJ3/" text>LKJ 3</v-btn>
						</v-list-item>
						<v-list-item class="pa-0">
							<v-btn href="https://rhindorop.github.io/LKJ4/" text>LKJ 4</v-btn>
						</v-list-item>
						<v-list-item class="pa-0">
							<v-btn href="https://rhindorop.github.io/LKJ5/" text>LKJ 5</v-btn>
						</v-list-item>
					</v-list>
				</v-menu>

				<div class="d-flex">
					Admin
					<div class="d-none d-sm-flex">istrator &zwnj;</div>
					<div class="d-none d-sm-flex">Lee Kang-Jin &zwnj;</div>
					<div class="d-flex d-sm-none">&zwnj; LKJ &zwnj;</div>1
				</div>
				<div></div>
			</v-card>
		</v-app-bar>
		<v-main>
			<Story />
		</v-main>
	</v-app>
</template>

<script>
import Story from "./components/Story";

export default {
	name: "App",

	components: {
		Story,
	},

	data: () => ({
		//
	}),
};
</script>
