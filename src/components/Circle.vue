

<template>
	<div class="circle-block">
		<a href="#" class="circle-block__first">
			<svg class="circle-first__icon" width="15.625vw" height="7.813vw">
				<use href="@/assets/img/sprite.svg#first-icon"></use>
			</svg>
			<span class="circle-block__link">Все филиалы</span>
		</a>

		<div class="circle-block__second">
			<svg class="circle-second__icon" width="15.625vw" height="7.813vw">
				<use href="@/assets/img/sprite.svg#second-icon"></use>
			</svg>

			<div class="cirlce-block__contains">
				<div class="cirlce-block__wrap">
					<svg class="circle-block__icon" width="1.042vw" height="1.042vw">
						<use href="../assets/img/sprite.svg#star-icon"></use>
					</svg>
					<span class="circle-block__value">5</span>
				</div>
				<p class="circle-block__text">
					Рейтиг Вуза по <br />
					QS WUR
				</p>
			</div>
		</div>

		<div class="circle-block__third">
			<svg class="circle-third__icon">
				<use href="@/assets/img/sprite.svg#third-icon"></use>
			</svg>

			<div class="circle-block__wrapper">
				<div class="cirlce-block__contains ">
					<div class="cirlce-block__wrap">
						<span class="circle-block__value">1 302</span>
						<svg class="circle-block__icon" width="0.781vw" height="0.781vw">
							<use href="/img/sprite.d34130e0.svg#icon2"></use>
						</svg>
					</div>
					<p class="circle-block__text">Преподавателей</p>
				</div>

				<div class="cirlce-block__contains">
					<div class="cirlce-block__wrap">
						<span class="circle-block__value">293</span>
						<svg class="circle-block__icon" width="0.781vw" height="0.781vw">
							<use href="../assets/img/sprite.svg#icon2"></use>
						</svg>
					</div>
					<p class="circle-block__text">
						научных <br />
						работников
					</p>
				</div>
			</div>
		</div>

		<div class="circle-block__fourth">
			<svg class="circle-fourth__icon">
				<use href="@/assets/img/sprite.svg#fourth-icon"></use>
			</svg>

			<div class="cirlce-block__contains">
				<span class="circle-block__value">4.3</span>
				<p class="circle-block__text">средний балл</p>
			</div>
		</div>

		<div class="circle-block__fifth" v-on:click="cr_click" >
			<svg class="circle-fifth__icon">
				<use href="@/assets/img/sprite.svg#fifth-icon"></use>
			</svg>

			<div class="cirlce-block__wrapper">
				<div class="cirlce-block__contains ">
					<span class="circle-block__value">291</span>
					<p class="circle-block__text">
						кол-во <br />
						публикаций
					</p>
				</div>

				<div class="cirlce-block__contains">
					<span class="circle-block__value">23,6</span>
					<p class="circle-block__text">
						Выполнение <br />
						плана, % 
					</p>
				</div>

				<div class="cirlce-block__contains">
					<span class="circle-block__value">ХХ</span>
					<p class="circle-block__text">
						заключенные <br />
						договора
					</p>
				</div>
			</div>
		</div>

		<div class="circle-block__sixth">
			<svg class="circle-sixth__icon">
				<use href="@/assets/img/sprite.svg#sixth-icon"></use>
			</svg>

			<div class="cirlce-block__wrapper">
				<div class="cirlce-block__contains">
					<div class="cirlce-block__wrap">
						<span class="circle-block__value">3,28  <span></span></span>
						<svg class="circle-block__icon" width="0.781vw" height="0.781vw">
							<use href="../assets/img/sprite.svg#icon1"></use>
						</svg>
					</div>
					<p class="circle-block__text">Денежные <br />Средства, млрд.</p>
				</div>

				<div class="cirlce-block__contains">
					<div class="cirlce-block__wrap">
						<span class="circle-block__value">4,9 <span></span></span>
						<svg class="circle-block__icon" width="0.781vw" height="0.781vw">
							<use href="../assets/img/sprite.svg#icon2"></use>
						</svg>
					</div>
					<p class="circle-block__text">Касса, млн.</p>
				</div>
			</div>
		</div>

		<div class="circle-block__middle">
			<span>38 633</span>
			<p>ОБучающихся</p>
		</div>

		<div class="circle__parts">
			<div class="circle__part-top">
				<div class="circle__part-text">
					<span class='span_84'>84%</span>
					<span class='span_text'
						>Абсолютная <br />
						успеваемость</span
					>
				</div>

				<svg width="18.229vw" height="9.167vw" viewBox="0 0 350 176" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M309.81 170.43C309.72 167.58 309.53 164.7 309.26 161.88L349.19 158C349.54 161.66 349.78 165.38 349.91 169.06L309.81 170.43Z" fill="#0b1b51" />
					<path d="M308.78 157.62C308.42 154.79 307.96 151.95 307.42 149.17L346.8 141.54C347.5 145.15 348.09 148.83 348.56 152.54L308.78 157.62Z" fill="#0b1b51" />
					<path d="M306.54 145C305.91 142.24 305.19 139.45 304.38 136.73L342.85 125.37C343.85 128.91 344.85 132.53 345.66 136.12L306.54 145Z" fill="#0b1b51" />
					<path d="M303.1 132.64C302.21 129.96 301.23 127.26 300.16 124.64L337.37 109.64C338.75 113.07 340.04 116.59 341.19 120.08L303.1 132.64Z" fill="#0b1b51" />
					<path d="M298.51 120.69C297.37 118.1 296.13 115.51 294.82 112.99L330.43 94.51C332.13 97.78 333.74 101.15 335.22 104.51L298.51 120.69Z" fill="#0b1b51" />
					<path d="M292.79 109.23C291.41 106.76 289.93 104.3 288.38 101.91L322.07 80.14C324.07 83.24 326 86.44 327.79 89.65L292.79 109.23Z" fill="#0b1b51" />
					<path d="M286 98.35C284.38 96.01 282.67 93.7 280.91 91.47L312.4 66.61C314.68 69.5 316.9 72.5 319 75.53L286 98.35Z" fill="#0b1b51" />
					<path d="M278.21 88.1601C276.38 85.9901 274.45 83.8401 272.49 81.7901L301.49 54.0601C304.04 56.7201 306.49 59.5001 308.9 62.3101L278.21 88.1601Z" fill="#0b1b51" />
					<path d="M269.48 78.74C267.48 76.74 265.33 74.79 263.18 72.93L289.42 42.59C292.2 45 294.95 47.53 297.58 50.11L269.48 78.74Z" fill="#0b1b51" />
					<path d="M259.9 70.1801C257.69 68.3901 255.4 66.6401 253.08 65.0001L276.33 32.3101C279.33 34.4501 282.33 36.7101 285.17 39.0301L259.9 70.1801Z" fill="#0b1b51" />
					<path d="M249.55 62.5701C247.18 61.0001 244.73 59.4801 242.27 58.0601L262.27 23.3101C265.46 25.1501 268.64 27.1201 271.71 29.1601L249.55 62.5701Z" fill="#0b1b51" />
					<path d="M238.52 56C236.01 54.66 233.43 53.38 230.84 52.2L247.47 15.7C250.82 17.23 254.18 18.89 257.47 20.63L238.52 56Z" fill="#0b1b51" />
					<path d="M226.92 50.46C224.3 49.37 221.6 48.34 218.92 47.46L232 9.48999C235.49 10.69 239 12.02 242.4 13.49L226.92 50.46Z" fill="#0b1b51" />
					<path d="M214.84 46.09C212.13 45.26 209.36 44.5 206.6 43.83L215.96 4.82996C219.55 5.68996 223.16 6.67996 226.68 7.76996L214.84 46.09Z" fill="#fb9b2b" />
					<path d="M202.43 42.9C199.65 42.33 196.81 41.83 194 41.44L199.59 1.71997C203.24 2.22997 206.92 2.86997 210.53 3.61997L202.43 42.9Z" fill="#fb9b2b" />
					<path d="M189.75 40.9101C186.93 40.6001 184.06 40.3801 181.21 40.2501L183 0.180054C186.69 0.350054 190.41 0.630054 194.06 1.03005L189.75 40.9101Z" fill="#fb9b2b" />
					<path d="M168.35 40.28L166.4 0.21C170.07 0 173.82 0 177.49 0L176.93 40.11C174.07 40.09 171.18 40.14 168.35 40.28Z" fill="#fb9b2b" />
					<path d="M155.56 41.4999L149.84 1.79995C153.48 1.27995 157.19 0.859946 160.84 0.569946L164.04 40.5699C161.23 40.7799 158.37 41.0999 155.56 41.4999Z" fill="#fb9b2b" />
					<path d="M143 43.94L133.49 4.99997C137.07 4.12997 140.73 3.35997 144.36 2.71997L151.36 42.22C148.54 42.67 145.73 43.27 143 43.94Z" fill="#fb9b2b" />
					<path d="M130.68 47.56L117.5 9.66999C120.98 8.45999 124.5 7.34999 128.1 6.35999L138.84 45C136.1 45.77 133.36 46.63 130.68 47.56Z" fill="#fb9b2b" />
					<path d="M118.801 52.34L102.061 15.89C105.401 14.35 108.841 12.89 112.281 11.58L126.661 49C124.001 50 121.371 51.16 118.801 52.34Z" fill="#fb9b2b" />
					<path d="M107.43 58.23L87.29 23.54C90.48 21.69 93.76 19.92 97.06 18.28L114.95 54.19C112.41 55.44 109.88 56.81 107.43 58.23Z" fill="#fb9b2b" />
					<path d="M96.6503 65.19L73.3203 32.56C76.3203 30.41 79.4303 28.34 82.5503 26.4L103.76 60.4C101.36 61.93 99.0003 63.53 96.6503 65.19Z" fill="#fb9b2b" />
					<path d="M86.5698 73.14L60.2598 42.86C63.0398 40.44 65.9298 38.08 68.8598 35.86L93.2098 67.73C90.9998 69.45 88.7198 71.27 86.5698 73.14Z" fill="#fb9b2b" />
					<path d="M77.2905 82.0001L48.2305 54.3501C50.7705 51.6801 53.4305 49.0601 56.1305 46.5601L83.3905 76.0001C81.3005 77.9301 79.2505 79.9501 77.2905 82.0001Z" fill="#fb9b2b" />
					<path d="M68.8798 91.7301L37.3398 66.9301C39.6198 64.0301 42.0198 61.1701 44.4698 58.4301L74.3798 85.1601C72.4898 87.2801 70.6398 89.4901 68.8798 91.7301Z" fill="#fb9b2b" />
					<path d="M61.4297 102.19L27.6797 80.51C29.6797 77.4 31.7997 74.33 33.9797 71.36L66.2797 95.14C64.5997 97.42 62.9997 99.8 61.4297 102.19Z" fill="#fb9b2b" />
					<path d="M54.9996 113.32L19.3496 94.94C21.0396 91.66 22.8596 88.39 24.7496 85.23L59.1696 105.83C57.7096 108.27 56.3096 110.79 54.9996 113.32Z" fill="#fb9b2b" />
					<path d="M49.6797 125L12.4297 110.12C13.7897 106.7 15.2897 103.28 16.8797 99.93L53.1097 117.14C51.8797 119.73 50.7297 122.37 49.6797 125Z" fill="#fb9b2b" />
					<path d="M45.5 137.13L7 125.89C8 122.35 9.19 118.8 10.45 115.33L48.15 129C47.18 131.68 46.29 134.41 45.5 137.13Z" fill="#fb9b2b" />
					<path d="M42.4998 149.6L3.08984 142.09C3.77984 138.46 4.59984 134.81 5.50984 131.25L44.3598 141.25C43.6598 144 42.9998 146.8 42.4998 149.6Z" fill="#fb9b2b" />
					<path d="M40.6998 162.3L0.759766 158.58C1.09977 154.91 1.56977 151.2 2.13977 147.58L41.7598 153.83C41.3298 156.61 40.9998 159.47 40.6998 162.3Z" fill="#fb9b2b" />
					<path d="M40.11 175.16H0V175C0 171.38 0.11 167.72 0.33 164.11L40.33 166.56C40.16 169.35 40.07 172.19 40.07 174.99L40.11 175.16Z" fill="#fb9b2b" />
				</svg>
			</div>

			<div class="circle__part-bottom">
				<div class="circle__part-text">
					<span>56%</span>
					<span>Качественная <br> успеваемость</span>
				</div>

				<svg width="18.229vw" height="9.167vw" viewBox="0 0 350 176" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M0.799844 17.79C0.449844 14.13 0.209844 10.4 0.0898438 6.72L40.1798 5.42999C40.2698 8.26999 40.4598 11.15 40.7198 13.98L0.799844 17.79Z" fill="#fb9b2b" />
					<path d="M3.16016 34.27C2.46016 30.65 1.87016 26.96 1.41016 23.27L41.2002 18.2C41.5602 21.02 42.0102 23.86 42.5502 26.64L3.16016 34.27Z" fill="#0b1b51" />
					<path d="M7.0898 50.46C6.0898 46.93 5.0898 43.31 4.2998 39.71L43.4298 30.86C44.0598 33.63 44.7798 36.42 45.5798 39.14L7.0898 50.46Z" fill="#0b1b51" />
					<path d="M7.0898 50.46C6.0898 46.93 5.0898 43.31 4.2998 39.71L43.4298 30.86C44.0598 33.63 44.7798 36.42 45.5798 39.14L7.0898 50.46Z" fill="#0b1b51" />
					<path d="M7.0898 50.46C6.0898 46.93 5.0898 43.31 4.2998 39.71L43.4298 30.86C44.0598 33.63 44.7798 36.42 45.5798 39.14L7.0898 50.46Z" fill="#0b1b51" />
					<path d="M7.0898 50.46C6.0898 46.93 5.0898 43.31 4.2998 39.71L43.4298 30.86C44.0598 33.63 44.7798 36.42 45.5798 39.14L7.0898 50.46Z" fill="#0b1b51" />
					<path d="M7.0898 50.46C6.0898 46.93 5.0898 43.31 4.2998 39.71L43.4298 30.86C44.0598 33.63 44.7798 36.42 45.5798 39.14L7.0898 50.46Z" fill="#0b1b51" />
					<path d="M12.56 66.21C11.18 62.78 9.9 59.27 8.75 55.77L46.85 43.23C47.73 45.92 48.72 48.62 49.78 51.23L12.56 66.21Z" fill="#0b1b51" />
					<path d="M19.4802 81.32C17.7802 78.04 16.1802 74.68 14.7002 71.32L51.4302 55.19C52.5702 57.78 53.8102 60.37 55.1102 62.9L19.4802 81.32Z" fill="#0b1b51" />
					<path d="M27.8194 95.71C25.8194 92.61 23.8994 89.41 22.1094 86.2L57.1094 66.65C58.4894 69.12 59.9694 71.59 61.5094 73.98L27.8194 95.71Z" fill="#0b1b51" />
					<path d="M37.4904 109.25C35.2104 106.36 33.0004 103.36 30.9004 100.33L63.9004 77.53C65.5204 79.87 67.2304 82.19 68.9804 84.42L37.4904 109.25Z" fill="#0b1b51" />
					<path d="M48.3902 121.81C45.8502 119.15 43.3902 116.36 40.9902 113.55L71.6902 87.74C73.5202 89.91 75.4402 92.06 77.4002 94.12L48.3902 121.81Z" fill="#0b1b51" />
					<path d="M60.44 133.29C57.66 130.88 54.91 128.35 52.29 125.76L80.42 97.16C82.42 99.16 84.57 101.11 86.71 102.97L60.44 133.29Z" fill="#0b1b51" />
					<path d="M73.5194 143.59C70.5194 141.45 67.5195 139.19 64.6895 136.86L89.9995 105.73C92.2094 107.52 94.4995 109.27 96.8195 110.92L73.5194 143.59Z" fill="#0b1b51" />
					<path d="M87.5396 152.61C84.3496 150.77 81.1696 148.79 78.0996 146.74L100.34 113.36C102.71 114.94 105.15 116.46 107.61 117.88L87.5396 152.61Z" fill="#0b1b51" />
					<path d="M102.35 160.25C98.9896 158.72 95.6396 157.05 92.3496 155.31L111.35 119.96C113.85 121.3 116.43 122.58 119.02 123.76L102.35 160.25Z" fill="#0b1b51" />
					<path d="M117.86 166.45C114.37 165.25 110.86 163.91 107.46 162.45L122.95 125.45C125.57 126.55 128.26 127.58 130.95 128.5L117.86 166.45Z" fill="#0b1b51" />
					<path d="M133.86 171.13C130.28 170.27 126.68 169.28 123.15 168.18L135 129.87C137.72 130.71 140.49 131.47 143.24 132.14L133.86 171.13Z" fill="#0b1b51" />
					<path d="M150.229 174.26C146.569 173.74 142.889 173.1 139.279 172.35L147.439 133.07C150.209 133.65 153.049 134.14 155.859 134.54L150.229 174.26Z" fill="#0b1b51" />
					<path d="M166.79 175.81C163.11 175.64 159.39 175.35 155.74 174.95L160.11 135.07C162.94 135.38 165.81 135.6 168.65 135.73L166.79 175.81Z" fill="#0b1b51" />
					<path d="M175.06 176C174.15 176 173.24 176 172.33 176L172.93 135.89H175.05C177.19 135.89 179.36 135.84 181.51 135.74L183.41 175.81C180.64 175.93 177.83 176 175.06 176Z" fill="#0b1b51" />
					<path d="M188.95 175.45L185.79 135.45C188.62 135.23 191.49 134.91 194.3 134.51L200 174.23C196.33 174.75 192.62 175.16 188.95 175.45Z" fill="#0b1b51" />
					<path d="M205.46 173.36L198.52 133.85C201.32 133.36 204.13 132.77 206.89 132.1L216.33 171.1C212.75 172 209.09 172.72 205.46 173.36Z" fill="#0b1b51" />
					<path d="M221.71 169.69L211 131C213.73 130.24 216.48 129.39 219.16 128.46L232.3 166.36C228.84 167.6 225.27 168.71 221.71 169.69Z" fill="#0b1b51" />
					<path d="M237.54 164.49L223.21 127C225.85 126 228.5 124.88 231.08 123.7L247.78 160.18C244.42 161.73 241 163.17 237.54 164.49Z" fill="#0b1b51" />
					<path d="M252.77 157.81L234.92 121.89C237.46 120.63 239.99 119.27 242.45 117.89L262.54 152.61C259.35 154.41 256.07 156.17 252.77 157.81Z" fill="#0b1b51" />
					<path d="M267.3 149.71L246.12 115.64C248.53 114.14 250.92 112.55 253.23 110.9L276.53 143.55C273.53 145.69 270.42 147.76 267.3 149.71Z" fill="#0b1b51" />
					<path d="M281 140.26L256.68 108.36C258.94 106.64 261.17 104.82 263.32 102.96L289.6 133.27C286.81 135.68 283.92 138 281 140.26Z" fill="#217AFF" />
					<path d="M37.4904 109.25C35.2104 106.36 33.0004 103.36 30.9004 100.33L63.9004 77.53C65.5204 79.87 67.2304 82.19 68.9804 84.42L37.4904 109.25Z" fill="#0b1b51" />
					<path d="M293.73 129.56L266.51 100.1C268.6 98.17 270.65 96.1 272.62 94.1L301.62 121.79C299.09 124.45 296.43 127.07 293.73 129.56Z" fill="#217AFF" />
					<path d="M305.4 117.71L275.52 90.95C277.41 88.83 279.27 86.63 281.03 84.39L312.55 109.21C310.26 112.1 307.86 115 305.4 117.71Z" fill="#217AFF" />
					<path d="M315.91 104.79L283.63 81C285.32 78.71 286.95 76.34 288.49 73.95L322.22 95.67C320.22 98.75 318.1 101.83 315.91 104.79Z" fill="#217AFF" />
					<path d="M325.15 90.93L290.75 70.29C292.21 67.85 293.62 65.29 294.92 62.81L330.56 81.22C328.87 84.5 327.05 87.76 325.15 90.93Z" fill="#217AFF" />
					<path d="M333 76.24L296.83 59C298.05 56.43 299.21 53.79 300.26 51.16L337.51 66C336.14 69.47 334.63 72.9 333 76.24Z" fill="#217AFF" />
					<path d="M339.5 60.84L301.8 47.12C302.8 44.45 303.67 41.72 304.46 39L343 50.28C341.92 53.82 340.76 57.37 339.5 60.84Z" fill="#217AFF" />
					<path d="M344.43 44.93L305.6 34.88C306.31 32.14 306.94 29.33 307.47 26.54L346.87 34.08C346.18 37.71 345.36 41.36 344.43 44.93Z" fill="#217AFF" />
					<path d="M347.83 28.61L308.21 22.33C308.65 19.53 309.02 16.67 309.28 13.84L349.22 17.61C348.87 21.28 348.41 25 347.83 28.61Z" fill="#217AFF" />
					<path d="M349.65 12.08L309.65 9.56999C309.83 6.73999 309.92 3.85998 309.92 0.999985V0.669983H350V0.999985C350 4.68998 349.88 8.41999 349.65 12.08Z" fill="#217AFF" />
				</svg>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'BlockCircle',
    methods: {
		cr_click: function() {
        
			this.connection.send('cr1_click')
		},
      
	},
	created() {
		const ws_url = 'ws://195.211.102.43:8999'
		this.connection = new WebSocket(ws_url)

		this.connection.onerror = error => {
			console.log(error)
		}
	},
}
</script>

