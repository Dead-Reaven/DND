<script>

export default {
	data() {
		return {
			teamsWithUsers: [
				{
					"id": 1660, "class_id": 2986, "const": "1", "name": "ЛЕВИ", "hash": "NWdWwwyWj3e57bun", "training_hits": 45, "training_score": 2, "created_at": "2023-11-14T07:11:45.000000Z", "updated_at": "2024-09-18T11:29:08.000000Z", "score": 62, "total_score": 64, "users": [{ "id": 17363, "name": "Білан Ангеліна Павлівна", "pivot": { "team_id": 1660, "user_id": 17363, "gist": "captain" } },
					{ "id": 17364, "name": "Білан Лілія Василівна", "pivot": { "team_id": 1660, "user_id": 17364, "gist": null } }, { "id": 17368, "name": "Левицька Валерія Андріївна", "pivot": { "team_id": 1660, "user_id": 17368, "gist": null } }, { "id": 17370, "name": "Максимів Максим", "pivot": { "team_id": 1660, "user_id": 17370, "gist": null } }, { "id": 17719, "name": "Маханчук Інна", "pivot": { "team_id": 1660, "user_id": 17719, "gist": null } }, { "id": 21044, "name": "Качала Оксана", "pivot": { "team_id": 1660, "user_id": 21044, "gist": null } }, { "id": 20639, "name": "Магда Тетяна", "pivot": { "team_id": 1660, "user_id": 20639, "gist": null } }, { "id": 17379, "name": "Чепіль Роман Омелянович", "pivot": { "team_id": 1660, "user_id": 17379, "gist": null } }]
				},
				{
					"id": 1661, "class_id": 2986, "const": "2", "name": "ФУТБОЛ", "hash": "GG1nDo48s801b45h", "training_hits": 51, "training_score": 2, "created_at": "2023-11-14T07:11:45.000000Z", "updated_at": "2024-10-03T09:01:15.000000Z", "score": 36, "total_score": 38, "users": [{ "id": 17217, "name": "Гнатишин Володимир Михайлович", "pivot": { "team_id": 1661, "user_id": 17217, "gist": null } },
					{ "id": 17341, "name": "Кіник Софія Павлівна", "pivot": { "team_id": 1661, "user_id": 17341, "gist": null } }, { "id": 17365, "name": "Кметь Олег Романович", "pivot": { "team_id": 1661, "user_id": 17365, "gist": null } }, { "id": 17366, "name": "Гоєв Василь Васильович", "pivot": { "team_id": 1661, "user_id": 17366, "gist": "captain" } }, { "id": 17371, "name": "Подібка Мар'яна Олегівна", "pivot": { "team_id": 1661, "user_id": 17371, "gist": null } }, { "id": 17767, "name": "Коптева Надія", "pivot": { "team_id": 1661, "user_id": 17767, "gist": null } }, { "id": 17372, "name": "Прус Назарій Васильович", "pivot": { "team_id": 1661, "user_id": 17372, "gist": null } }, { "id": 17373, "name": "Рудка Софія Андріївна", "pivot": { "team_id": 1661, "user_id": 17373, "gist": null } }, { "id": 20283, "name": "Русняк Олеся", "pivot": { "team_id": 1661, "user_id": 20283, "gist": null } }, { "id": 17374, "name": "Ручинський Назарій Васильович", "pivot": { "team_id": 1661, "user_id": 17374, "gist": null } }, { "id": 19677, "name": "Хрущев Юрій", "pivot": { "team_id": 1661, "user_id": 19677, "gist": null } }, { "id": 17380, "name": "Човган Кіра Русланівна", "pivot": { "team_id": 1661, "user_id": 17380, "gist": null } }]
				},
				{ "id": 1662, "class_id": 2986, "const": "3", "name": "ЧЄЛІКИ", "hash": "7nPM6JVMW8CP6Pvx", "training_hits": 47, "training_score": 5, "created_at": "2023-11-14T07:11:45.000000Z", "updated_at": "2024-09-23T09:26:35.000000Z", "score": 106, "total_score": 111, "users": [{ "id": 10102, "name": "Кифор Яна Ігорівна", "pivot": { "team_id": 1662, "user_id": 10102, "gist": "captain" } }, { "id": 18427, "name": "Гончарова Тетяна", "pivot": { "team_id": 1662, "user_id": 18427, "gist": null } }, { "id": 18626, "name": "Гонцовська Олена", "pivot": { "team_id": 1662, "user_id": 18626, "gist": null } }, { "id": 17375, "name": "Тичков Максим Васильович", "pivot": { "team_id": 1662, "user_id": 17375, "gist": null } }, { "id": 17376, "name": "Ткачук Яна Василівна", "pivot": { "team_id": 1662, "user_id": 17376, "gist": null } }, { "id": 17377, "name": "Тростянчин Діана Андріївна", "pivot": { "team_id": 1662, "user_id": 17377, "gist": null } }, { "id": 17378, "name": "Турчин Матвій Андрійович", "pivot": { "team_id": 1662, "user_id": 17378, "gist": null } }, { "id": 17381, "name": "Яремко Олег Андрійович", "pivot": { "team_id": 1662, "user_id": 17381, "gist": null } }] }]
			,
			games: {
				"1660": { "replies_count": 10, "training_score": 10, "score": 20, "total_score": 30, "isWin": true },
				"1661": { "replies_count": 0, "training_score": 0, "score": 0, "total_score": 0, "isWin": false },
				"1662": { "replies_count": 0, "training_score": 0, "score": 0, "total_score": 0, "isWin": false }
			},
			trainingHits: { "9978": 3 }
		}
	},

	methods: {
		onChangeCaptain(team, user) {
			// Uncomment when ready to integrate with backend
			// this.axios.post(`teacher/teams/${team.id}/captain/${user.id}`).then(resp => {
			// 	if (confirm('Потрібно перезавантажити дані.')) {
			// 		location.reload();
			// 	}
			// });
		},

		isCaptain(team, user) {
			return user?.pivot.gist === 'captain';
		},

		// Initiate dragging; add a flag for both desktop & mobile
		onDragStart(event, user) {
			this.draggedUserID = user.id;
			if (event.dataTransfer) {
				event.dataTransfer.dropEffect = 'move';
				event.dataTransfer.effectAllowed = 'move';
				event.dataTransfer.setData('userID', user.id.toString());
			}
		},

		// Handle drop logic for both desktop and mobile
		onDrop(event, teamID, index) {
			const userID = this.draggedUserID || parseInt(event.dataTransfer?.getData('userID'));
			if (!userID) return;

			let targetUser;

			this.teamsWithUsers = this.teamsWithUsers.map(team => {
				const newUsers = team.users.filter(user => {
					if (user.id === userID && !user.pivot.gist && user.pivot.team_id !== teamID) {
						user.pivot.team_id = teamID;
						targetUser = user; // Store user for later
						return false; // Exclude the dragged user from current team
					}
					return true;
				});
				return { ...team, users: newUsers };
			});

			if (targetUser) this.teamsWithUsers[index].users.push(targetUser);

			this.draggedUserID = null; // Reset dragged user ID
		},
	},
};


