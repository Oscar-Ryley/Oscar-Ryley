# Hi, I'm Oscar Ryley :)

**I also go to Hackathons**

<a href="https://oscar-ryley.github.io/map" target="_blank" rel="noopener noreferrer">
	<picture>
		<source media="(prefers-color-scheme: dark)" srcset="https://s.wordpress.com/mshots/v1/https://oscar-ryley.github.io/map?theme=dark&w=480" />
		<img alt="Hackathon map" src="https://s.wordpress.com/mshots/v1/https://oscar-ryley.github.io/map?w=480" width="480" />
	</picture>
</a>

<!-- Layout: map (left) + stats card (right) -->
<table>
	<tr>
		<td valign="top">
			<!-- left column: map (kept above) -->
		</td>
		<td valign="top" style="padding-left:18px;">
			<!-- STATS CARD START - edit the numbers inside the <text> elements with the matching id attributes -->
			<svg xmlns='http://www.w3.org/2000/svg' width='320' height='200' viewBox='0 0 320 200' role='img' aria-label='Hackathon stats card' style='border-radius:8px'>
				<defs>
					<linearGradient id='g' x1='0' x2='1'>
						<stop offset='0' stop-color='#4c566a'/>
						<stop offset='1' stop-color='#2e3440'/>
					</linearGradient>
				</defs>
				<rect width='100%' height='100%' rx='10' fill='url(#g)' />
				<text x='20' y='34' fill='#eceff4' font-size='18' font-family='Inter, Arial, sans-serif'>Hackathon Stats</text>
				<g font-family='Inter, Arial, sans-serif' fill='#d8dee9' font-size='14'>
					<text x='20' y='68'>Total:</text>
					<text id='total' x='220' y='68' text-anchor='end' font-weight='700'>12</text>

					<text x='20' y='98'>MLH Events:</text>
					<text id='mlh' x='220' y='98' text-anchor='end' font-weight='700'>10</text>

					<text x='20' y='128'>HUK:</text>
					<text id='huk' x='220' y='128' text-anchor='end' font-weight='700'>5</text>

                    <text x='20' y='158'>Organised</text>
                    <text id='organised' x='140' y='158' text-anchor='end' font-weight='700'>3</text>

                    <text x='160' y='158'>Volunteered</text>
                    <text id='volunteered' x='300' y='158' text-anchor='end' font-weight='700'>4</text>
				</g>
			</svg>
			<!-- STATS CARD END -->

			<p style="margin-top:8px;margin-bottom:0;font-size:12px;color:#586069">Edit the numbers directly in this file: change the values inside the <code>&lt;text id='...'</code> elements between <!-- STATS CARD START --> and <!-- STATS CARD END -->.</p>
		</td>
	</tr>
</table>