<style lang="scss" scoped>
.circle-block__sixth {
	width: 15.365vw;
	height: 18.229vw;
	transform: translate(-1.5vw, -7.2vw);

	.circle-sixth__icon {
		width: 15.365vw;
		height: 18.229vw;
	}

	.cirlce-block__wrapper {
		display: flex;
		flex-direction: column;
		position: absolute;
		top: 0;
		left: 0;
	}

	.cirlce-block__contains {
		position: static;

		&:first-of-type {
			transform: translate(5vw, 5vw);
		}

		&:last-of-type {
			transform: translate(1vw, 6vw);
		}

		.circle-block__text {
			text-align: center;
		}

		.circle-block__icon {
			position: absolute;
			top: 0;
			right: 1vw;
			margin-right: 0;
		}
	}

	.cirlce-block__wrap {
		position: relative;
	}
}
.circle-block__fifth {
	width: 14.167vw;
	height: 16.667vw;
	position: absolute;
	bottom: 0.5vw;
	left: -0.3vw;
    cursor: pointer;

	.circle-fifth__icon {
		width: 14.167vw;
		height: 16.667vw;
	}

	.cirlce-block__wrapper {
		display: flex;
		flex-direction: column;
		position: absolute;
		top: 0;
		left: 0;
	}

	.circle-block__value {
		font-size: 1.563vw;
	}

	.circle-block__text {
		font-size: 0.521vw;
		line-height: 0.833vw;
	}

	.span_text{
		position: absolute;
		width: 76px;
		height: 34px;
		left: 768px;
		top: 546px;

		font-family: Oswald;
		font-style: normal;
		font-weight: normal;
		font-size: 10px;
		line-height: 15px;
		/* or 155% */

		text-align: center;
		letter-spacing: 0.1em;
		text-transform: uppercase;

		color: #FB9B2B;
	}
	.cirlce-block__contains {
		position: static;

		&:first-of-type {
			transform: translate(1.8vw, 1vw);
		}

		&:nth-of-type(2) {
			transform: translate(3.8vw, 2vw);
		}

		&:last-of-type {
			transform: translate(8vw, 2vw);
		}
	}
}

