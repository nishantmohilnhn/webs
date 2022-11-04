<script>
    let listOfimg =[
        {title:"snomo" ,src:"https://picsum.photos/700/304"},
        {title:"snomo" ,src:"https://picsum.photos/700/305"},
        {title:"snomo" ,src:"https://picsum.photos/700/306"},
        {title:"snomo" ,src:"https://picsum.photos/700/307"},
        {title:"snomo" ,src:"https://picsum.photos/700/308"}
    ]
</script>
<section class="flex flex-col items-center">
<ul class="flex overflow-x-auto gap-1 snap-x snap-mandatory">
	{#each listOfimg as { title, src }, i}
		<li class="shrink-0 snap-center"><img src="{src}" alt="{title}"> 
        </li>
	{/each}
</ul>
</section>
