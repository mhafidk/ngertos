<script>
	import PostCard from '../lib/components/post-card.svelte';
</script>

<svelte:head>
	<title>Ngertos.</title>
</svelte:head>

<div class="py-8">
	<h1 class="text-center text-2xl font-semibold md:text-3xl">
		Mau <span class="text-lime-600">belajar</span> apa hari ini?
	</h1>
	<div class="mt-5 flex w-full items-center">
		<input
			type="text"
			class="form-input h-10 w-10/12 rounded-l border-transparent bg-lime-50 px-4 py-2 focus:border-lime-600 focus:bg-white focus:ring-0 md:w-11/12"
		/>
		<div
			class="flex h-10 w-2/12 items-center justify-center rounded-r border border-lime-600 bg-lime-600 hover:cursor-pointer hover:border-lime-700 hover:bg-lime-700 md:w-1/12"
		>
			<svg
				xmlns="http://www.w3.org/2000/svg"
				height="34px"
				viewBox="0 -960 960 960"
				width="34px"
				fill="#ffffff"
				class=""
				><path
					d="M784-120 532-372q-30 24-69 38t-83 14q-109 0-184.5-75.5T120-580q0-109 75.5-184.5T380-840q109 0 184.5 75.5T640-580q0 44-14 83t-38 69l252 252-56 56ZM380-400q75 0 127.5-52.5T560-580q0-75-52.5-127.5T380-760q-75 0-127.5 52.5T200-580q0 75 52.5 127.5T380-400Z"
				/></svg
			>
		</div>
	</div>
</div>
<div class="">
	<div class="flex flex-wrap gap-x-2 gap-y-6">
		<div class="flex h-36 w-28 grow flex-col items-center rounded md:h-56 md:w-44">
			<img
				src="/math.webp"
				alt="Matematika"
				class="h-28 w-full rounded-lg object-cover transition ease-in-out hover:scale-105 md:h-44"
			/>
			<a
				href="/materi?search=matematika"
				class="mt-2 inline-block text-lg font-medium hover:text-lime-600 md:mt-3"
			>
				Matematika
			</a>
		</div>
		<div class="flex h-36 w-28 grow flex-col items-center rounded md:h-56 md:w-44">
			<img
				src="/programming.webp"
				alt="Informatika"
				class="h-28 w-full rounded-lg object-cover transition ease-in-out hover:scale-105 md:h-44"
			/>
			<a
				href="/materi?search=informatika"
				class="mt-2 inline-block text-lg font-medium hover:text-lime-600 md:mt-3"
			>
				Informatika
			</a>
		</div>
		<div class="flex h-36 w-28 grow flex-col items-center rounded md:h-56 md:w-44">
			<img
				src="/english.webp"
				alt="Bahasa Inggris"
				class="h-28 w-full rounded-lg object-cover transition ease-in-out hover:scale-105 md:h-44"
			/>
			<a
				href="/materi?search=bahasa%20inggris"
				class="mt-2 inline-block text-lg font-medium hover:text-lime-600 md:mt-3"
			>
				Bahasa Inggris
			</a>
		</div>
	</div>
</div>
<div class="mt-24">
	<h2 class="text-2xl font-semibold">Materi & Soal Terbaru</h2>
	<div class="mt-4 grid grid-cols-1 gap-6">
		<PostCard />
	</div>
	<div class="mt-10 text-center">
		<a
			href="/materi"
			class="border-b-2 border-lime-600 text-lime-600 hover:border-lime-700 hover:text-lime-700"
			><div
				class="flex items-center justify-center gap-2 transition ease-in-out hover:translate-x-3"
			>
				<p>Lebih banyak lagi</p>
				<p class="text-2xl font-bold">&#11106;</p>
			</div></a
		>
	</div>
</div>
<div class="mt-28 rounded bg-neutral-50 px-10 py-12 shadow-md" id="tentang">
	<h2 class="text-center text-2xl font-semibold">Tentang</h2>
	<p class="mt-4">
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui sunt quos hic repellat, quibusdam
		minima laboriosam sequi sapiente vitae. Exercitationem, pariatur magnam? Officia sapiente libero
		animi laboriosam quibusdam minima vero!
	</p>
	<p class="mt-4">
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui sunt quos hic repellat, quibusdam
		minima laboriosam sequi sapiente vitae. Exercitationem, pariatur magnam? Officia sapiente libero
		animi laboriosam quibusdam minima vero!
	</p>
	<p class="mt-4">
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui sunt quos hic repellat, quibusdam
		minima laboriosam sequi sapiente vitae. Exercitationem, pariatur magnam? Officia sapiente libero
		animi laboriosam quibusdam minima vero!
	</p>
</div>
<div class="my-36 animate-bounce text-center">
	<a href="/#" class=" text-lime-600 hover:text-lime-700"
		><div class="inline-block">
			<p class="text-2xl font-bold">&#11105;</p>
			<p>Kembali ke atas</p>
		</div></a
	>
</div>