.circle-block__fourth {
	width: 12.604vw;
	height: 8.177vw;
	position: absolute;
	bottom: -1.4vw;
	left: 50%;
	transform: translateX(-50%);

	.circle-fourth__icon {
		width: 12.604vw;
		height: 8.177vw;
	}
}

svg {
	overflow: visible;
}

.circle-block__third {
	position: absolute;
	bottom: 0;
	right: 0;
	width: 15.417vw;
	height: 17.656vw;
	z-index: 1;
	transform: translate(1.6vw, 0.6vw);

	.cirlce-block__contains {
		position: static;
		transform: none;
		transform: translate(-1.875vw, -2.083vw);

		.cirlce-block__wrap {
			align-items: flex-start;
			position: relative;
			left: 0.5vw;

			.circle-block__icon {
				margin-left: 0.25vw;
				margin-right: 0;
			}
		}

		&:last-of-type {
			transform: translate(-6vw, 0vw);
			.cirlce-block__wrap {
				align-items: baseline;
			}
		}
	}

	.circle-block__wrapper {
		display: flex;
		flex-direction: column;
		position: absolute;
		top: 50%;
		right: 0;
		transform: translateY(-50%);
	}
}

.circle-third__icon {
	width: 15.417vw;
	height: 17.656vw;
}