</script>

<template>
	<div class="teams-wrap">
		<div class="teams">
			<template v-for="(team, index) in teamsWithUsers" :key="team.id">
				<div v-if="team.users.length" class="team" @dragover.prevent @dragenter.prevent
					@drop="onDrop($event, team.id, index)">
					<h3 contenteditable @keydown.enter.prevent="$event.target.blur()"
						@focusout="($event.target.textContent !== team.name) && onChangeTeamName(team, $event.target.textContent)"
						spellcheck="false" title="Придумайте унікальну назву для цієї команди">
						{{ team.name }}
					</h3>
					<hr />
					<section class="scores">
						<div>
							<small class="remark">Бали за підготовку</small>
							<div class="score" title="Бали за підготовку (середнє арифметичне)">
								{{ games[team.id]?.training_score || 0 }}
							</div>
						</div>

						<div class="score" style="font-size: 40px; cursor: pointer" @click="recalculateTeamScore(team)"
							title="Загальний бал. Натисніть щоб перерахувати">
							<!-- @todo Вивести сумарний бал -->
							{{ games[team.id]?.total_score || 0 }}
						</div>
						<!--<div class="recalculate-button" title="Перерахувати бали команди" @click="recalculateTeamScore(team)">
								🧮
							</div>-->
						<div>
							<small class="remark">Бали за гру</small>
							<div class="score" title="Бали за правильні відповіді у грі">
								{{ games[team.id]?.score || 0 }}
							</div>
						</div>
					</section>
					<hr />

					<div class="participants">
						<div v-for="(user, key) in team.users" :key="user.id" @dragstart="onDragStart($event, user)"
							:draggable="!user.pivot.gist">
							<input type="radio" :name="`captain_${team.id}`" class="captain"
								@change="onChangeCaptain(team, user)" :checked="isCaptain(team, user)"
								:title="isCaptain(team, user) ? 'Капітан доманди' : 'Назначити капітаном команди'" />
							{{ user.name }}
							<!-- <span v-if="trainingHits[user.id]" title="Переглянуто підготовчих матеріалів">
							<sup style="color: var(--orange)">★{{ trainingHits[user.id] }}</sup>
						</span> -->
						</div>
					</div>
					<div class="qr" :data-team-hash="team.hash"
						@click.exact="$store.copyText($event.target.closest('div')?.getAttribute('data-qr-url'))"
						@click.ctrl="$store.open($event.target.closest('div')?.getAttribute('data-qr-url'))">
						<!-- QR -->
					</div>
					<!-- <img src="@/assets/img/team-children.png" alt="Команда" class="children" /> -->
				</div>
			</template>

		</div>
	</div>


