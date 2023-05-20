[![Contact me on Codementor](https://www.codementor.io/m-badges/boonecabal/im-a-cm-g.svg)](https://www.codementor.io/@boonecabal?refer=badge)

Creating page layout for new_application.py

I figured out how to center a container.  This is the code for it:

```html
<main>
	<div class="container py-3 bg-light" style="height: 81vh">
		<div class="row h-100 justify-content-center align-items-center">
			<div class="col-8 text-center bg-info">
				<h2 class="p-2 flex-fill">Lease Application</h2>
				<p class="p-2 flex-fill">use justify-content utilities on flexbox containers to change the alignment of flex items on the main axis (the x-axis to start, y-axis if flex-direction: column). Choose from start (browser default), end, center, between, around, or evenly.</p>
				<p class="p-2 flex-fill">By using flexbox you can center the entire the column of the grid.</p>
			</div>
		</div>
	</div>
</main>