.circle__parts {
	position: absolute;
	left: 50%;
	transform: translate(-50%, 0);
	top: 0;
	z-index: 2;
	width: 18.594vw;
	height: 18.594vw;
}

.cirlce-block__wrap {
	display: flex;
	align-items: center;
	justify-content: center;

	.circle-block__icon {
		margin-right: 1.25vw;
	}
}

.circle-block__middle {
	position: absolute;
	width: 12.5vw;
	height: 12.5vw;
	border-radius: 50%;
	border: 1px solid rgba(33, 122, 255, 0.48);
	top: 52%;
	left: 50%;
	transform: translate(-50%, -50%);
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	z-index: 1;

	span {
		font-weight: 500;
		font-size: 3.646vw;
	}

	p {
		font-size: 0.938vw;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		margin-top: 0px;
	}
}

.circle-block {
	position: relative;
	width: 36.25vw;
	height: 36.25vw;

	&:after {
		content: '';
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		width: 33.542vw;
		height: 33.542vw;
		border-radius: 50%;
		border: 1px solid rgba(33, 122, 255, 0.48);
		z-index: -1;
	}

	&:before {
		content: '';
		position: absolute;
		top: 52%;
		left: 50%;
		transform: translate(-50%, -50%);
		width: 19.833vw;
		height: 19.833vw;
		border-radius: 50%;
		border: 1px solid rgba(33, 122, 255, 0.48);
		z-index: 1;
	}
}

