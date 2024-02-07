## Log a ticket page

# Zoho Creator Page Explanation

This Markdown document provides an explanation of the provided code snippet for a Zoho Creator page. The code is meant to create a web page within a Zoho Creator app. The page consists of a header section with a hero banner image and a welcome message, followed by a form section for logging a ticket.

## Provided Code Snippet:

```html
<%{
	%>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,300;9..40,500;9..40,700&display=swap" rel="stylesheet">
<style>
	.zc-pb-tile-container {
		padding: 0px !important;
		border-radius: 0 !important;
	}
	.Layout.elemContainment {
		padding: 0 !important;
		border: none !important;
		border-radius: 0 !important;
	}
	.box {
		border-shadow: none;
	}
	.rowBlocks {
		width: 720px;
		max-width: 100%;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		align-content: center;
		justify-content: center;
		align-items: center;
		margin: 0 auto;
		gap:10px;
		padding-bottom:50px;
	}
	.rowBlocks h1 {
		width: 100%;
		font-family: 'DM Sans', sans-serif;
		font-weight:700;
	}
	.block {
		width: 49%;
		max-width: 100%;
		flex: 0 0 49%;
	}
	.block i {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		align-content: center;
		justify-content: flex-start;
		align-items: center;
		gap: 10px;
	}
	#header {
		position: relative;
		height:420px;
		overflow: hidden;
		max-width:100%;
	}
	.welcome-message {
		padding: 50px;
		width: 720px;
		max-width: 100%;
		margin: -70px auto 0;
		background-color: white;
		line-height: 1.7em;
		z-index: 0;
		position: absolute;
		right: 0;
		left: 0;
	}
	.welcome-message p {
		font-family: 'DM Sans', sans-serif;
		font-weight:300;
	}
	h1 {
		font-size: 25px;
		line-height:1.1em;
		font-family: 'DM Sans', sans-serif;
		font-weight:700;
		padding-left:10px;
	}
	.hero-banner img {
		width: 100%;
		height: 250px;
		object-fit: cover;
		object-position: bottom;
	}
	form[name="Support_Ticket"].label-inplace {
    width: auto !important;
}
	.welcome-header {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-content: center;
    align-items: center;
    justify-content: space-between;
}
i.fa-regular.fa-life-ring {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-content: center;
    justify-content: flex-start;
    align-items: center;
}
i#home-ico {
    font-size: 18px;
    transform: scale(1);
	transition: ease-in-out 0.2s;
	background-color: transparent;
	border-radius: 50%;
	padding:10px 10px 11px;
}
i#home-ico:hover {
    transform: scale(1.2);
	transition: ease-in-out 0.2s;
	background-color: #ef8216;
	padding:10px 10px 11px;
	color:white;
	}
	</style>
	<section id="header">
	<div class="hero-banner">
		<img src="https://res.cloudinary.com/dugqkshbe/image/upload/v1698059855/Client%20Portal/RHi-Banner-Image_byk3b3.jpg" width="100%">
	</div>
<div class="welcome-message">
<div class="welcome-header">
	<i class="fa-regular fa-life-ring"><h1>Log a ticket
</h1></i>
<a href="/#Home"><i elname="sectionIcon" class="zc-li-solid ui-1-home-minimal" id="home-ico" title="Home"> </i></a>
</div>
<p>When you submit a ticket, please allow 48 hours for a response. This ensures that we have the time needed to investigate the issue thoroughly and provide you with the best solution and support.</p></div>
	</section>
	<section id="body">
	<div class="rowBlocks">
	<div elName='zc-component' formLinkName='Support_Ticket' params='zc_Header=false&amp;zc_SuccMsg=Data Added Successfully!&amp;zc_SubmitVal=Submit&amp;zc_ResetVal=Reset'>Loading Form...</div>
	</section>
<%

}%>
```
sdkdf
