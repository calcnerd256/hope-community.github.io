---
layout: index
meeting_weekday: Sundays
meeting_time: 10:30 A.M.
street_address: 1637 Stubbeman Ave
pastor_name: Matthew Beasley
pastor_email: matthewhenrybeasley@gmail.com
---
		<div class="container-fluid" id="home">
			<div class="row">
				<div class="bg-1">
					<div class='cover-text-bg'>
						<p class='cover-text'></p>
						<p class='cover-text-secondary'>Join us {{ page.meeting_weekday }} at {{ page.meeting_time }}</p>
						<p class='cover-text-thirdiary'>{{ page.street_address }}, Norman, OK</p>
						<!--<a class="btn btn-secondary text-black" href="{{ "/visit" | relative_url}}">More Info</a>-->
					</div>
				</div>
			</div>
			<div class='row'>
				<div class='col-md-3'></div>
				<div class='col-md-9 big-info-block'>
					<div class='section-title'>Directions</div>
					<div class='section-text-block'>
						<p>We currently meet at the Union Baptist Association office buidling at {{ page.street_address}}, Norman. It's just to the south of Norman North High School and just north of E Robinson St.</p>
					</div>
				<!--	<div class='section-title'>What To Expect</div>
					<div class='section-text-block'>
						<p>We are a community of people from various backgrounds growing in our commitment to follow Jesus Christ and to actively love our neighbors.</p>

						<p>Our community includes people who have been following Jesus for many years, some who are new to Christian faith, and some who are exploring Christianity for the first time. Regardless of your background, beliefs, or life situation, we would love to have you join us this Sunday.</p>-->
					<div class='section-title'>Contact Us</div>
					<div class='section-text-block'>
						<p>If you would like to know more about Hope Community Church, or want to contact us for any other reason, email {{ page.pastor_name }} at {{ page.pastor_email }}.</p>
					</div>


	<!--				<div class='section-title'>Commonly Asked Questions</div>
					<div class='section-text-block'>
						<p>Throw some Q&A in here.</p>
					</div>-->
				</div>
			</div>

		</div>