.cirlce-block__contains {
	position: absolute;
	z-index: 1;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	text-align: center;
}

.circle-block__first {
	position: relative;
	display: flex;
	justify-content: center;
	z-index: 3;
}

.circle-block__link {
	display: block;
	letter-spacing: 0.1em;
	text-transform: uppercase;
	color: #217aff;
	font-size: 0.833vw;
	position: absolute;
	left: 50%;
	top: 50%;
	transform: translate(-50%, -50%);

	&::before {
		content: '';
		position: absolute;
		left: 50%;
		transform: translateX(-50%);
		top: -0.781vw;
		width: 0;
		height: 0;
		border-style: solid;
		border-width: 0 0.286vw 0.495vw 0.286vw;
		border-color: transparent transparent #217aff transparent;
	}
}

.circle-block__value {
	color: #fff;
	font-weight: 500;
	font-size: 1.8vw;
}

.circle-block__text {
	text-align: center;
	letter-spacing: 0.1em;
	text-transform: uppercase;
	color: #627dae;
	font-size: 0.729vw;
	line-height: 1.042vw;
}

.circle-block__second {
	position: absolute;
	right: 0;
	width: 14.323vw;
	height: 17.604vw;
	z-index: 2;
	transform: translate(0.6vw, -6.2vw);

	.circle-block__text {
		position: relative;
		left: 2vw;
	}
}

.circle-second__icon {
	position: absolute;
	top: 0;
	left: 0;
	width: 14.323vw;
	height: 17.604vw;
}

.circle__part-top {
	color: #fb9b2b;
	position: absolute;
	top: 9.8vw;
	left: 0.2vw;

	.circle__part-text {
		position: absolute;
		bottom: -4vw;
		left: 0;
		z-index: 1;
	}
}




.circle__part-text {
	text-align: center;

	span {
		display: block;
	}

	span:first-of-type {
		font-size: 1.146vw;
        line-height: 1.042vw;
        font-weight: 700;
        margin-bottom: 0.156vw;
	}

	span:last-of-type {
		letter-spacing: 0.1em;
		text-transform: uppercase;
		font-size: 0.521vw;
		line-height: 0.781vw;
	}
}

.circle__part-bottom {
	color: #217AFF;
	position: absolute;
	bottom: -9.5vw;
	right: 0.2vw;

	.circle__part-text {
		position: absolute;
		top: -4vw;
		right: -1vw;
		z-index: 1;
	}
}
</style>