</template>

<style lang="scss" scoped>
.teams {
	display: flex;
	justify-content: center;
	gap: 10px;
	flex-wrap: wrap;
}

.team {
	width: 32%;
	padding: 20px;
	border: 3px solid;
	border-radius: 16px;
	display: flex;
	flex-direction: column;
	min-width: min(320px, 90dvw);
	overflow: hidden;

	& [draggable="true"] {
		transition: all 0.3s ease;
		cursor: grab;

		&:hover {
			background: rgba(255, 255, 255, 0.299);
		}
	}

	h3 {
		text-align: center;
		font-size: 26px;
		color: #e72667;
		margin: 0;
		line-height: 1;
		min-height: 52px;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.scores {
		display: flex;
		justify-content: space-around;
		align-items: center;
		gap: 3px;

		.remark {
			font-size: 12px;
			max-width: 63px;
			text-align: center;
			color: #b8b1ee;
			display: block;
		}

		.score {
			text-align: center;
			font-weight: bold;
			color: var(--orange);
		}
	}

	hr {
		margin: 15px 20px;
		border-top: 2px solid #e72667;
	}

	.recalculate-button {
		cursor: pointer;
		transition: all .3s linear;
	}

	.recalculate-button:hover {
		transform: scale(1.2);
	}

	.qr {
		display: flex;
		justify-content: center;
		margin-top: 20px;
		cursor: none !important;
	}

	.qr:not(:hover) {
		filter: blur(10px);
		opacity: 0.2;
	}

	.participants {
		flex-grow: 1;
		text-align: left;
	}

	.participants>*:not(:last-child) {
		margin-bottom: 10px;
	}

	.captain {
		margin-right: 8px;
		vertical-align: middle;
		cursor: pointer;
	}

	/*.captain:not(:checked) {visibility: hidden;}*/

	img.children {
		transform: translate(20px, 20px);
		opacity: 0.9;
	}
}













.team:nth-child(1) {
	border-color: #e72667;

	hr {
		border-color: #e72667;
	}

	h3,
	.score {
		color: #e72667
	}
}

.team:nth-child(2) {
	border-color: #FF8A00;

	hr {
		border-color: #FF8A00;
	}

	h3,
	.score {
		color: #FF8A00
	}
}

.team:nth-child(3) {
	border-color: #8dc645;

	hr {
		border-color: #8dc645;
	}

	h3,
	.score {
		color: #8dc645
	}
}
</style>
